# Ramas y fusiones

| Comando | Descripción |
| ------- | ----------- |
| `git branch` | Muestra una lista de las ramas que existen en el proyecto (el asterisco señala la rama activa) |
| `git branch -a` | Muestra una lista de todas las ramas (locales y remotas) |
| `git branch [nombre de la rama]` | Crea una nueva rama |
| `git branch -d [nombre de la rama]` | Elimina una rama local |
| `git push origin --delete [nombre de la rama]` | Elimina una rama remota |
| `git checkout -b [nombre de la rama]` | Crea una nueva rama y se desplaza hasta ella |
| `git checkout -b [nombre de la rama] origin/[nombre de la rama]` | Clona una rama remota y se desplaza hasta ella |
| `git branch -m [nombre de la rama antigua] [nombre de la rama nueva]` | Renombra una rama local |
| `git checkout [nombre de la rama]` | Cambia a una rama concreta |
| `git checkout -` | Cambia a la última rama activa |
| `git checkout -- [nombre-del-archivo.txt]` | Descarta cambios en un archivo |
| `git merge [nombre de la rama]` | Combina una rama con la rama activa |
| `git merge [nombre de la rama de origen] [nombre de la rama de destino]` | Combina una rama de origen con una rama de destino |
| `git stash` | Guarda temporalmente los cambios locales no confirmados |
| `git stash clear` | Elimina todas las entradas del stash |
