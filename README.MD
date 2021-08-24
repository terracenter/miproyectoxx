# Udemy Curso Completo de Git y github para principiantes
### Referencia
[Curso completo de git y github para principiantes](http://https://www.udemy.com/course/curso-completo-de-git-y-github-para-principiantes/l "Curso completo de git y github para principiantes")

### Contenido
- ##### Configurar el git en el pc 
```bash
    git config --global user.name "**Tu_usuario**"
    git config --global user.email "**TuCorreo**"
```
- ##### Inicicializar el proyecto
```bash
git init
```
- ##### Ver el estado del proyecto
```bash
git status
```
- ##### preparar archivos para enviarlos al reposotorio
```bash
git add Nombrerchivo
git add . (todos los archivos)
```
- #####  Sacar archivos antes de envialos al repositorio, lo contrario a ***git add***
```bash
git rm --cache NombreArchivo
```
- ##### Ignorar archivos para no ser enviados al repositorio, dentro del archivo .gitignore se coloca todo lo que se quiera ignorar
```bash
touch .gitigore
```
- ##### Ver el log en un sola linea
```bash
git log --online
```
- ##### Cambiar a una version anterior usando el datos de git log --online,  Esta opcion es MUY PELIGROSA, ya que puede perder codigo.
```bash
git checkout 14b0284
```
- ##### Ver cuantas ramas hay
```bash
git branch
```
- ##### Ira la rama master
```bash
git checkout master
```
- ##### Creacion de una nueva rama
```bash
git checkout -b ramafooter
```
- ##### Unir ramas 
```bash
git merge ramafooter
```
- ##### Elimnacion de ramas
```bash
git branch -d ramafooter
```
- ##### push an existing repository from the command line
git remote add origin git@github.com:terracenter/miproyectoxx.git
git branch -M main
git push -u origin main

##### **NOTA**: Es recomendable enviar al servidor remoto (control de versiones) por lo menos una ves al dia los cambios realizados al codigo, depues de cada commit