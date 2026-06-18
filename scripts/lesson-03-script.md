# Guión - Lección 3: Añadir más elementos HTML

**Responsable:** Andrea Correa

**Herramienta:** codesandbox

**Duración Estimada:** 8 minutos

## [0:00 – 0:30] Introducción

"Hola. En la lección anterior creamos nuestra primera página web utilizando HTML. Ya tenemos títulos y párrafos, pero una página real suele tener mucho más contenido.

Hoy vamos a mejorar esa página agregando listas, imágenes y enlaces. Al final tendrás una página mucho más completa y aprenderás algunas de las etiquetas más utilizadas en HTML."

---

## [0:30 – 1:30] Recordando la lección anterior

"Si vienes de la lección anterior, ya deberías tener algo parecido a esto:"

```html
<h1>¡Hola, mundo!</h1>

<h2>Sobre mí</h2>

<p>Me llamo Ana y tengo 15 años.</p>

<p>Estoy aprendiendo a crear páginas web con HTML.</p>

<h2>Mis cosas favoritas</h2>

<p>Me gusta la música, los videojuegos y la programación.</p>
```

"Ya sabemos crear títulos y párrafos. Ahora vamos a añadir nuevos elementos para mostrar información de una forma más organizada."

---

## [1:30 – 3:30] Crear una lista

"Primero vamos a agregar una lista de cosas favoritas."

```html
<h2>Mis cosas favoritas</h2>

<ul>
    <li>Los gatos</li>
    <li>Los videojuegos</li>
    <li>La programación</li>
</ul>
```

"La etiqueta ul significa Unordered List, o lista no ordenada.

Dentro de ella usamos varias etiquetas li, que significan List Item o elemento de lista.

Observa cómo cada elemento aparece acompañado por un punto automáticamente."

---

## [3:30 – 5:30] Agregar una imagen

"Ahora vamos a insertar una imagen en nuestra página."

```html
<h2>Mi mascota</h2>

<img src="image/perrito.png" alt="Mi perrito" width="300">
```

"La etiqueta img sirve para mostrar imágenes.

El atributo src indica dónde se encuentra la imagen.

En este caso la imagen está dentro de la carpeta image.

El atributo alt contiene una descripción alternativa y es útil cuando la imagen no puede mostrarse.

Y width nos permite controlar el tamaño de la imagen."

---

## [5:30 – 7:00] Crear un enlace

"Ahora agregaremos un enlace para que el usuario pueda visitar otra página."

```html
<h2>Mi página favorita</h2>

<a href="https://www.youtube.com" target="_blank">
    Visitar YouTube
</a>
```

"La etiqueta a proviene de la palabra anchor.

El atributo href indica la dirección a la que queremos enviar al usuario.

Y target igual a blank hace que el enlace se abra en una nueva pestaña."

---

## [7:00 – 7:40] Repaso rápido

"Hoy aprendimos tres etiquetas nuevas:"

* ul → crea listas.
* li → agrega elementos dentro de una lista.
* img → muestra imágenes.
* a → crea enlaces.

"También conocimos algunos atributos importantes como src, alt, width y href."

---

## [7:40 – 8:00] Cierre

"¡Excelente trabajo!

Ahora tu página ya no tiene solamente texto. También contiene listas para organizar información, imágenes para hacerla más visual y enlaces para conectar con otros sitios web.

En la siguiente lección aprenderás a darle estilo a todo este contenido utilizando CSS, agregando colores, tamaños y una mejor presentación visual.

¡Nos vemos en la siguiente lección!"
