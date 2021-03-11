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

_Si tienes muchos archivos puedes utilizar el comnando_

```
$ git add .
```

## Paso 4: Crea commit (Capturas de tu codigo) ⚙️

_Para crear estas capturas de tu codigo debes utilizar el siguiente comando_

```
$ git commit -m "Mensaje de tu progreso"
```

_En caso de querer actualizar el nombre de este commit, se utiliza_

```
$ git commit -amend
```

_Si es necesario ver el listado de commit, se usa el comando_

```
$ git log --oneline
```

_Si deseas volver a un commit anteriror utiliza el comando_

```
$ git checkout <Nombre del commit>
```
_En cambio si deseas revirtir esas modificaciones, utiliza_

```
$ git reset <Nombre del commit>
```

_Se abrira el editor y procederas a actualizar el nombre del commit, guardaras los cambios y cerraras el editor_

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - El framework web usado
* [Maven](https://maven.apache.org/) - Manejador de dependencias
* [ROME](https://rometools.github.io/rome/) - Usado para generar RSS

## Contribuyendo 🖇️

Por favor lee el [CONTRIBUTING.md](https://gist.github.com/villanuevand/xxxxxx) para detalles de nuestro código de conducta, y el proceso para enviarnos pull requests.

## Wiki 📖

Puedes encontrar mucho más de cómo utilizar este proyecto en nuestra [Wiki](https://github.com/tu/proyecto/wiki)

## Versionado 📌

Usamos [SemVer](http://semver.org/) para el versionado. Para todas las versiones disponibles, mira los [tags en este repositorio](https://github.com/tu/proyecto/tags).

## Autores ✒️

_Menciona a todos aquellos que ayudaron a levantar el proyecto desde sus inicios_

* **Andrés Villanueva** - *Trabajo Inicial* - [villanuevand](https://github.com/villanuevand)
* **Fulanito Detal** - *Documentación* - [fulanitodetal](#fulanito-de-tal)

También puedes mirar la lista de todos los [contribuyentes](https://github.com/your/project/contributors) quíenes han participado en este proyecto. 

## Licencia 📄

Este proyecto está bajo la Licencia (Tu Licencia) - mira el archivo [LICENSE.md](LICENSE.md) para detalles

## Expresiones de Gratitud 🎁

* Comenta a otros sobre este proyecto 📢
* Invita una cerveza 🍺 o un café ☕ a alguien del equipo. 
* Da las gracias públicamente 🤓.
* etc.



---
⌨️ con ❤️ por [Villanuevand](https://github.com/Villanuevand) 😊