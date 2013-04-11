# Tutorial de la plantilla base *Jekyllxhibit*: creación de páginas Web por colaborativa.eu

## 1. Registro de dominio (opcional)

El primer paso sería registrar un dominio .ES o .COM. En caso de no haber registrado un dominio nuestra página web estará alojada en un subdominio de GitHub

> `nombreusuario.github.com

## 2. Dar de alta en GitHub

Vamos a utilizar las siguientes tres herramientas para crear nuestra página web:

* Jekyll: es un simple generador de páginas web en html estático.
* Prose.io: es un editor de contenidos en formato Jekyll.
* GitHub Pages: aloja gratuitamente páginas generadas con Jekyll.

Nos damos de alta en Github.com, ¡es muy fácil y gratis!

<a href="http://www.flickr.com/photos/50381188@N06/8637580247/" title="Paso-02-GitHub por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8244/8637580247_991f7df110.jpg" width="500" height="286" alt="Paso-02-GitHub"></a>

## 3. Copiar plantilla base *jekyllxhibit* en nuestro usuario de GitHub

A continuación accedemos con nuestro usuario en GitHub y localizamos nuestra plantilla base *jekyllxhibit* en:

> `https://github.com/colaborativa/jekyllxhibit`

 <a href="http://www.flickr.com/photos/50381188@N06/8638707576/" title="Paso-03-01-GitHub-Clonar por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8399/8638707576_0138553b93.jpg" width="500" height="286" alt="Paso-03-01-GitHub-Clonar"></a>

Hacemos click en **FORK this repo** localizado en la parte superior derecha y tendremos en nuestro usuario de GitHub una copia de la plantilla llamada *jekyllxhibit*.

## 4. Renombrar plantilla GitHub

Un paso más antes de comenzar a añadir contenidos. Tenemos que renombrar la actual plantilla teniendo en cuenta que:

* Si vamos a utilizar un dominio propio no importa el nombre que elijamos para la plantilla.
* Si no disponemos de dominio entonces la plantilla hay que llamarla igual siguiendo la nomenclatura: 

> `NOMBREUSUARIO.github.com` 

 De esta manera podremos acceder a nuestra página Web a través de la url: 

> `http://nombreusuario.github.com`

Para renombrarla hacemos click en la pestaña **Settings** del repositorio, introducimos el nuevo nombre y hacemos click en **Rename**. Llegado este punto hay que asegurarse que la sección **GitHub Pages** de **Settings** está activada y puede leerse: 

> `Your site is published at http://www.nombreusuario.github.com

<a href="http://www.flickr.com/photos/50381188@N06/8638715922/" title="Paso-03-01-GitHub-Renombrar por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8118/8638715922_8ba3f8b6d4.jpg" width="500" height="286" alt="Paso-03-01-GitHub-Renombrar"></a>

## 5. Configurar plantilla GitHub 

El archivo `CNAME` forma parte de nuestra plantilla *jekyllxhibit* y tiene que ser editado teniendo en cuenta:

* Si vamos a utilizar un dominio propio el archivo `CNAME` debe contener el nombre de nuestro dominio, por ejemplo: `colaborativa.eu`´.
* Si no disponemos de dominio y nuestra página se accede a través de `NOMBREUSUARIO.github.com` entonces este archivo debe contener una línea en blanco.

Para editar el archivo `CNAME` ir a nuestra plantilla en GitHub, veremos entonces la lista de archivos que la forman. Hacer click sobre el archivo `CNAME` y aparecerá la siguiente pantalla:

<a href="http://www.flickr.com/photos/50381188@N06/8637668359/" title="Paso-05-01-GitHub-Editar-CNAME por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8528/8637668359_e91c19c5f9.jpg" width="500" height="286" alt="Paso-05-01-GitHub-Editar-CNAME"></a> 

Hacer click en **Edit**, editarlo y hacer click en **Commit Changes** situado abajo a la derecha. 

<a href="http://www.flickr.com/photos/50381188@N06/8637673623/" title="Paso-05-02-GitHub-Editar-CNAME por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8114/8637673623_7e97737735.jpg" width="500" height="325" alt="Paso-05-02-GitHub-Editar-CNAME"></a>

En el explorador ir a nombreusuario.github.com y ver la plantilla funcionando. ¡Ya podemos comenzar a añadir contenidos!

## 6. Descripción estructura plantilla GitHub

Brevemente describimos los archivos que componen la plantilla en GitHub:

* _config.yml: almacena información de configuración de la plantilla. 
* _layouts: plantillas en html que se utilizarán para visualizar los posts, en nuestro caso sólo disponemos de una llamada `default.html`. 

* _posts: el contenido de nuestra página Web se localiza en este directorio, deben nombrarse siguiendo la nomenclatura **AÑO-MES-DIA-título.md**. El orden en el que aparecen los contenidos viene determinado por esta fecha. Cuenta con dos subdirectorios: 

    * sections: incluye las secciones que aparecen en la barra de la izquierda. Cada sección tiene asociado un número de exhibits.

    * exhibits: incluye nuestros protectos, artículos, noticias, etc. Cada exhibit está asociado a una sección concreta.

* stylesheets: hojas de estilo en formato CSS.

## 7: Añadir Contenidos con Prose.io

Para comenzar a añadir contenidos iremos a:

> `http://prose.io`

