# Guion — Lección 6: Consejos y próximos pasos (10 minutos)

**Responsable:** Fabian Sandoval

**Herramienta:** CodePen

**Duración estimada:** 10 minutos

## [0:00 – 0:30] Introducción

>"Hola, bienvenidos a la última lección del curso. En esta lección no vamos a aprender nada nuevo — vamos a repasar lo que ya sabes y te voy a dar algunos consejos para que sigas mejorando."

## [0:30 – 2:30] Repaso rápido

_(Mostrar diapositiva con resumen del curso)_

>"En este curso aprendiste seis cosas importantes:"
>* "Uno — qué es un sitio web y para qué sirven HTML y CSS."
>* "Dos — cómo escribir la estructura básica de una página HTML."
>* "Tres — cómo agregar títulos, párrafos, listas, imágenes y enlaces."
>* "Cuatro — cómo darle estilo a tu página con colores y fuentes."
>* "Cinco — cómo armar una página de perfil completa desde cero."
>* "Y seis — esto que estás viendo ahora: consejos para seguir adelante."

## [2:30 – 5:00] Errores comunes

_(Abrir CodePen en pantalla)_

>"Antes de irte, quiero mostrarte los errores más comunes que comete todo el mundo cuando empieza."

_(Escribir en la sección HTML de CodePen)_

>"Error número uno — olvidar cerrar una etiqueta."

```html
<h1>Hola, mundo
<p>Esto es un párrafo.</p>
```

>"¿Ves? Le falta el cierre al h1. Siempre que abres una etiqueta, tienes que cerrarla así:"

```html
<h1>Hola, mundo</h1>
<p>Esto es un párrafo.</p>
```
>"Error número dos — escribir mal el nombre de una etiqueta."

```html
<H1>Hola, mundo</H1>
```
>"Las etiquetas van siempre en minúscula. H1 en mayúscula puede funcionar a veces, pero no es correcto. Escríbelas siempre así: h1, p, ul, img."
>"Error número tres — olvidar los dos puntos o el punto y coma en CSS."

```css
h1 {
  color blue
}
```

>"Falta el dos puntos después de color y el punto y coma al final. Así es como debe quedar:"

```css
h1 {
  color: blue;
}
```

## [5:00 – 7:30] Consejos para seguir mejorando

_(Mostrar diapositiva)_

>"Ahora sí, los consejos."
>"Primero — practica todos los días aunque sea 10 minutos. No necesitas hacer algo grande, solo abre CodePen y prueba algo nuevo."
>"Segundo — cuando algo no te funcione, no te rindas. Revisa que no haya errores de tipeo — un espacio de más o una letra mal puede romper todo."
>"Tercero — explora MDN. Es una página gratuita donde puedes buscar cualquier etiqueta HTML o propiedad CSS y ver cómo funciona. La dirección es developer.mozilla.org — está en español."
>"Cuarto — mira el código de páginas que te gustan. En cualquier navegador puedes hacer clic derecho e inspeccionar para ver cómo están hechas."

## [7:30 – 9:30] Demostración final en CodePen

_(Abrir CodePen en pantalla)_

>"Para cerrar, te muestro un pequeño ejemplo de todo lo que aprendiste junto en una sola página."

_(Escribir en la sección HTML de CodePen)_

```html
<h1>Mi página web</h1>
<h2>Sobre mí</h2>
<p>Hola, soy estudiante y acabo de aprender HTML y CSS.</p>
<ul>
  <li>Me gusta la música</li>
  <li>Me gusta el deporte</li>
</ul>
```

_(Escribir en la sección CSS de CodePen)_

```css
h1 {
  color: green;
  text-align: center;
}

h2 {
  color: blue;
}

p {
  font-family: Arial;
  font-size: 18px;
}

ul {
  color: gray;
}
```

>"¿Ves? Con lo que aprendiste en este curso ya puedes hacer esto. Y esto es solo el comienzo."

## [9:30 – 10:00] Cierre

>"Gracias por completar el curso de fundamentos de desarrollo web. Si quieres seguir practicando, el enlace a CodePen está en la descripción de este video."
>"¡Mucho éxito y sigue programando!"








































