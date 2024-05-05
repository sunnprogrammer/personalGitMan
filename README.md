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

