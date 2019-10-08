## First Class:
CSS, es un lenguaje que permite a crear diseño web
Permite cambiar el tamaño, color, de fuentes, layouts u otros.
Presentación del proyecto.

## Second Class:
Una página web esta construida por 3 tecnologías
HTML, para crear la estructura
CSS, para realizar el diseño o Presentación del sitio
JavaScript, para la interacción del usuario con el sitio
CSS fue presentado en HTML4 y ha sido revolucionado día tras día para tener mejoras
Actualmente esta en la versión CSS3

## Third Class:
Recursos para consultar propiedades, selectores, funciones de CSS

## Quizz:
Was HTML meant to be a presentational language?
R// No. It's impractical to create websites where the content of each HTML page isn't separate from the presentation 

Are we required to memorize every CSS selector, property and value available?
R// No. A solid understanding of the concepts and reliable references is all we need.

Mozilla Developer Network, Web Platform Docs, and W3C are helpful CSS resources.
R// True. These resources always have important, up-to-date information on a given CSS topic.

"CSS" stands for:
R// Cascading Style Sheets

CSS is what handles the _ _ _ _ _ layer of a web page.
R// presentation

CSS was introduced in:
R// HTML4

## Fourth Class:
Conocimiento de las 3 formas de agregar CSS
Inside HTML, que es dentro de las etiquetas style, dentro del head 
Inline HTML, que es dentro de cada etiqueta especifica con el atributo style
External CSS, que es cuando creamos un archivo css afuera del HTML y lo llamamos con Link
Se vieron varias propiedades de CSS como:
font-weight: Funciona para cambiar la fuente, ya sea italica, bold, entre otros
font-size: Funciona para cambiar el tamaño de la fuente
background-color: Para colocar un color de fondo al elemento
color: Agregar color a las letras
Las inline HTML, son más especificas que un inside HTML, pero no son recomendadas, ni tampoco las inside,
ya que se puede tener muchas lineas de codigo y es dificil mantener todas en un momento, 
por eso es mejor tener una external CSS

## Fifth Class:
Uso de la propiedad
text-align: Funciona para brindarle una posicion al texto
Uso de external stylesheets, sus beneficios y fexibilidad al momento de trabajar proyectos grandes

## Sixth Class:
Funcionalidad de @import dentro de otras hojas de estilos
Uso de la etiqueta link y sus 2 propiedades, rel y href

## Quizz:
What is a downside to using internal styles on large projects?
R// The browser is required to download all styles each time a new page loads and 
We're duplicating many styles across multiple pages.

We write inline styles directly inside an element's tag, using which of the following attributes?
R// style 

What file extension do we need to use when creating a style sheet?
R// .css

We usually embed internal styles in the <head> section of the HTML document, and they're defined within the 
R// style tag

What attribute specifies the relationship between the current HTML document and the linked document?
R// rel

What are the three methods for adding CSS to a page?
R// inline styles, internal styles and external style sheet

Which method allows us to bring one or more style sheets into another style sheet?
R// @import

With an _ _ _ _ _ style sheet, we can change the look of an entire website with one file.
R// external

## Sevent Class:
Selectores de CSS, 
Universal Selector, aplica estilos a todos los elementos en nuestro HTML, empieza con *
Sintaxis de reglas de CSS, primero el selector, seguido de {} y dentro de las llaves, las propiedades
seguido de : y el valor que se cambiara, terminado con ;

## Eight Class:
Type Selectors,
La sintaxis es con la etiqueta HTML, seguido de las llaves {}
y dentro de las llaves, las propiedades y valores.
Uso de la propiedad margin
Uso de colores hexadecimales

## Ninth Class:
ID selectors, son selectores especificos de una etiqueta que tenga como atributo un ID unico
Solo se puede usar un ID name en una etiqueta en todo el archivo HTML
Los ID selectors, son especificos y pueden ser utiles pero solo pueden apuntar a un unico elemento
Uso de la propiedad border en CSS
y funcionamiento del ID en anchor tags 

## Tenth Class:
Class Selectors, nos permiten reutilizar clases en distintos tags HTML, 
Las class selectors apuntan a las etiquetas con el atributo class,
Nos ayudan a reutilizar codigo

## Eleventh Class:
Uso de multiples veces una clase en varias etiquetas HTML

## Twelve Class:
Descendant Selectors 
Son selectores que apuntan al hijo dentro de una etiqueta HTML
Por su estructura de arbol, CSS entiende quien esta dentro de las etiquetas HTML

