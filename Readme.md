1- instalar git git-scm.com/
identificar que git esté bien instalado comando git version-- comando "git help" les da los commandos más usados con una breve descripción
ir a la carpeta del proyecto
de manera visual posicionarse en la carpeta click derecho y click en abrir con git bush
desde la consola comando, cd y escriben la ruta local absoluta de la carpeta de su proyecto. ej cd /users/natalia/desktop/coderhouse/git
iniciar git, comando git init
luego configurar, comando git config --global user.name "su nombre"
comando git config --global user.email "su email"
comando git config --list configurar todos los datos que les pide y esto compueba si esta okey la configuracion
comando git status ap2arecen archivos en rojo
comando git add (y escribir el nombre del archivo, para subir de a uno) git add . (para subrir todos los archivos de esa carpeta juntos)
comando git status aparecen los archivos en verde
comando git commit -m "comentario de la accion que estan subiendo"
comando git log les muestra el historial de los commit que hicieron
comando git log --oneline --decorate --all --graph es igual que el comando anterior resumido en una version mas corta
comando git diff para ver los cambios y movimientos
comando git branch -l rama base , rama master
comando git branch (nombre de la rama) aparece la rama master y la nueva rama creada
comando git checkout (nombre de la rama) para transladarse a esa rama y trabajar en esa bifurcación
comando git log les muestra el historial de los commit que hicieron copiar el id del commit al que quieren volver
comando git checkout para ir una versión atrás
comando git checkout (escribir el id del commit al que desean volver)
comando git merge (escribir el nombre de la rama que quiero fusionar) para fusionar (juntar) varias ramas

---

# en el github crear nuevo repositorio

elegir un nombre y crear

abrir la carpeta del proyecto

poner el comando git init ( si no tiene aún el repositorio en github)
