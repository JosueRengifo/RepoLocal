//Crear repositorio local
1 Crear la carpeta del repositorio 
2 Abrir la carpeta 
3 Iniciar la consola de git bash
4 git init //iniciar una repositorio en la carpeta seleccionada 
5 Agregar al menos un archivo al repositorio local 
6 git add nombre_primer_archivo 
7 git commit -m "initial commit"
8 // Crear repositorio  github/bigbucket 
9 git add remote origin https://github.com/JosueRengifo/RepoLocal.git url del repositorio creado
10 git push -u origin master


//comandos git 
//verificar estado del repositorio local
git status
//agregar cambios
git add nombre_archivo_modificado
//agregar todos los cambios si se tiene un archivo .gitignore 
git add .
//confirmar cambios  git commit -m "mensaje descriptivo del commit"
//sincronizacion de cambios remoto a local 
//git pull origin nombre_rama
//sincronizacion de cambios local a remoto 
//git pull origin nombre_rama