## Thirteen Class:
PseudoClases:
Funcionan para dar interactividad con el usuario, y su sintaxis es primero etiqueta HTML seguido de : y la PseudoClase
Se vio la pseudoclase link, visited, hover, active y focus


## Fourtheen Class:
Conclusiones de la fase, 
Uso de comentarios en CSS y su sintaxis 

## Quizz: 
Which selector targets every element on the page at once and applies the styles we set?
R// universal selector

We define the universal selector with a(n) 
R// *


When targeting an element with a type selector:
R// we use the element's HTML tag as the selector

Do IDs have browser functionality?
R// Yes. We can use IDs as fragment identifiers that create anchors in a page.

An element can only have ____  ID, and a page can only have ____  element with the same ID name.
R// one and one

Which selectors have the most specificity and carry the most weight?
R// ID selectors 

A descendant selector consists of:
R// two or more selectors separated by whitespace

Which of the following are common CSS pseudo-classes?
R// :link, :visited, :hover and :active

You create a class selector with a ___ character
R// .

## Fifteen Class:
DATA TYPES:
Existen muchos tipos de datos en CSS, entre los más comunes existe, colores, tamaño y numeros.
Adicional a otros como imagenes, gradiantes y URI.


## Sixteen Class:
Lenght Types:
Existen 6 tipos de tamaños en CSS, entre ellos el más popular px (pixeles),
Son valores absolutos, que son utilizados para definir un tamaño que nunca cambiaría con el tamaño de la pantalla o 
la densidad de pixeles.

## Seventeen Class:
Porcentaje Types:
Son valores relativos y permiten ser dinamicos al momento de ser visualizados en distintas pantallas o densidad de pixeles
Son utilizados para brindar responsive design y ayudan a adaptar el layout en distintos
dispositivos.

## Eighteen Class:
Unidad relativa em,
Es relativa y funciona para tener fuentes escalables y dependientes a nuestra fuente padre,
hay que tener cuidado en usar esta unidad, ya que dependiendo de en que padre nos encontremos, 
puede variar dichas fuentes.

## Nineteen Class:
Unidad relativa rem,
Funciona igual que los ems, con la diferencia que ellos no son afectados por padres dentro de nuestro HTML,
el apunta directamente a la fuente root del HTML

## Twenty Class:
Colores,
Existen 3 formas de declarar colores en CSS:
1.- Keywords, es la forma de escribir el color, existen varios, los más comunes, son: blue, white, black, etc,
2.- Hexadecimal, su sintaxis es # seguido del valor hexadecimal, puede tomar valores de 0-9 y de a-f, representando azul, rojo y verde
3.- funcion rgb, se declara con la palabra rgb, seguido de parentesis (), y dentro de el, toma 3 valores de 0-255, cada uno representa, red, green and blue
4.- Colores transparentes rgba, al igual que la funcion rgb, solo que ahora tiene un 4to parametro, llamado alpha, que ayuda a dar transparencia al color, el valor puede ir de 1% a 100% o .1 a 1

## Quizz
In the rgb function, the value rgb( 255, 255, 255) represents 100% white, while the value rgb( 0, 0, 0) represents 100% black.

The color value steelblue is an example of which of the following?
R// predefined Keyword

An RGB color value defined in hexadecimal notation uses:
R// A combination of red, green and blue colors using three or six hexadecimal characters

The RGBa color function:
R// extends the RGB model by allowing us to set the opacity of a color via alpha channel

We can abbreviate the hex value #cc7733 to #c73.

## Twenty First Class:
Propiedades para texto
1.- Text-align: permite alinear el texto de varias formas, como left, right, center o justify
2.- Text-transform: permite cambiar el texto a mayuscula, minuscula o capitalizado (prima letra mayuscula)
3.- Font-weight: permite cambiar le importancia de texto a negrita o normal, adicional a valores numericos de 100 a 900, donde 100 es lo mas delgado y 900 lo mas resaltado
4.- Text-decoration: permite darle decoracion al texto, como subrayado entre otros.

## Twenty second class:
Font-family:
Es una propiedad que permite configurar tipo de fuente que muestre en nuestra pagina,
Permite utilizar por defecto fuentes instaladas en las computadoras, como arial, helvetica, entre otros
Se puede configurar mas de 1 fuente, seguido de comma, por si el usuario no tiene esa fuente, el navegador intentará mostrar la siguiente fuente

