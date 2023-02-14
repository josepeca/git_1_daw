# git_1_daw
Ed_Tarea_3_git
### Crear y clonar repositorio
1. Acceder a GitHub con usuario y contraseña
2. Crear repositorio git_1_daw,ED_Tarea_3_git,public,añadir README.md
3. Abrir terminal,pwd,/home/usuario
4. cd repositories
5. git init
6. git clone git@github.com:josepeca/git_1_daw.git 
### Commit inicial 
1. gedit README.md introducir pasos Crear y clonar repositorio
2. git commit -am "commit inicial"
### Push inicial
1. git push
### Ignorar archivos
1. touch .gitignore
2. touch privado.txt
3. mkdir privada
4. gedit ,gitignore
### Añadir 1.txt
1. touch 1.txt
2. git add 1.txt
### Crear el tag v0.1
1. git tag -a v.01 -m "version v.01 Tarea 3"
2. git commit -am "Añadir fichero 1.txt y tag v.01 Tarea 3"
### Cuenta de GitHub
1. Buscar en github.com usuarios de la clase
2. Pulsar follow 
3. En cada repositorio pulsar star
### Crear una tabla
|NOMBRE|GITHUB|
|---|---|
|Abrahan|[arodmor789](https://github.com/arodmod789)|
|Antonio|[anuncar621508](https://github.com/anuncar621508)|
|David Gal|[Dagalca](https://github.com/Dagalca|)|
### Crear colaborador
1. Situado en el repositorio pulsar Setting
2. Pulsar Collaborators y Add people
3. Introducir jmerlop327 y agregar
4. Pendiente de recibir la confirmacion de la invitacion
### Crear Rama y añadir fichero
1. git checkout - b v0.2
2. touch 2.txt
3. git add 2.txt
4. gedit README.md
5. git commit -am "Añadir fichero 2.txt y rama v0.2"
6. git push
### Merge directo
1. checkout main
2. git merge v0.2 -m "Fusion de main v0.2"
### Merge con conflicto y arreglo
1. gedit 1.txt
2. git commit -am "Añadir Hola al archivo 1.txt
3. git push
4. checkout v0.2
5. gedit 1.txt
6. git commit -am "Añadir Adios al archivo 1.txt"
7. git push
8. git checkout main
9. git merge v0.2
10. git merge --abort
11. git status
12. gedit 1.txt
13. git commit -am "Solucion conflicto"
14. git push
15. git merge v0.2
### Borrar rama
1. git tag -a v0.2 -m "version v0.2 Tarea3"
2. git connit -am "Añadir version v0.2 Tema 3"
3. git push
4. git branch -D v0.2
5. git push
### Listado
1. git log --graph --all --oneline
2. git add README.md
2. git commit -am "Añadir comandos usados"
