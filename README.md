# CursoGit

_Este pequeño curso pretende guiarlos para la utilizacion de una de las herramientas primordiales al momento de conmenzar la estructuracion y construccion de un proyecto, dando a conocer los comandos que pueden llegar a necesitarse en algun en algunas de las funciones de Git._

Mira * [Descarga](https://git-scm.com/downloads) - para comenzar.
Mira * [GitHub](https://github.com/join) - para crear una cuenta.

## Paso 1: Configurar Git ⚙️

_Una vez instalada la consola de Git Bash en nuestro ordenador y creada la cuenta en GitHub, abres la consola donde quieras iniciar el proyecto_
_Confirguramos el usuario y el email con los siguientes comandos_

```
$ git config --global user.name <user>
```
```
$ git config --global user.email <email>
```

```
$ git config --global core.editor <editor>
```

_Para verificar que se haya ingresado la informacion correcta usa_

```
$ git config --list
```
_Para finalizar la verificacion presiona la letra "q"_

## Paso 2: Crear un repositorio local ⚙️

_Para crear un repositorio loca, debes ubicar la carpeta donde sera contenido y utilizas el comando_

```
$ git init
```

_Esto inicializar las funcionalidades basicas de git en este primer proyecto, posteriormente empieza a crear los archivos y a modificarlos para comprobar el estatus de estos archivos utiliza el_

```
$ git status -s
```
## Paso 3: Modifica y agrega archivos ⚙️

_Si tienes archivos modificados recientemente, mediante este comando git te lo hara saber, para que esos cambios que se pudieron realizar se actualicen usa el comando_

```
$ git add <nombre del archivo>
```

_Si tienes muchos archivos modificados o creados puedes utilizar el comnando_

```
$ git add .
```

## Paso 4: Crea commit (Capturas de tu codigo) ⚙️

_Para crear estas capturas de tu codigo debes utilizar el siguiente comando_

```
$ git commit -m "Mensaje de tu progreso"
```
_Si es necesario ver el listado de commit, se usa el comando_

```
$ git log --oneline
```
_En caso de querer actualizar el nombre de este commit, se utiliza_

```
$ git commit -amend
```
_Se abrira el editor y procederas a actualizar el nombre del commit, guardaras los cambios y cerraras el editor. Si deseas volver a un commit anteriror utiliza el comando_

```
$ git checkout <Nombre del commit> 
```
_En cambio si deseas revirtir esas modificaciones, utiliza_

```
$ git reset <Nombre del commit>
```
## Paso 5: Crear tags (etiquetas para identificar partes del codigo) ⚙️

_Una vez hayas avanzado lo suficiente y creas que debes hacer una version del sistema, utliza las "tags" (etiquetas), estas permitiran guardar los commits se han creado hasta el momento y funcionando como un puntero hacia un commit especifico_

```
$ git tags
```

_Si deseas crear una tag usaras el comando, que guardara una etiqueta anotada_


```
$ git tag -a <version> -m "descripcion"
```

_O si es necesario hacer una etiqueta ligera_


```
$ git tag -a <version>
```

## Paso 6: Subir tu repositorio local a la web de github ⚙️

_Debes tener una cuenta Github creada y un repositorio tambien, una vez hecho esto debe utilizar el comando_

```
$ git remote add orgin https://github.com/repositorio.git
```
_Una vez establecida la conexion con el repositorio web, debes utilizar el comando_

```
$ git push -u origin master
```
_Para sincronizazr todos los cambios y por fin tener subido el repositorio local_


## Paso 7: Clonar un repositorio web a local ⚙️

_Si deseas clonar un repositorio web debes iniciarlizarl primero, si_

```
$ git remote add orgin https://github.com/repositorio.git
```
_Una vez establecida la conexion con el repositorio web, debes utilizar el comando_

```
$ git push -u origin master
```
_Para sincronizazr todos los cambios y por fin tener subido el repositorio local_

## Paso 7: Crear branch, modificarlos y unificarlos ⚙️

_Para crear una branch (rama) debes utilziar el comando_

```
$ git branch <branch>
```

_Para ver las ramas que ya se han creado, utiliza_

```
$ git branch O git show-branch 
```

_Para moverse de una rama a otra_

```
$ git checkout <branch> 
```

_Para fusionar ramas_

```
$ git merge experimental -m 'descripcion'
```

_Para fusionar los cambios con la rama principal_
```
$ git merge master -m 'descripcion'
```

_Para eliminar una rama_
```
$ git branch -d <branch>
```

_Cargar la rama en el repositorio remoto_
```
$ git push -u origin <branch>
```

## Autores ✒️

* **Andrés Villanueva** - *Trabajo Inicial* - [villanuevand](https://github.com/villanuevand)
* **Pildoras Informaticas** - *Documentación* - [pildorasinformaticas](https://www.youtube.com/watch?v=ANF1X42_ae4&list=PLU8oAlHdN5BlyaPFiNQcV0xDqy0eR35aU)

---
⌨️ con ❤️ por [Villanuevand](https://github.com/Villanuevand) 😊