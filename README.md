# REVIEW DEL CURSO DE FRONT-END WEB DEVELOPER

## Día 1- 22 ABR

Páginas Web: Contenido de distinto tipo; imágenes, texto, vídeo, sonido, ... mostrado a través de un **navegador**.
Las páginas web para ser visualizadas de forma pública tienen que estar alojadas en un **servidor web**

Las webs son **texto** están desarrolladas en un lenguaje de marcas: **HTML**

```html
  <!DOCTYPE html>
  <html>
    <head>INFORMACION QUE NO SE VISUALIZA EN LA PAGINA</head>
    <body></body>
  </html>
```

Imagen: `<img>`
Titulo: `<h1>`
Lista desordenada: `<ul><li>`
Lista ordenada: `<ol><li>`
Hipervínculo: `<a></a>`
Texto: `<p>`

[página del curso](https://bcncodes-academy.web.app)

[MDN: La biblia del desarrollo web](mdn.com)

## Día 2 - 23 Abril

Elementos de bloque vs en linea

Elementos de bloque: div, p, h1, h2, main, header, footer,...
Elementos de línea: img, a, span, strong, i, em,...

Elementos semánticos:
header: contenido es la cabecera de la página
footer: contenido que va al pie de página
nav: barra navegación

strong, ul, table, ...

Comenzamos el ejercicio del [blog Anden27](http://anden-27.blogspot.com/2018/03/museo-de-los-vikingos-en-oslo.html)

## Día 3 - 26 Abril

Inicio CSS:
formato de una regla CSS
concepto de herencia de estilos
selectores de id y de clase

Ejercicio con selectores de clase
Recepta de la iaia. EJercicio entregable

## Día 4 - 27 Abril

Selectores avanzados: Según la posición en el árbol podemos seleccionarlos
Ej.: 

```css
selección de descendientes:
header a{ }
body nav{ }
selección hijos directos:
body > nav { }
header > nav { }
selección por agrupación:
p, h2{ }
selección por un atributo: img[src="gatito.jpg"]{ }
selección por pseudoelementos: div::before{ }
selección por pseudoclases: a:hover{ }
```
BOX-MODEL || MODELO DE CAJA

elemento de bloque: estructura de caja: contenido | padding | border | margin
medidas de una caja: ancho de una caja por defecto se refiere al contenido. Se puede cambiar con la propiedad:
    `box-sizing` y valor `border-box`
    
## Día 5 - 28 Abril

Posicionamiento - Positioning: 
1. propiedad positioning;
2. display: flex;
3. display: grid;

1. Positioning
  - `position: static`, posición por defecto, el elemento no se puede mover de su lugar,
  - `position: relative`, elemento se mueve si se alteran los valores de las props: top, left, right or bottom. El elemnto se desplaza el hueco no se rellena.
  - `position: absolute`, el se mueve igual que el relative, pero su espacio se ocupa por el siguiente elemento. Las coordenadas se fijan respecto al elemento superior posicionado como relative, y si no hay ninguno respecto al body.
  - `position: fixed`: 0 que absolute pero el el no se mueve con scroll.
  - `position: sticky`:  0 que fixed pero hace scroll hasta que el scroll llega a las coordenadas del elemento.

---

JS
codeCombat
como se asignan valores a variables y se imprimen por pantalla.

## Día 6 - 29 Abril

JS

Cómo se declaran variables: 
```js
let nom_variable = valor;
const nom_constante = valor;
```

Tipos de variable:
```js
let nombre = "Pepe"; // nombre es una variable de tipo string
let num = 3; // num es una variable de tipo number
let bandera = true; // bandera es de tipo boolean
```

Una variable sin valor devuelve `undefined`

Operadores:
+ --> se utiliza para sumar number o para concatenar strings.
"-", "/","*","%", "**"

Sumar numero number + string = concatenar strings

---

CSS

pseudo-elementos: elementos que no pertenecen a la página pero se generan sobre elementos que ya existen.

```css
p::before{
  content="":
}

after, first-letter, first-line, selection, etc.
```

## Día 7 - 30 de Abril

Pseudo-classes: Diferentes estados que puede tener un elemento. Ej.: `:hover`, `:visited`, `:link`, etc.

Flexbox: librería que se ocupa de posicionar elementos html.
  - Necesita un elemento contenedor al que se aplica el flex: `display:flex` para modificar el comportamiento de los hijos
  - Propiedades del contenedor: `flex-flow: column wrap`, `justify-content: center`, `align-items: center`
  - Propiedades de los hijos: `order: 1`, `align-self`




