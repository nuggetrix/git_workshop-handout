

Das verteilte Sourcecode-Verwaltungs-System GIT soll im IT-DLZ des
Landesamtes für Digitalisierung, Breitband und Vermessung das bisher
eingesetzte Werkzeug SVN ablösen. Einsatzbereiche sind insbesondere
Java-Entwicklung, C#-Entwicklung mit dem TFS sowie Verwaltung von TestSkripten.

Dazu sollen die Mitarbeiter der Softwareentwicklung sowie des Test Centers
im Umgang mit dem neuen Werkzeug sowie Migrationsmöglichkeiten der
bestehenden Projekte von SVN geschult werden. Der Schulungsinhalt sollte an
ein bis zwei Tagen zu vermitteln sein, aufgrund der Teilnehmerzahl sollte die
Schulung an drei Terminen an verschiedenen Wochentagen verteilt auf zwei bis
drei Wochen stattfinden, entweder bei einem Anbieter in München oder im Haus
in unserem Schulungsraum. Die Schulungen sollen Anfang März beginnen. 


- Dezentrale Versionsverwaltung im Team
 Grundlagen Workflows
- Clients
 Git GUI, Git Bash Tortoise Git
 Eclipse Integration Visual Studio
- Repositories
 Ein Git Repository anlegen Repository aus Github klonen
 und bearbeiten Subversion Repository (SVN) nach Git importieren
 Fehlersuche
 Historie
 Integrationsmöglichkeiten zu JIRA und Bamboo bzw. in den TFS
- Arbeiten mit Git
 Add / Stage / Commit / Push Undo / Reset / Rebase Tags
- Branching und Merging
 Was ist ein Branch? Update und Merge Erfolgreiche Strategien
- Plattformen
 GitHub BitBucket Team Foundation Server (TFS)
 Visual Studio Team Services (VSTS)


# Telefonat Bachert



# Ablaufplan
Geschichte der Versionskontrolle (45) - ppt

Git Installation & Configuration 
## Ubung installation  (45)


## Übung der Teilnehmerliste
- Checkout Teilnehmerliste
- Hinzufügen eines Info files deinname.json
- Pushen des Files 

Est 11 Uhr 

## GIT Architektur ( ?? )

Mittag

## Git Befehle
- Repo anlegen 
- Git Add
- Andere version

## Rezepte Anlegen

## Branches   
Übung Branches Anlegen


(ca 15 Uhr Kaffee)
## Stände Vergleichen 
(vergleichen zwischen zwei branches)


## Tree-Ish

Übung Stände vergleichen

# Tag 2 

## Command Line or Git Tool   

## Github Archologie 

## Git Plattformen

## Special Moves

## Migration

## Git im Workflow





##Inhalte

#Geschichte der Versionskontrolle
Geschichte der Versionskontrolle (8)


Git Installation & Configuration (4)

## Übung der Teilnehmerliste
- Checkout Teilnehmerliste
- Hinzufügen eines info files
- Pushen des Files

#Die Architektur von GIT
 -Git Checksums
(Bild aufmahlen) Working Copy, Staging, Repository,    Remote
git sha / commit number
- Parents etc one commit parent of each other
- Daten integrität
- Staging directory

#Git Befehle
- init 
   bare
- add 
- commit
- remove
- delete
- ignore
.gitkeep
.gitignore



#Stände mit Git
- git diff
- Delete files
- Move files


#Branches
- checkout
- clone
branch -m   "move / rename"
branch -d löscht gemergten branch
branch -D forced Delete (auch nicht gemerged)


(14 Uhr)
#Command Line or Git Tool   
 - the command line
 - tortoise git
 - integration into Intelli J
 - integration into Visual Studio
 - integration into Visual Studio Code
 - integration into Eclipse

# Remotes 


# Github Archologie 


# Uebung Rezepte (15 Uhr )





#Tag 2

(15 Uhr)
# Git Plattrofmen
-GitHub 
-Visualstuido Online
-Bitbucket 
-Gitlab


# Git Stash
git stash --save 
git reset --hard
git revert 


#tree-ish

#Git Integration
  - Jira, Babboo, TFS 


#reset
HEAD
revert 

#tagging



#conflicts
-the hard way 

#bare 
make it bare ? 


# Authorization 
- SHH Keys
- User Name / Password
- HTTPS vs SSH


#Git and open source
- Pull Requests
- Forking
- Project on Github


#ignore or not to ignore
Git und Builds Systeme 
- beispiel NPM

#Github Archologie
OpenSource und Git
- contributors
- pull requests
- push 
Aufgabe: Checke dein Lieblingsprojekt aus
Aufgabe: Finde einen pending "pull request" der einen bug fixt
Aufgabe: Review den letzten commit
Aufgabe: Finde den branch für einen nightly build


#Viewing History
-Git Blame
-History
- Git & Ticketsystem

#Special Moves
Rebase
- Partial Rebase
- Merging History
cherry pick



#Migrating 

SVN - https://www.atlassian.com/git/tutorials/migrating-overview
- https://gist.github.com/barrysteyn/2ba947313e0a4ad086c3
- Continious Migration (Paralelbetrieb)
TFVC to GIT 
- https://docs.microsoft.com/en-us/vsts/git/import-from-tfvc

#Continious Integration workflow 
- Tagging a Release
- Automatic Testing process
- Automatic deployment process



Links 
Git Architecture
https://blog.angularindepth.com/become-a-git-pro-by-learning-git-architecture-in-15-minutes-9c995db6faeb