y accederemos con nuestras credenciales de GitHub, para ello hacer click en el botón **Authorize with GitHub**.

<a href="http://www.flickr.com/photos/50381188@N06/8638725787/" title="Paso-07-01-Proseio-Acceder por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8522/8638725787_9a2ec88a12.jpg" width="500" height="271" alt="Paso-07-01-Proseio-Acceder"></a>

Prose.io tendrá acceso a nuestra plantilla alojada en GitHub y nos permitirá añadir contenidos. Prose.io nos mostrará una lista de proyectos alojados en GitHub, hacemos click en la plantilla que deseamos modificar y aparecerá la siguiente pantalla:

<a href="http://www.flickr.com/photos/50381188@N06/8638736133/" title="Paso-07-02-Proseio-Listado por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8525/8638736133_9c982f554d.jpg" width="500" height="271" alt="Paso-07-02-Proseio-Listado"></a>

Podremos añadir o modificar contenidos en el directorio `exhibits`, que contiene nuestros proyectos, artículos, noticias, etc., y en el directorio `sections`, que contiene las secciones en las que se clasifican los exhibits y se muestran en la columna de la izquierda.

### 7.1 Editar secciones con Prose.io

Para editar una sección existente hacer click en el directorio `sections` y aparecerá el listado de secciones existentes:

<a href="http://www.flickr.com/photos/50381188@N06/8638754333/" title="Paso-07-03-Proseio-sections por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8119/8638754333_d91cef9fbd.jpg" width="500" height="271" alt="Paso-07-03-Proseio-sections"></a>

Hacemos click en la que deseamos modificar y aparecerá la siguiente barra de edición:

<a href="http://www.flickr.com/photos/50381188@N06/8638754525/" title="Paso-07-04-Proseio-sections-editar por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8532/8638754525_30afa7ff88.jpg" width="500" height="271" alt="Paso-07-04-Proseio-sections-editar"></a>

A continuación vamos a explicar las opciones de la barra de edición:

#### Formato Markdown

Nuestros contenidos se escriben en formato de texto Markdown. Se trata de un lenguaje de marcado fácil y en el que se pueden insertar bloques de texto html. Al hacer click en el botón **M** de la barra de edición nos aparecerá un pequeño y sencillo tutorial de la sintaxis Markdown:

<a href="http://www.flickr.com/photos/50381188@N06/8638769529/" title="Paso-07-05-Proseio-barra-edicion-markdown por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8106/8638769529_8a0f461062.jpg" width="500" height="396" alt="Paso-07-05-Proseio-barra-edicion-markdown"></a>

#### Cabecera con metadata

Todos los archivos contienen una pequeña cabecera con variables de configuración sencillas llamada **metadata** y a continuación el contenido propiamente dicho de la sección o exhibit a editar. A través del botón **Metadata** podemos mostrar o ocultar esta cabecera, lo cual nos permitirá centrarnos en la edición del contenido.

<a href="http://www.flickr.com/photos/50381188@N06/8639873168/" title="Paso-07-06-Proseio-barra-edicion-metadata por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8539/8639873168_62718f54f7.jpg" width="500" height="396" alt="Paso-07-06-Proseio-barra-edicion-metadata"></a>