## Twenty Three Class:
line-height propiedad,
Permite tener espacios entre textos, es recomendable utilizar valores pequeños para no afectar mucho los textos,
existe una propiedad llamada font,
permite encapsular todas las propiedades antes vistas en una sola linea y ahorrar codigo

## Twenty Four Class:
Box Model Content,
Es un modelo donde cada etiqueta de HTML es visto como una caja y sus diferentes componentes como:
margen, padding y bordes.
El padding es el espacio que hay dentro de la caja, donde existe el contenido 
El borde es el borde que se le puede dar a la caja
El margen es el espacio que se puede crear afuera de la caja para separar con otros elementos

## Twenty Five Class:
Padding:
Se puede usar 5 propiedades para el padding:
padding-right: permite crear padding solo al lado derecho
padding-bottom: 
padding-left:
padding-top 
ó únicamente padding: el orden de los valores en la propiedad paddin es:
el primer valor para el top, el segundo para right, el tercero para bottom y el 4to para left, 
funciona como las manecillas del reloj.
Se puede utilizar valores relativos o absolutos para declarar padding.

## Twenty Six Class:
border
Se puede utilizar 4 propiedades para definir un borde:
border-size: Se define el tamaño o magnitud del borde
border-style: Se define como sera el borde, puede ser solid, dashed o docked
border-color: Se define el color del borde
o utilizamos el shorted handed propiedad únicamente border:
dentro de esta ultima propiedad podemos pasar los 3 parametros antes mencionados y crear el borde en una sola instruccion

## Twenty Seven Class:
Margin:
Tiene las mismas propiedades que border, y padding, 
Uso de Google Chrome Developer Tools 

## Twenty Eight Class:
Display Property:
Tiene 3 valores, inline, block e inline-block,
Existen etiquetas que vienen con inline display por defaut como las anchor tags (a) o span
Otros vienen con el valor block por default como (h1), p tags entre otros,
Esta propiedad permite tener un mejor control del layout y los elementos.

## Quizz:
What is the order of values in the following shorthand property?
padding: 10px 20px 10px 20px;
R// top, right, bottom, left.

The same order of values in the padding property applies to the margin shorthand property. e.g. padding: top, right, bottom, left;
R// True

The _______ area creates space inside the box, while the _______ area creates space outside and around the box.
R// padding, margin

Write the declaration that will turn off the display for .featured-img: .featured-img {   _______: _______; }
R// display: none;

In the CSS box model, what is the innermost area of a "box"?
R// content area.

Which type of elements only take up as much width as they need?
R// inline

When we use the margin value _______, the browser automatically calculates the margins for each side.
R// auto

What type of elements take up the full width available based on the width of their parent element?
R// block elements 

## Twenty Nine Class:
width and height properties:
Funcionan para declarar un ancho y altura especificos a nuestros elementos,
y tener un layout controlado en sus dimensiones,
hay que tomar en cuenta que cuando inspeccionamos, tendremos otro valor de width y height y esto es porque tambien se suma
el valor de los margenes, padding y borde, por lo que si queremos definir un valor absoulto ,
deberiamos de realizar una resta para saber cual seria el width o height deseados

## Thirty Class:
box-sizing: permite ajustar nuestros width y height automaticamente, el realiza la resta y sumas del padding y margenes
para poder declarar nuestros valores sin necesidad de hacer dichas operaciones
max-widht: propiedad que permite limitar nuestros elementos a un valor maximo
funciona para limitar divs o imagenes a que cuando la pantalla sea más grande, no se pongan mas grande, o cuando la pantalla sea pequeña
mantengan un tamaño constante

## Thirty One Class:
background-image: permite definir una imagen en nuestro background, 
por defecto, la propiedad repite la imagen hasta que complete el area asignado del div o etiqueta.
existen propiedades como background-size: que permite definir un tamaño para la imagen propiedades
background-repeat: en esta propiedad podemos definir si la imagen se repita o no,
con repite o no-repeat, adicional hay otros dos valores como 
repeat-x, que hara que se repita la imagen en el eje x (horizontal)
repeat-y, que hara que se repita la imagen en el eje y (vertical)

## Thirty Two Class:
background-size: cover property, permite ajustar la imagen al tamaño del div,
existe la posibilidad de colocar la imagen en distintas posiciones, como left, right, center o valores de porcentajes o medidaes
con la propiedad background-position

## Thirty Three Class:
Float:
Es una propiedad que permite definir de que lado posicionar nuestros elementos
Elimina la propiedad de block de los elementos y permite aliniar dos divs en la misma fila, por ejemplo

