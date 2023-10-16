# Ejercicio de clase

## modificación de clase

Pasos para clonar un repositorio
1. Abrimos la terminal
2. Abrimos el repositorio que queremos copiar de git hub
3. En la terminal ponemos **$ git clone -o pruebasReadme https://github.com/danielcastelao/pruebasReadme**
4. Nos ubicamos en la carpeta clonada **$ cd audacity**
5. Creamos nuestro repositorioen git hub
6. Lo añadimos en la terminal **$ git remote add origin https://github.com/miusuario/mirepo.git**
7. Luego con **$ git remote -v** vemos los repositorios copiados configurados
    origin  https://github.com/SusanaSantosM/clonamosPruebas.git (fetch)
    origin  https://github.com/SusanaSantosM/clonamosPruebas.git (push)
    pruebasReadme   https://github.com/danielcastelao/pruebasReadme.git (fetch)
    pruebasReadme   https://github.com/danielcastelao/pruebasReadme.git (push)
8. Ahora podemos subir cualquier modificacion al repositorio con **git push -u origin master**
9. En caso que el autor modifique el codigo de su repositorio lo podemos lo actualizariamos con un pull **$ git pull --rebase repo_auda master**
