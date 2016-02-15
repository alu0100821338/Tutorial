# Práctica 1. Tutorial  

A continuación encontramos un pequeño tutorial que recoge los primeros pasos en **Procesadores de Lenguaje**. Además, abarca la instalación y puesta en marcha del conjunto de ***herramientas*** con las que trabajaremos este curso:

  1. Node.JS
  2. express
  3. GitHub
  4. Atom
  5. Cloud9
  6. Gh-Pages


### Instalacion node.JS

  Node.js es un entorno *Javascript* del lado del servidor, *basado en eventos*. Aprovechando el motor V8, node proporciona un entorno de ejecución del lado del servidor que compila y ejecuta javascript a **altas velocidades**, permitiendo desarrollar aplicaciones con múltiples conexiones simultáneas.

  Para instalar **node.js**, necesitamos descargar el paquete para la plataforma requerida:  [nodejs](https://nodejs.org/en/).

 En windows, una vez descargado y realizados los pasos del asistente de instalación obtenemos la siguiente consola de comandos.

 ![](http://i64.tinypic.com/11qps9d.png)


### Instalacion express

  **Express** es una infraestructura de aplicaciones web *Node.js* mínima y flexible que proporciona un conjunto sólido de características para las aplicaciones web y móviles.

  Instalamos **express** en node.JS con el comando

  ```
  $ npm install express --save
  ```

  Una vez instalado el express, al usarlo, se nos generará automaticamente una estructura como la siguiente.

  ![](http://i68.tinypic.com/16ay8zr.png)

  Más información en [express](http://expressjs.com/).


### Instalar GitHub Desktop

  Si trabajamos desde Windows o desde Mac, para tener un acceso a Git más amigable emplearemos **GitHub Desktop**, ya que se trata de una aplicación de escritorio con la manejaremos nuestros archivos de una forma más fácil y rápida que por consola.

  Una vez que dispongamos de una cuenta en GitHub [GitHub](https://github.com/), debemos dirigirnos a la página oficial de esta herramienta y descargarnos el asistente de instalación [GitHub Desktop](https://desktop.github.com/).

  ![](http://i64.tinypic.com/xrby8.png)

  Una vez realizada la instalación, lanzamos la aplicación y cumplimentamos la información de la cuenta de git que ya había sido creada, configurándola.

  ![](http://i64.tinypic.com/20ivvv6.png "Título de la imagen")

  En este punto ya tenemos acceso a nuestros repositorios

  ![](http://i66.tinypic.com/2mzl3wp.png)

### Instalacion Atom

  **Atom** es un  editor de texto libre que emplearemos para desarrollar nuestros proyectos.

  Para instalarlo nos dirigimos a la pagina oficial de [atom](https://atom.io/) y lo descargamos. Ejecutamos el asistente de instalación para poder comenzar a usar este editor.

  ![](http://i65.tinypic.com/2wextvc.jpg "Título de la imagen")

### Abrir cuenta en Cloud9

  **Cloud9** es un IDE que pone a tu disposición un entorno, ofreciéndote un servidor virtual para ti, con el que puedes almacenar tu código y probar las aplicaciones. Este entorno será usado en nuestros proyectos, y además es posible crear varios workspaces según deseemos.

  Para abrir una cuenta entra en la página oficial de [Cloud9](https://c9.io) y regístrate. Un workspace tiene el siguiente aspecto, donde por un lado tenemos nuestra estructura de directorios, un editor de archivos, además de la consola:

  ![](http://i64.tinypic.com/xehqhj.png)

  * *Un aspecto importante de Cloud9 que puede sernos útil es la posibilidad de desarrollar nuevos* ***espacios de trabajo a partir de proyectos desarrollados en GitHub.*** *Para ello tenemos que crear un nuevo workspace y añadir la url del repositorio git en el que estamos trabajando*

  ![](http://i66.tinypic.com/10gh502.png)

#### Markdown y traductores

Otra de las tareas iniciales de esta asignatura consiste en emplear el **formato Markdown**. Se trata de un lenguaje de marcado ligero que trata de conseguir la máxima legibilidad y facilidad de publicación tanto en sus forma de entrada como de salida.

##### Encabezados

Para los distintos tamaños de fuente se usa #:

  * '# Titulo'

  * '## Titulo'

  * '### Titulo'

  * '#### Titulo'

  * '##### Titulo'

  * '###### Titulo'

##### Citas

Para las citas se emplea:

 '> No temo a los ordenadores; lo que temo es quedarme sin ellos. -Isaac Asimov'

##### Énfasis

'**negrita**' '*cursiva*' ´`codigo`´ '~~tachado~~'

##### Listas

'* lista 1

'* lista 2

'1. lista 1

'2. lista 2

Este tutorial ha sido escrito en este formato, y luego traducido con la herramienta **Pandoc** para obtener el fichero html.

**Pandoc** es un traductor que te permite obtener ficheros en varios lenguajes, en nuestro caso lo usaremos para traducir de Markdown a HTML.

Para instalarlo acudimos a la página oficial de [pandoc](https://github.com/jgm/pandoc/releases/tag/1.16.0.2) y descargamos el paquete. Para usarlo, empleamos la siguiente sentencia en consola, indicando que el resultado no deseamos que lo muestre por consola, sino que lo guarde en el fichero indicado con la extensión html:

```
$ pandoc -f markdown -t html tutorial.md > tutorial.html
```
![](http://i65.tinypic.com/jrpn3d.png)

Enlaces de interés:

* [Markdown](https://en.wikipedia.org/wiki/Markdown)

* [Pandoc](http://pandoc.org/)

#### GitHub Pages

Una vez generado nuestro tutorial, podemos publicarlo gracias a gh Pages. **GH Pages** es una herramienta que permite mostrar tus proyectos git como una página web, de manera gratuita y con repositorios ilimitados.

Para empezar a usar Gh-Pages podemos hacerlo de forma automática desde el repositorio git con el que estamos trabajando. Así se generará de forma automática una *rama gh-pages* donde aparecerán los archivos que contienen la información web. Debajo del nombre de repositorio hacemos click en ***settings***.

![](http://i68.tinypic.com/103vptc.png)

Ahora hacemos click en el botón ***launch automatic page generator***

![](http://i65.tinypic.com/16iw4kg.png)

Incluimos nuestro tutorial y elegimos el **tema** que deseemos aplicar. Ahora en ***username.io/repositorio*** encontramos nuestro tutorial publicado.

![](http://i66.tinypic.com/10yl3k5.png)

Más información en [GitHub Pages](https://pages.github.com/).

> Si deseas contactar [contactar](https://plus.google.com/u/1/108254120853355124901) conmigo o escribirme cualquier sugerencia. -Cristina Tosco González
