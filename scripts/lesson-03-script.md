# Guion - Lección 3: Añadir más elementos HTML

**Responsable:** Andrea Correa

**Herramienta:** CodeSandbox

**Duración estimada:** 8 a 9 minutos

---

## [0:00 – 0:30] Introducción

"Hola. En la lección anterior ya creamos una página básica con HTML usando títulos y párrafos.

En esta lección vamos a continuar esa misma página, pero ahora le agregaremos más elementos: una lista, una imagen y un enlace.

La idea es que nuestra página deje de ser solo texto y empiece a parecerse más a una página web real."

---

## [0:30 – 1:00] Preparar el archivo

"Estoy trabajando en CodeSandbox y voy a usar el archivo HTML de la lección 3.

También tengo una carpeta llamada image, donde guardé una imagen llamada perrito.png.

Esa imagen la voy a usar más adelante con la etiqueta img."

---

## [1:00 – 1:40] Base inicial

"Voy a empezar con una estructura simple parecida a la de la lección anterior."

```html
<!DOCTYPE html>
<html>

<head>
    <title>Mi página con más elementos HTML</title>
</head>

<body>

</body>

</html>
```

"DOCTYPE le dice al navegador que usamos HTML moderno.

html encierra todo el documento.

head guarda información interna de la página, como el title.

Y body es donde colocaremos todo lo que sí se verá en pantalla."

---

## [1:40 – 2:40] Agregar títulos y párrafos

"Primero agregamos el contenido básico dentro del body."

```html
<h1>¡Hola, mundo!</h1>

<h2>Sobre mí</h2>

<p>Me llamo Ana y tengo 15 años.</p>

<p>Estoy aprendiendo a crear páginas web con HTML.</p>
```

"h1 es el título principal de la página.

h2 funciona como subtítulo para separar secciones.

Y p sirve para escribir párrafos de texto.

Hasta aquí seguimos trabajando con lo que ya se vio antes, pero ahora vamos a añadir elementos nuevos."

---

## [2:40 – 4:10] Crear una lista con ul y li

"Ahora voy a crear una sección para mis cosas favoritas."

```html
<h2>Mis cosas favoritas</h2>

<p>Estas son algunas cosas que me gustan:</p>
```

"Este h2 crea una nueva sección y el párrafo introduce lo que voy a mostrar.

Pero en vez de poner todos los gustos en un solo párrafo, voy a usar una lista."

```html
<ul>
    <li>Escuchar música</li>
    <li>Jugar videojuegos</li>
    <li>Aprender programación</li>
</ul>
```

"La etiqueta ul significa lista no ordenada.

Se llama así porque los elementos aparecen con puntos, no con números.

Dentro de ul usamos li.

Cada li representa un elemento de la lista.

Por ejemplo, escuchar música es un elemento, jugar videojuegos es otro y aprender programación es otro.

Esto hace que la información se vea más ordenada y fácil de leer."

---

## [4:10 – 6:00] Agregar una imagen con img

"Ahora vamos a agregar una imagen a la página."

```html
<h2>Mi mascota</h2>

<p>También puedo agregar imágenes usando HTML.</p>
```

"Primero creo un subtítulo con h2 y luego un párrafo corto para explicar la sección.

Ahora escribo la etiqueta img."

```html
<img src="image/perrito.png" alt="Mi perrito" width="300">
```

"La etiqueta img sirve para mostrar imágenes.

A diferencia de otras etiquetas, img no necesita cierre.

El atributo src indica la ruta de la imagen.

En este caso, la imagen está dentro de la carpeta image y se llama perrito.png.

El atributo alt es una descripción alternativa. Sirve si la imagen no carga y también ayuda a la accesibilidad.

El atributo width cambia el ancho de la imagen. Aquí uso 300 para que no se vea demasiado grande.

Si la imagen no aparece, normalmente el error está en la ruta, en el nombre de la carpeta o en el nombre del archivo."

---

## [6:00 – 7:30] Agregar un enlace con a

"Ahora voy a agregar un enlace.

Los enlaces son importantes porque permiten conectar una página con otra."

```html
<h2>Mi página favorita</h2>

<p>Los enlaces permiten visitar otros sitios web.</p>
```

"De nuevo creo una sección con h2 y agrego un párrafo explicativo.

Ahora escribo el enlace."

```html
<a href="https://www.youtube.com" target="_blank">
    Visitar YouTube
</a>
```

"La etiqueta a sirve para crear enlaces.

El atributo href indica la página a la que queremos ir.

El texto que está entre a y su cierre es lo que verá el usuario.

En este caso el usuario verá Visitar YouTube.

El atributo target con el valor blank hace que el enlace se abra en una nueva pestaña."

---

## [7:30 – 8:20] Repaso rápido

"En esta lección agregamos tres elementos nuevos.

Usamos ul para crear una lista.

Usamos li para colocar elementos dentro de esa lista.

Usamos img para mostrar una imagen.

Y usamos a para crear un enlace.

También vimos atributos importantes como src, alt, width, href y target."

---

## [8:20 – 9:00] Cierre

"Con esto nuestra página ya no tiene solamente títulos y párrafos.

Ahora también tiene una lista para organizar información, una imagen para hacerla más visual y un enlace para navegar a otra página.

En la siguiente lección se podrá usar este mismo HTML para darle estilo con CSS, agregando colores, tamaños, bordes y una mejor presentación.

¡Nos vemos en la siguiente lección!"
