# Comandos básicos GIT

## git config --global user.name "nombre"
+ Se usa para vincular los commits a tu nombre.
+ Se puede establecer o cambiar el nombre de usuario utilizando el comando **git config**.

## git config --global user.email "mail@gmail.com"
+ Se usa para vincular la dirección de correo electrónico asociado a tus commits.  

## git init
+ Se usa al iniciar un proyecto.
+ Crea un subdirectorio *.git* en el directorio de trabajo actual.

## git status
+ Permite ver que cambios han sido puestos en escena, cuales no, y que archivos no están siendo rastreados por Git.
+ Muestra el estado del directorio de trabajo y del área de preparación.

## git commit -m "mensaje"
+ Guarda los cambios en el repositorio local. 

## git add .
+ Añade todos los archivos. 

## git add nombrearchivo.js
+ Añade el archivo indicado en el nombre. 

## git log
+ Muestra el histórico de commits.
+ Indica el identificador del commit, autor, fecha de realización y mensaje enviado.

## git log --oneline
+ Muestra cada confirmación en una sola linea.
+ Permite que veamos mas cantidad de commits en pantalla y facilita mucho seguir la secuencia.

## git log -5
+ Muestra la cantidad determinada de commits.

## git branch nombre_rama
+ Permite crear una rama nueva.

## git checkout -b nombre_rama
+ Permite crear una rama nueva y al mismo tiempo te lleva a esa rama nueva.

## git branch -m nuevo_nombre
+ Cambia el nombre de la rama actual. 

## git branch -m nombre_antiguo nombre_nuevo
+ Permite cambiar el nombre de una rama.
+ Para poder hacer esto, no hay que estar parado en la rama.

## git branch -d nombre_rama 
+ Elimina la rama localmente.
+ Se debe estar fuera de dicha rama.

## git push origin --delete nombre_rama
+ Empuja os cambios a remoto informando de la eliminación de la rama al repositorio de origen remoto.
+ Se tiene que usar con el comando anterior (git branch -d nombre_rama).

## git restore somefile.js
+ Ayuda a deshacer/descartar los cambios locales no comprometidos.

## git stash
+ Toma los cambios sin confirmar, los guara aparte para usarlos mas adelante y acto seguido los deshace en el código en que se esta trabajando. 

## git stash pop
+ Aplica los cambios previamente guardados con el comando anterior (git stash).

## git fetch
+ Descarga commits, archivos y referencias de un repositorio remoto a tu repositorio local.
+ Permite ver como ha progresado el historial central, pero no te obliga a fusionar los cambios en el repositorio local.

## git pull
+ Extrae y descarga contenido desde un repositorio remoto y actualizar al instante el repositorio local para reflejar ese contenido.

## git pull origin nombre_rama
+ Descarga los cambios de la rama señalada.

## git push
+ Carga/sube contenido del repositorio local a un repositorio remoto.

## git push origin nombre_rama
+ Sube los cambios a la rama especificada.
+ Si ya se tiene la rama en remoto pero esta se modifico en local, este comando actualiza la rama en remoto.
