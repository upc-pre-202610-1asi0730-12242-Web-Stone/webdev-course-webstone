Lección 3: Añadir más elementos HTML

Responsable: Andrea Correa
Herramienta: CodePen sin registro
Duración estimada: 8 minutos

[0:00 – 0:30] Introducción

Hola, en esta lección vamos a continuar con la página que se creó en la lección anterior. Ya tenemos títulos y párrafos, pero ahora vamos a hacer que la página tenga más contenido usando listas, imágenes y enlaces.

Al final de esta lección, tu página tendrá una lista de cosas favoritas, una imagen y un enlace que abre otra página web.

[0:30 – 1:30] Recordatorio de la página anterior

En la lección anterior aprendimos que HTML sirve para organizar el contenido de una página web. Usamos etiquetas como h1 para el título principal, h2 para subtítulos y p para párrafos.

Ahora vamos a agregar nuevos elementos debajo de lo que ya teníamos.

[1:30 – 3:00] Agregar una lista

Primero vamos a crear una lista de cosas favoritas. Para eso usamos la etiqueta ul, que significa lista no ordenada.

Dentro de ul colocamos varios li. Cada li representa un elemento de la lista.

<ul>
  <li>Escuchar música</li>
  <li>Jugar videojuegos</li>
  <li>Aprender programación</li>
</ul>

La etiqueta ul crea la lista completa y cada li agrega un punto dentro de esa lista.

[3:00 – 5:00] Agregar una imagen

Ahora vamos a agregar una imagen. Para eso usamos la etiqueta img.

<img src="https://placekitten.com/400/250" alt="Un gatito bonito" width="400">

La etiqueta img no necesita cierre.
El atributo src indica la dirección de la imagen.
El atributo alt muestra una descripción si la imagen no carga.
El atributo width sirve para cambiar el tamaño de la imagen.

[5:00 – 6:30] Agregar un enlace

Ahora agregaremos un enlace usando la etiqueta a.

<a href="https://developer.mozilla.org/es/docs/Web/HTML" target="_blank">
  Aprender más sobre HTML
</a>

El atributo href indica a qué página nos llevará el enlace.
El atributo target blank permite abrir el enlace en una nueva pestaña.

[6:30 – 7:30] Repaso de etiquetas

Hoy aprendimos tres etiquetas nuevas:

ul sirve para crear listas.
li sirve para agregar elementos dentro de una lista.
img sirve para mostrar imágenes.
a sirve para crear enlaces.

También vimos atributos como src, alt, width, href y target.

[7:30 – 8:00] Cierre

¡Listo! Ahora tu página ya no tiene solo texto. También tiene una lista, una imagen y un enlace.

En la siguiente lección se podrá usar esta misma página para darle estilo con CSS, agregando colores, tamaños, bordes y mejor presentación.