# moment1_webb3

## 1 Versionshantering 
### 1.1 Kortfattat om syftet med versionshantering
Syftet med versionshantering är att strukturera koden till utvecklingen av mjukvara/webbutveckling. En viktig sak är att kunna utveckla tillsammans med andra är at kunna dela kod och jobba med olika delar av ett projekt. Där kommer versionshantering in som en viktig och nödvändigt arbetsredskap för att få det praktiskt att fungera. 
Att dela upp koden i olika versioner gör det mycket enklare att testa nya funktioner man bygger och kunna gå tillbaks om det blir fel osv, det oavsett om man utvecklar själv eller i grupp.
### 1.2 Beskrivning av tre olika VCS.
**Git:**
* Syfte = Ursprungligen att hantera källkoden till Linux, har sedan växt och utvecklats.
* Utvecklare = Linus Torvalds
* Utvecklingsår = 2005
* Licens = Gratis, baserat på öppen källkod.
* Övrigt = Är ett distribuerat versions kontroll-system. Det innebär att hela koden och dess versioner är speglad på utvecklares datorer.

**Concurrent Version System (CVS):**
* Syfte = Ett verionshanteringssystem med syfte att kunna tillbaks till tidigare moment i kodandet av systemet. Att förenkla för fler personer att utveckla i samma projekt.
* Utvecklare = Dick Grune
* Utvecklingsår = 1986
* Licens = Open source under GNU licens. GNU står för General Public License.
* Övrigt =  Är ett centralt versionshanteringssystem.

**Subversion:**
* Syfte = Syftet med projektet Subversion var att skapa ett open-source versions-kontroll-system som skulle fungera till stora delar som det väletablerade Concurrent Version System (CVS) fast med fixade buggar och tillagd funktionalitet
* Utvecklare = CollabNet inc
* Utvecklingsår = 2000
* Licens = Gratis, baserat på öppen källkod under Apache licens.
* Övrigt = Är ett centralt versionshanteringssystem. Dvs alla utvecklare laddar upp ändringar till ett centralt repo som fungerar som den centrala kopian på hela koden.  Under 2009 så blev togs projektet under Apache Incubators vingar och processen för att blir ett standard-top-Apache projekt kom igång vilket realiserades 2010. Därefter kallas det också Apache Subversion. Detta betyder att man Apaches stora ekosystem av utvecklare som jobbar med projektet.

## 2 Om Git
**Förklara följande begrepp:**
* Workspace =  Är själva  mappen på din dator där filerna som du programmerar i ligger. Här sker själva kodandet.
* Staging area = Är platsen där ändringar placeras innan de sparas/commitas till repon. Du kan välja enskilda filer att staga, filtyper eller alla filer
* Local repository = En lokal repo (repository) är din och bara din repo. Ingen har tillgång eller ser denna förutom du.
* Remote repository = Är en public repo som de andra som utvecklar samma projekt ser. Att dela via github är ett vanligt tillvägagångssätt.
* Branch = Är en gren av repot. Vanligt att man splittar upp utvecklingen i flera grenar när man utvecklar helt nya delar exempelvis
* Merge = När man sammanfogar grenarna (brancherna) av repot igen.
 
**Beskriv följande kommandon:**
* git config = Här ställer man in inställningar i git som exempelvis användarnamn och e-postadress.
* git init = Initierar (skapar) ett repo. 
* git status = Visar vilka filer i den branschen du står i som har blivit ändrat och vilka som har förberetts för commit.
* git add = Adderar ändringar som du vill skall följa med när du sparar/gör commit till en bransch. Genom att skriva git add /filsökväg/filnamn så lägger du till en enskild fil, med git add *filtyp lägger du till alla filer av en viss typ och med gid add . Så lägger du till alla gjorda ändringar.
* git commit = Sparar ändringarna till branschen du står i.
* git push = Flyttar ändringarna även till den externa repon
* git checkout = Man loggar ur från en bransch. I kombination men andra kommandon kan man byta bransch och skapa en ny ( git checkout -b nytt branchnamn)
* git pull = Används för att hämta och fetcha innehåll från en extern repo till att uppdatera en lokal repo.
* git merge  = Sammanfogar två olika brancher med varandra igen.
* git fetch = Laddar ner commits, filer från en extern repo till en lokal repo.
* git log = Visar historiken av alla brancher och deras commits.
