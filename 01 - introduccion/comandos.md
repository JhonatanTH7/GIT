# Configuración

Revisar versión de github
git -v
git --version

Comandos para configurar git por primera vez
git config --global user.name "nombre"
git config --global user.email "correo"

Comando para borrar la configuración de git
rm ~/.gitconfig

Comando para ver que usuario esta siendo usado en el momento
git config --global user.name
git config --global user.email
git config --list

Comando para inicializar en un repositorio
git init

Comando para ver el estado de los archivos
git status

Comando para ver las versiones de mi proyecto
git log
git log --oneline

Comando para cambiar entre versiones o ramas
git checkout <Nombre de la rama o identificador de la versión>

Comando para volver a la versión anterior
git checkout --.

Pasos para crear una version de mi codigo

1. Agregar los cambios
   git add .
   git add *.js
   git add home.html

2. Comprometer los archivos
   git commit -m "Descripción del commit"