En el caso de las secciones sólo existirá la cabecera metadata, la parte de contenidos estará vacía, y el único dato que tendremos que editar es el que corresponde a la etiqueta **title** que se refiere al título de la sección que aparecerá en la columna izquierda de la página Web. El resto de etiquetas permanecerán intactas.

#### Sección publicada

Otra opción de la barra de edición nos permite indicar si la sección se publicará en nuestra Web o no. Está representada por el icono standárd de **Herramientas**. Esta opción resulta de utilidad cuando estamos creando nuevas secciones que aún no hemos llenado de contenido por lo que nos interesa mantenerlas ocultas.

<a href="http://www.flickr.com/photos/50381188@N06/8639873292/" title="Paso-07-07-Proseio-barra-edicion-publicado por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8521/8639873292_08de43dce8.jpg" width="500" height="396" alt="Paso-07-07-Proseio-barra-edicion-publicado"></a>

#### Vista Preliminar

Al hacer click en el botón **Vista prelimitar**, representado con un icono de un ojo, veremos como se visualizará nuestra sección o exhibit en la página Web. En el caso de secciones al no existir contenido, sólo existe la cabecera de metadata, la vista preliminar mostrará una pantalla en blanco.

<a href="http://www.flickr.com/photos/50381188@N06/8638769937/" title="Paso-07-08-Proseio-barra-edicion-vistapreliminar por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8255/8638769937_22b9321aea.jpg" width="500" height="396" alt="Paso-07-08-Proseio-barra-edicion-vistapreliminar"></a>

#### Guardar y salir

Una vez editado el título de la sección debemos guardar los cambios. Para ello hacer click en el botón **Save** de la barra de edición y aparecerá la siguiente pantalla:

<a href="http://www.flickr.com/photos/50381188@N06/8639903062/" title="Paso-07-09-Proseio-barra-edicion-guardarysalir por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8384/8639903062_6c85fab690.jpg" width="500" height="396" alt="Paso-07-09-Proseio-barra-edicion-guardarysalir"></a>

A continuación hacer click en el botón **Commit** para confirmar los cambios. Cada vez que realizamos una modificación se registrarán junto con un mensaje que podemos personalizar si lo deseamos.

Si en el momento de guardar no estamos satisfechos con los cambios realizados podemos volver a la pantalla de edición haciendo click en el icono de **Prohibido**, situado junto al botón **Commit**.

### 7.2 Añadir fotos con Prose.io y Flickr.com

Para añadir fotos a uno de nuestros artículos situados en el directorio `exhibits` primero tendremos que seleccionar el archivo a través de *Prose.io* y entrar en la pantalla de edición.

<a href="http://www.flickr.com/photos/50381188@N06/8639973616/" title="Paso-07-10-Proseio-flickr por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8542/8639973616_c271f67bb5.jpg" width="500" height="396" alt="Paso-07-10-Proseio-flickr"></a>

Una manera fácil de almacenar las imágenes de nuestra página Web es a través del servicio gratuito que ofrece *Flickr.com*. Para ello tendremos que darnos de alta en *Flickr.com* y añadir las fotos. Para insertar una foto en uno de nuestros exhibits sólo hay que hacer click en el botón **Compartir** de *Flickr.com*, copiar el código html asociado a la imagen y pegarlo en el archivo de nuestro exhibit en *Prose.io*.

<a href="http://www.flickr.com/photos/50381188@N06/8639974016/" title="Paso-07-11-Proseio-flickr por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8117/8639974016_c2a77b12fa.jpg" width="500" height="289" alt="Paso-07-11-Proseio-flickr"></a>

En la siguiente captura de pantalla podemos ver la imagen insertada en nuestro exhibit.

<a href="http://www.flickr.com/photos/50381188@N06/8638875757/" title="Paso-07-13-Proseio-flickr por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8100/8638875757_867e85aa81.jpg" width="500" height="396" alt="Paso-07-13-Proseio-flickr"></a>

En la siguiente captura de pantalla podemos ver una vista preliminar de como se visualizaría en nuestra Web.

<a href="http://www.flickr.com/photos/50381188@N06/8638875923/" title="Paso-07-14-Proseio-flickr por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8111/8638875923_b088d5a880.jpg" width="500" height="396" alt="Paso-07-14-Proseio-flickr"></a>

