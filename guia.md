## Página web de la Asociación

[https://www.qgis.es/](https://www.qgis.es/)

![](img/01_web.jpg)

Tenemos un apartado de blog, por ejemplo [https://www.qgis.es/post/2021-12-15-qgis-no-esta-afectado-por-log4j/](https://www.qgis.es/post/2021-12-15-qgis-no-esta-afectado-por-log4j/)

![](img/02_ejemplo_entrada.jpg)

El código de la página web está se encuentra en GitHub, que de forma sencilla es una página que aloja proyectos de código principalmente y que usa control de versiones.

[https://github.com/qgises/qgis-es](https://github.com/qgises/qgis-es)

El mismo proyecto QGIS también se encuentra GitHub.

GitHub no es la única opción. La Asociación también cuenta con cuenta en GitLab [https://gitlab.com/qgis_es]

## ¿Cuáles son los archivos que necesitamos editar para añadir una entrada en el blog?

- Autores Carpeta [/content/authors](https://github.com/qgises/qgis-es/tree/master/content/authors)
- Entradas. Carpeta [/content/post](https://github.com/qgises/qgis-es/tree/master/content/post)

Tanto para autores como para los post debemos crear una carpeta que debe contener un archivo *index.md*
y todas las imágenes que queramos añadir.

La carpeta de los post debe tener como prefijo la fecha en formato (2022-01-21) más el nombre que queremos que aparezca en la URL

![post](img/03_post.jpg)

En la carpeta del autor basta con nuestro nombre.

![post](img/04_authors.jpg)

**No debemos usar espacios para separa palabras. Usamos guiones**

## Markdown

Markdown es un lenguaje de marcado que facilita la aplicación de formato (negrita, enlaces, encabezados,listas...) a un texto empleando una serie de caracteres de una forma especial. 

Como explica "John Gruber":http://daringfireball.net/projects/markdown/, uno de sus creadores, Markdown es realmente dos cosas: por un lado, el lenguaje; por otro, una herramienta de software que convierte el lenguaje en HTML válido.

[Qué es Markdown, para qué sirve y cómo usarlo](https://www.genbeta.com/guia-de-inicio/que-es-markdown-para-que-sirve-y-como-usarlo)

En el siguiente enlace tenemos una guía de las marcas que se usan en Markdown

[Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)

Vemos un ejemplo en el blog:
- [Entrada en la web](https://www.qgis.es/post/2021-03-29-qgis-docker/)
- [Post en MarkDown](https://github.com/qgises/qgis-es/tree/master/content/post/2021-03-29-qgis-docker)


## Creando nuestra propia entrada

Vamos a usar el este repositorio para reproducir el flujo que debemos hacer

- Crear una copia fork
- Clonar el repositorio en nuestro equipo
- Crear una rama
- Añadir nuestro archivos e ir registrando los cambios (commit)
- Subir los cambios a nuestro repositorio remoto
- Pedir que los cambios sean añadidos al repositorio de QGIS ES (Pull Request)