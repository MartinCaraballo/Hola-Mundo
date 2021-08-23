:tada: Martín Caraballo

git config --global init.defaultBranch main

git init Hola-Mundo

cd Hola-Mundo
code .

git status

git add .

git status

git commit -m "Commit Inicial"

git config --global user.email "martin.caraballo@correo.ucu.edu.uy"

git config --global user.name "MartinCaraballo"

git commit -m "Commit Inicial"

git remote add origin https://github.com/MartinCaraballo/Hola-Mundo.git

git pull origin main --allow-unrelated-histories

git branch --set-upstream-to=origin/main main

git push

del README.md

del .gitignore

git clone https://github.com/MartinCaraballo/Hola-Mundo.git

git branch dev

git checkout dev

git status

git add .

git commit -m "Cambios en la rama"

git push origin dev

git checkout main

git merge dev

git push

git branch -d dev