## Thirty Four Class:
Profundizar en float.


## Thirty Five Class:
list-style-position,
list-style-type:
Estas propiedades permiten trabajar con las listas, ya sean ordenadas o desordenadas.
La primera propiedad permite integrar la numeracion dentro del numeros
y la segunda propiedad permite definir formas a las listas desordenadas.

## Quizz:
The ________ property can alter the way a browser calculates the total width of an element.
R// box-sizing

Which CSS property do we use to prevent content from becoming wider than a certain width?
R// max-width

If we specify one background-position value, what will the browser assume is the vertical position value?
R// center or 50%

How does the browser calculate an element's total width value?
R// The browser adds any left/right padding and border-width values to the width value we define

Which background-repeat value repeats a background image horizontally?
R// repeat-x 

Which background-size value displays the full image while maintaining the width and height proportions?
R// cover

Which box-sizing value forces any padding and border-width values into the width and height of an element?
R// border-box

## Thirty Six Class:
text-shadow (sombra horizontal, sombra vertial, blur, color)
permite crear sombras incluso con valores negativos,
se puede combinar muchas sombras separadas con coma, y crear sombras y formar letras en 3D.
En el parametro de color, permite valores keyword, hexadecimal y rgba

## Thirty Seven Class:
box-shadow, tiene los mismos valores que text-shadow, 
solo que tiene un valor opcional, que es spread, es el 4 valor y permite
expander la sombra en toda la caja.
existe el valor inset, que permite tener el efecto de sombra dentro del elemento

## Thirty Eigh Class:
border-radius,
al igual que otras propiedades como margin, border.
Permite asignar los valores de arriba, derecha, abajo e izquierda como las manecillas del reloj
permite tener border curvados en nuestros elementos

## Thirty Nine Class:
CSS gradients
linear-gradient: permite tener mezclas de 2 o mas colores, creando una transicion de colores genial,
gradiantes... Permite definir el direccionamiento de como empieza el gradiente, por defecto empieza de arriba hacia abajo.
Podemos definir el direccionamiento con angulos, o con keywords como to top, to left, to right o to bottom.
su sintaxis es: linear-gradient(direccionamiento, color1, color2, color n);
tambien existe radial-gradient, que permite generar el gradiante como un circulo

## Forty Class:
color stop,
permite crear gradiantes mas complejos
ya que mezcla 3 colores y podemos definir el porcentaje de cada uno despues de la declaracion del color con porcentajes


## Forty One Class:
Combinacion de imagenes con linear gradient.
Permite tener una combinacion de gradiante mientras se tiene una imagen,
lo unico que se debe hacer es hacer la separacion con una coma

## Forty Two Class:
@font-face,
permite agregar fuentes externas al proyecto,
existen varias extensiones y formatos de fuentes que ayudan a tener distintas formas,
o distintos diseños.

## Quizz:
What will happen if you define a fully opaque background image or color anywhere above the bottom background layer?
R// The fully opaque layer will cover up all background layers behind it.

Which of the following CSS properties increases the space between letters?
R// letter-spacing

The color stop value ____ allows other background layers to show through a gradient.
R// transparent 

When defining multiple background values:
R// The first value listed is the topmost layer rendered, and the last value is the bottom layer.

## Forty Three Class:
Media Queries
Gracias a los media query, podemos tener diseños responsivos o adaptables a distintos dispositivos, 
tamaños de pantallas, resoluciones  etc.
La sintaxis es asi:
media (condicion) {}
podemos tener dos valores a comparar y unir dichas con el operador and 

## Forty Four Class
Implementacion de media queries en el proyecto
uso de la etiqueta HTML meta, para definir que el tamaño de dispositivo sea el correcto
y asi evitar problemas de visualizacion


## Forty Five Class
Funcionamiento de la cascada en CSS,
Funciona cuando tenemos dos reglas en un orden hacia abajo,
CSS toma la ultima declaracion como la correcta, por eso se dice que es en cascada

## Forty Six Class:
Specifity,
Es en que orden toma los valores CSS, el orden es asi
Primero los element
luego clases
luego IDs
luego inline selectors
Siendo el ultimo tener mas especifidad

## Forty Seven Class:
Initial values,
por default los elementos tiene un estilo por default de los navegadores,
si queres regresar a esos valores, únicamente podemos usar el valor initial, ya sea en 
colores, margenes, etc.

## Forty Eight Class:
Conclusiones del curso y modos para poder practicar lo que uno aprendio














































































































 


















