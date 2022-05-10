#Hello
…or create a new repository on the command line
echo "# test" >> README.md #fájl létrehozása az első sorba "# test" kerül
git init #a git mappa incilizálása
git add README.md #staging changes, azaz a változtatások jóváhagyása, és megjelölés beküldésre 
git commit -m "first commit" #változtatások jóváhagyása, és megjelölés beküldésre
git branch -M main #a fejlesztési ág átnevezése main-re
git remote add origin https://github.com/falusiflowfc/test.git #távoli repo hozzáadása origin néven
git push -u origin main # a fejlesztési ág feltöltése első alkalommal 
…or push an existing repository from the command line
git remote add origin https://github.com/falusiflowfc/test.git
git branch -M main
git push -u origin main #feltölti az origin nevű távoli repo-ba a commitokat
git pull origin main #origin main lehívása
További terminál parancsok:
git pull origin main # a friss repo letöltése
git remote -v #aktuális távoli repo lekérdezése
git status # change , stage, commit állapotának lekérdezése
git  config --global --list #globális beállítások listázása
cd #ChangeDirectory
cd.. #egy mappával felljebb lép
mkdir <directory name> #make directory
rmdir <directory name> #remove directory
  ls #list - könyvtár listázása