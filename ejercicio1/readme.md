En Git Bash: 
-----------
pwd
mkdir ejercicios
cd ejercicios
code .

En VSC:
-------
Open File ejercicios 
Terminal
new terminal
//cambio powershell por Git Bash//
//Crear carpeta ejercicio1//

En Git Bash: 
-----------
cd ejercicio1
touch readme.md
git config --global user.mail margal1997@gmail.com 
git config --global user.name "Martha Gallego”
cd ..
git init
git status
git add . 
git commit -m "Version  Inicial"

En VSC:
-------
//Escribir el detalle de la misión en Readme.md//

En Git Bash: 
------------
git add ejercicio1/readme.md
git commit -m "Agrega solución primer ejercicio"

git remote add origin git@github.com:MARGAL1997/aspirantes-mir-ejercicio-1.git
git branch -M main
git push -u origin main

//Enviar el link del repositorio en Github a su mentor(a).//
