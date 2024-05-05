<h1 style="text-align: center;">Manual Personal de Git</h1>

# Introducción
Git es un sistema de control de versiones distribuido, Git nos permite a los desarrolladores llevar un registro de los cambios en nuestros proyectos.
# Comandos de git
## git init
Este comando inicializa git en el repositorio actual en el que te encuentras
```bash
git init
```
## git init nombreRepo
Este comando inicializa git en el repositorio 'nombreRepo'
```bash
git init nombreRepo
```
## git status
Este comando muestra el estado del repositorio, es decir que archivos se han modificado o que archivos estan en la zona stage listos para hacer commit.
```bash
git status
```
## git add
Este comando permite agregar archivos a la zona staged para posteriormente hacer commit de dichos archivos.
```bash
git add
```
## git commit
Este comando permite confirmar todos los cambios, es decir confirma todos los archivos modificados que estan en la zona staged.
```bash
git commit -m "add: comando ejemplo"
```
## git branch nombreRama
Este comando permite crear una rama con el nombre nombreRama
```bash
git branch nombreRama
```
## git checkout -b nombreRama
Este comando permite crear una rama con el nombre nombreRama y a la vez pasar a esa rama creada.
```bash
git checkout -b nombreRama
```
## git branch
Este comando muestra las ramas existentes localmente
```bash
git branch 
```
## git switch
Este comando permite cambiar entre ramas
```bash
git switch nombreRama
```
## git branch -d nombreRama
Este comando permite eliminar una rama
```bash
git branch -d nombreRama
```
## git --graph --online
Este comando permite visualizar los commits hechos de manera mas resumida y grafica
```bash
git --graph --online
```
## git merge  nombreRama --no-ff
Este comando se utiliza para forzar la creación de un commit de fusión incluso cuando Git podría hacer una fusión "fast-forward".
```bash
git merge nombreRama --no-ff
```
## git merge nombreRama
Este comando se utiliza para fusionar la rama actual con la rama nombreRama, se hara merge en la rama actual, es la rama nombreRama se fusiona en la rama actual donde nos encontremos.
```bash
git merge nombreRama
```
## git merge --abort
Este comando permite abortar un merge.
```bash
git merge --abort
```
## git clone URL_del_repositorio
Este comando permite clonar un repositorio de github.
```bash
git clone <URL_del_repositorio>
```
## git remote add origin <URL_del_repositorio_remoto>
Este comando permite agregar un origen al repositorio, es decir un alias al repositorio remoto.
```bash
git remote add origin <URL_del_repositorio_remoto>
```
## git remote -v
Este comando permite verificar si se agrego correctamente el alias al repositorio.
```bash
git remote -v
```
## git push origin nombreRama
Este comando permite subir cambios a la rama nombreRama en el repositorio remoto.
```bash
git push origin nombreRama
```
## git fetch nombreRemoto
Este comando trae todos los cambios de nombreRemoto a nuestra rama local, pero no los fusiona.
```bash
git fetch nombreRemoto
```
## git pull <nombre_remoto> <nombre_rama_remota>
Este comando trae todos los cambios de nombreRemoto a nuestra rama local y los fusiona.
```bash
git pull nombreRemoto nombreRamaRemota
```
## git remote prune <nombre_remoto>
Este comando limpia aquellas ramas que que se eliminaron del repositorio remoto, pero que aun estan presentes en el repositorio local, las limpa.
```bash
git remote prune nombreRemoto
```

