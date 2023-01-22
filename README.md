Desktop jobb klikk: Git Bash here - Terminál megnyitása

git init - git inicializálása.

code . - Visual Studio Code indítása

git clone https://github.com/szabopeter92/git-vizsga0104 - Vizsga feladat klónozása a github-ról. Ezután mappa átnevezése.

git add . - Létrehozott README.md és .gitignore hozzáadása a staging area-hoz.

git branch console - Console ág létrehozása.

git checkout console - Console ágra átlépés.

git add . - A feladatban meghatározott app.js-ben történt változtatás hozzáadása a staging area-hoz.

git status - Local repo ellenőrzése.

git commit -m "A console branchen az app.js módosítva, console.log üzenet hozzáadva." - Kommitolás a local repoba.

git add . - A feladatban kiírt style.css-ben történt változtatás hozzáadása a staging area-hoz.

git status - Local repo ellenőrzése.

git commit -m "A style.cssben a body background módosítva." - Kommitolás a local repoba.

git add . - README.md file kitöltése, hozzáadása a staging area-hoz.

git status - Local repo ellenőrzése.

git commit -m "Minden kész, README.md kitöltve." - Kommitolás a local repoba.

git remote remove origin - Clone miatt meglévő remote origin törlése.

git remote add origin https://github.com/vojtillal/git-vizsga-0121-vojtillal.git - Github-on létrehozott remote repo megadása.

git remote -v - Remote repo kilistázása. (Végre működik... :P)

git checkout main - Main ágra átlépés.

git push -u origin main - Main ág felpusholása a remote repoba.

git checkout console - Console ágra átlépés.

git push -u origin console - Console ág felpusholása a remote repoba.