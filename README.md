git clone git@github.com:pamadob/git_1_daw.git


touch README.md


git add README.md
git status


git commit

ERROR [*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.]




git init
git config user.name "usuario"
git config user.email ""
git add
git commit -m "Comentario"



git push


touch privado.txt

mkdir privada


echo "privado.txt" > .gitignore
echo "/privada" > .gitignore
git add .gitignore
git commit -m "añadido fichero .gitignore"

touch 1.txt
git add 1.txt
git commit -m "añadido 1.txt"

git push


git tag v0.1
git push




| NOMBRE | GITHUB |
| ----------- | ----------- |
| Miguel | https://github.com/fpertru695 |
| Andrés | https://github.com/AndresGilR/ | 


git branch v0.2
git checkout v0.2

touch 2.txt
git add 2.txt
git commit -m "añadido 2.txt"


git push origin v0.2



git checkout master
git merge v0.2 -m "merge v0.2 sin conflictos"



git checkout master
echo "Hola" >> 1.txt
git add .
git commit -m "hola en 1.txt"






git push origin v0.2
echo "Adios" >> 1.txt
git add 1.txt
git commit -m "adios en 1.txt"


[git checkout master
git merge v0.2
vim 1.txt   (En este punto no consegui salir del editor de texto (:wq) y tuve que cerrar el terminal)(originandose asi problemas en los que no me dejaba continuar)

git reset --merge]



git checkout master
git merge v0.2
vim 1.txt
git add .
git commit -m "arreglado merge en 1.txt"



vim 1.txt
git add .
git commit -m "arreglado merge en 1.txt"




git tag v0.2
git branch -d v0.2



touch equipo.md
git add equipo.md
git commit -m "subiendo equipo"
git push