Una vez concluida la edición, hacemos click en botón **Save**. A continuación hacer click en el botón **Commit** para confirmar los cambios. Cada vez que realizamos una modificación se registrarán junto con un mensaje que podemos personalizar si lo deseamos.

Si en el momento de guardar no estamos satisfechos con los cambios realizados podemos volver a la pantalla de edición haciendo click en el icono de **Prohibido**, situado junto al botón **Commit**.

<a href="http://www.flickr.com/photos/50381188@N06/8638878691/" title="Paso-07-15-Proseio-flickr por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8259/8638878691_d4e66bf223.jpg" width="500" height="396" alt="Paso-07-15-Proseio-flickr"></a>


### 7.3 Añadir vídeos con Prose.io y Vimeo.com

Para añadir fotos a nuestros `exhibits` hay que seguir un proceso similar, recomendamos utilizar el servicio gratuito *vimeo.com*. El primer paso sería darse de alta en *vimeo.com* y subir el vídeo que queremos insertar en nuestra página Web. La siguiente captura muestra el formulario de alta de *vimeo.com*.

<a href="http://www.flickr.com/photos/50381188@N06/8640024066/" title="Paso-07-16-Proseio-vimeo por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8099/8640024066_a1b65e15a3.jpg" width="500" height="396" alt="Paso-07-16-Proseio-vimeo"></a>

A continuación, accedemos a *vimeo.com* y añadimos nuestro primer vídeo. Para insertarlo en uno de nuestro `exhibits` habrá que hacer click en el botón **Share** situado en la esquina superior derecha del vídeo y copiar el texto situado bajo el título **Embed**.

<a href="http://www.flickr.com/photos/50381188@N06/8639974276/" title="Paso-07-12-Proseio-vimeo por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8522/8639974276_c5b2b83e89.jpg" width="500" height="289" alt="Paso-07-12-Proseio-vimeo"></a>

En *Prose.io* accedemos al `exhibit` en el que deseamos insertar el vídeo y pegamos el texto de *vimeo.com*.

<a href="http://www.flickr.com/photos/50381188@N06/8640024222/" title="Paso-07-17-Proseio-vimeo por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8108/8640024222_2c4ee838f7.jpg" width="500" height="396" alt="Paso-07-17-Proseio-vimeo"></a>

En el texto para la inserción del vídeo hay que hacer una comprobación antes de almacenar los cambios del `exhibit`. *Prose.io* no entiende correctamente aquellas variables en las que no se especifica ningún valor, esperamos que resuelvan este problem pronto. En el ejemplo de abajo se trataría de las variables: webkitAllowFullScreen, mozallowfullscreen y allowFullScreen.

> `<iframe
> src="http://player.vimeo.com/video/58116607"
> width="500" height="281"
> frameborder="0" webkitAllowFullScreen
> mozallowfullscreen
> allowFullScreen>
</iframe> <p><a
> href="http://vimeo.com/58116607">Montaje
> RepRapPro Huxley en Colaboratorio</a>
> from <a
> href="http://vimeo.com/colaborativa">colaborativa</a>
> on <a
> href="http://vimeo.com">Vimeo</a>.</p>`

 Para que el vídeo se inserte correctamente hay que editar el texto y eliminarlas. El texto anterior editado quedaría:

> `<iframe
> src="http://player.vimeo.com/video/58116607"
> width="500" height="281"
> frameborder="0"> </iframe> <p><a
> href="http://vimeo.com/58116607">Montaje
> RepRapPro Huxley en Colaboratorio</a>
> from <a
> href="http://vimeo.com/colaborativa">colaborativa</a>
> on <a
> href="http://vimeo.com">Vimeo</a>.</p>`

Haciendo click en el botón de **Vista preliminar** podemos comprobar que el vídeo se ha insertado correctamente en nuestro `exhibit`.

<a href="http://www.flickr.com/photos/50381188@N06/8638920807/" title="Paso-07-18-Proseio-vimeo por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8104/8638920807_5a5ef1c6eb.jpg" width="500" height="396" alt="Paso-07-18-Proseio-vimeo"></a>

## Créditos

La plantilla base *jekyllxhibit* 

## Contacto

Puedes contactar con nosotros en info@colaborativa.eu para más información.

[1]: http://colaborativa.eu
[2]: http://jrmoran.com/playground/markdown-live-editor/

