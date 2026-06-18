# Guión - Lección 2: Introducción a HTML

**Responsable:** Oscar Checa

**Herramienta:** CodePen(sin registro)

**Duración Estimada:** 10 minutos

## [0:00 – 0:30] Introducción
> "Hola, hoy vas a dar el siguiente paso: vas a escribir tu *primera página web real* con HTML.
Al final de esta lección vas a tener una página con tu nombre, una descripción y tus cosas favoritas. Y lo mejor: la verás funcionar en tu navegador
sin instalar absolutamente nada. Vamos."

## [0:30 – 1:50] ¿Qué es HTML? 

> "HTML son las siglas de HyperText Markup Language. Suena complicado, pero la idea es simple. 
Piensa en una página web como una carta. El *contenido* de la carta — el texto, los títulos, los párrafos — eso es HTML.
HTML le dice al navegador qué hay en la página y cómo está organizado.No es un lenguaje de programación como Java.
HTML es un lenguaje de *etiquetas*. Y ahora vas a ver qué significa eso."

## [1:50 - 2:30] Abrir CodePen

> "Abre tu navegador y ve a codepen.io/pen.
Vas a ver tres columnas: HTML, CSS y JS. Hoy solo usamos la columna de *HTML*, las otras dos las ignoramos por ahora. En la parte de abajo verás el resultado en tiempo real.
Cada vez que escribas algo, aparecerá ahí de inmediato."

## [2:30 - 5:00] La estructura base

> "Toda página HTML empieza con la misma estructura base.
Escribe esto conmigo:"

```html
<!DOCTYPE html>
<html>

  <head>
    <title>Mi primera página web</title>
  </head>
  <body>
  </body>
</html>
```

> "Vamos por partes. La primera línea — DOCTYPE html — le dice al navegador:'esto es HTML moderno, léelo correctamente.'

> Luego viene la etiqueta html. Fíjate que tiene una etiqueta de apertura — html con los signos de menor y mayor —
y una etiqueta de cierre — con una barra antes de html.
*Todo en HTML funciona así: se abre y se cierra.* 

> Dentro de html hay dos secciones:
> head y body."

> "El head es la cabeza de la página. Guarda información que el navegador necesita
pero que el usuario *no ve directamente*. Por ejemplo, el title — que es el texto
que aparece en la pestaña del navegador."

> "El body es el cuerpo. *Todo lo que el usuario sí ve en pantalla va aquí.*"

## [5:00-7:30] Agregar contenido

> "Ahora vamos a poner contenido dentro del body.
Empieza con un título principal:"


```html
    <h1>¡Hola, mundo!</h1>
```

> "h1 significa 'heading 1', o sea, el título más importante de la página. Mira cómo apareció en la vista previa de abajo — grande y en negrita. 

> Ahora agrega un título secundario y un párrafo:"


```html
    <h2>Sobre mí</h2>
    <p>Me llamo Ana y tengo 15 años.</p>
    <p>Estoy aprendiendo a crear páginas web con HTML.</p>
```

> "h2 es un título más pequeño que h1 — hay hasta h6, de mayor a menor.
Y p es un párrafo. Cada etiqueta p es un bloque de texto separado. 

> Agrega una sección más:"


```html
    <h2>Mis cosas favoritas</h2>
    <p>Me gusta la música, los videojuegos y la programación.</p>
```

> "Ahora *cambia el contenido*: pon tu propio nombre, tu edad, tus cosas favoritas.
Esta es tu página, personalízala."

## [7:30-9:00] Repaso de etiquetas

> "Muy bien. Antes de terminar, repasemos las etiquetas que usamos hoy:"


> "- *DOCTYPE html* — declara que es HTML moderno.
> - *html* — envuelve toda la página.
> - *head* — información de la página, no visible en pantalla.
> - *title* — texto de la pestaña del navegador.
> - *body* — todo lo que sí se ve.
> - *h1* — título principal.
> - *h2* — título secundario.
> - *p* — párrafo de texto.

> Nota que *todas se abren y se cierran*. Si olvidas cerrar una etiqueta,
la página puede verse rara. Es el error más común de los principiantes. 

> Una pista: CodePen te avisa cuando hay algo mal con un pequeño ícono de error."

## [9:00 - 10:00] Cierre

> "¡Lo lograste! Acabas de crear tu primera página web con HTML.

> En esta lección aprendiste:
> - Que HTML usa *etiquetas* que se abren y se cierran.
> - Que la estructura base de toda página es DOCTYPE, html, head y body.
> - Que h1 y h2 son títulos, y p es un párrafo.

> ¡Hasta la siguiente lección!"
