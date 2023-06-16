# DataAnalystJr
McCheckity check

Anotaciones de clase

Estructura Básica de un Documento HTML.

Antes que nada, debes saber que el código HTML se compone de etiquetas o marcas.
Las etiquetas en HTML son palabras clave que se escriben entre los signos <> y que el
navegador entiende.

Normalmente las etiquetas se componen de una etiqueta de apertura (entre los signos
<>), una etiqueta de cierre (entre los signos </>) y un contenido. El contenido puede ser
texto u otras etiquetas. Aunque existen algunas etiquetas que no tienen ni contenido ni
etiqueta de cierre, son una excepción. La sintaxis sería la siguiente:
<etiqueta>
contenido etiqueta
</etiqueta>

Existen otros tipos de etiquetas para crear una página web en HTML5 que nos permiten
enlazar o encuadrar otros elementos dentro de las páginas web. Algunas de las más
usadas son:
● <a>: Define y da forma a un ancla.
● <abbr>: Introduce una abreviatura.
● <address>: Especifica un elemento de dirección.
● <article>: Define una parte independiente del contenido de un documento, como
una entrada de blog o un artículo de periódico.
● <aside>: Define el contenido aparte del contenido principal. Representado
principalmente como barra lateral.
● <audio>: permite introducir un archivo de audio.
● <br>: Inserta un solo salto de línea.
● <button>: Especifica un botón pulsador.
● <canvas>: Se utiliza para representar gráficos de mapa de bits dinámicos sobre la
marcha, como gráficos o juegos.
● <div>: Define una sección en un documento HTML 5
● <form>: Para introducir formularios.
● <footer>: Representa el pie de una sección, con información acerca de la
página/sección que poco tiene que ver con el contenido de la página, como el
autor, el copyright o el año.
● <header>: representa un grupo de artículos introductorios o de navegación. Está
destinado a contener por lo general la cabecera de la sección (un elemento h1-h6
o un elemento hgroup), pero no es necesario.
● <hgroup>: Sirve para crear el encabezado de una sección.
● <h1> a <h6>: Especifica el encabezado 1 al encabezado 6.
● <img>: Introduce una sección para una imagen.
● <map>: Una etiqueta destinada a elaborar mapas de imagen.
● <nav>: Define una sección del documento destinada a la navegación.
● <p>: Etiqueta usada para escribir párrafos de texto.
● <script>: Sirve para introducir un script.
● <section>: Define una sección genérica para un documento.

HTML es un lenguaje que se compone por elementos que permiten definir la estructura
del documento. Estos elementos son los que nos posibilitan determinar cómo estará
armada la página y sus secciones. Las etiquetas nos brindan la oportunidad de definir los
elementos en el código.
<elemento1>
contenido del elemento 1
</elemento1>
<elemento2>
contenido del elemento 2
</elemento2>

Todos los elementos se dividen en dos categorías:
Elementos en bloque. Estos son los elementos que estructuran la parte principal de la
página web, dividiendo una página en bloques coherentes. Un elemento a nivel de bloque
siempre comienza con una nueva línea y ocupa todo el ancho de la página web, de
izquierda a derecha.

Los siguientes son algunos de los elementos en bloque en HTML:
<address>, <article>, <aside>, <blockquote>, <canvas>, <dd>, <div>, <dl>, <dt>, <fieldset>,
<figcaption>, <figure>, <footer>, <form>, <h1> hasta <h6>, <header>, <hr>, <li>, <main>,
<nav>, <noscript>, <ol>, <output>, <p>, <pre>, <section>, <table>, <tfoot>, <ul> y <video>.
Ejemplo.
<p>
Este párrafo es un elemento en bloque.
</p>

Elementos en línea. Los elementos en línea son aquellos elementos que diferencian la
parte de un texto dado y le proporcionan una función particular. Estos elementos no
comienzan con una nueva línea y toman el ancho según el requisito. Los elementos en
línea se utilizan principalmente con otros elementos.

Los siguientes son algunos de los elementos en bloque en HTML:
<a>, <abbr>, <acronym>, <b>, <bdo>, <big>, <br>, <button>, <cite>, <code>, <dfn>, <em>, <i>,
<img>, <input>, <kbd>, <label>, <map>, <object>, <q>, <samp>, <script>, <select>, <small>,
<span>, <strong>, <sub>, <sup>, <textarea>, <time>, <tt>, <var>.
Ejemplo.
<p>
Texto normal y... <b>Texto en negrita</b>
</p>

Un atributo en HTML son palabras especiales utilizadas dentro de la etiqueta de apertura,
para controlar el comportamiento del elemento. Los atributos HTML brindan información
adicional sobre el elemento. Cada atributo HTML tiene su nombre y valor:
<elemento atributo=”valor">contenido del elemento</elemento>
Algunos elementos no tienen etiqueta final ni contenido, estos elementos se denominan
elementos vacíos o elementos de cierre automático.

Veamos algunos atributos y cuál es su función.
● id =” ” : Para identificar un elemento único.
● class =” ” : Identificador múltiple.
● align =” ” : Alineación de contenido.
● border =” ” : Para darle borde al contenido.
● style =” ” : Para darle un estilo al contenido.
● background-color =” ” : Para color de fondo.
● href =” ” : Para enlaces html.
● height =” ” : Para determinar altura.
● width =” ” : Para determinar ancho.
● src=“ ” : Para imágenes.

Ejemplo. Usamos el elemento <a> con el atributo href y valor
https://pilares.cdmx.gob.mx/inicio
<a href="https://pilares.cdmx.gob.mx/inicio">Esto es un link</a>
Ejemplo. Usamos el elemento <img> con el atributo scr y el valor pilares.jpg
<img scr="pilares.jpg" height="400" width="600">
El ejemplo anterior también tiene atributos de height y width, que definen el alto y el
ancho de la imagen en la página web






==== 


Introducción

Desde su sillón todo el mundo oirá, verá, participará,
incluso será capaz de aplaudir, dar ovaciones,
cantar en el coro, añadir sus gritos de
participación a los de todos los demás.
─Paul Otlet, 1934

Cuando Tim Berners-Lee publicó la primera página web a finales de 1990 en el CERN, la
web era muy distinta a como la conocemos en la actualidad. Las páginas web sólo tenían
texto. En los 31 años de historia de la web, el lenguaje de marcado o etiquetado que se
emplea para crear las páginas web ha evolucionado poco a poco y se han ido
desarrollando sucesivas versiones. A la versión inicial del lenguaje se añadieron nuevas
características como las imágenes, las tablas o los marcos que permitían dividir las
páginas web en varias partes. Las páginas web fueron evolucionando y cada vez
contenían más imágenes. Los diseñadores gráficos se incorporaron al desarrollo de las
páginas web y se desarrolló una nueva disciplina: el diseño web. Además, los
navegadores web, cada vez eran más potentes y las conexiones Internet más rápidas, así
que, las páginas web cada vez mostraban más información.
Durante los primeros cinco años la web sólo servía para leer, para consumir contenidos,
no existía mucha interacción con las páginas web. Sin embargo, cuando se añadieron los
formularios la web comenzó a cambiar. Los formularios permitían un mayor grado de
interacción entre el usuario y las páginas web. Además, el lenguaje incorporó la
posibilidad de añadir nuevos tipos de contenidos a las páginas web como audio, vídeo o
animaciones y, los navegadores web se volvieron más rápidos y más potentes. Todo ello
ayudó a que las páginas web se transformarán en aplicaciones web, en inglés, Web Apps,
que permiten realizar a través de una página web las mismas tareas que
tradicionalmente se realizaban mediante un software instalado en un ordenador a partir
de un CD-ROM.
Hoy en día, a través de una página web podemos enviar correos electrónicos, podemos
jugar, podemos editar fotografías, podemos ver vídeos o incluso, podemos editar los
vídeos, todo ello a través de una página web

Fundamentos técnicos de una página web

Pero, ¿qué es el hipertexto? Según el diccionario de la lengua de la Real Academia
Española hipertexto es: conjunto estructurado de textos, gráficos etcétera, unidos entre sí
por enlaces y conexiones lógicas. Un texto normal como por ejemplo, un libro,
normalmente está limitado a una organización lineal o secuencial. Sin embargo, el
hipertexto permite saltar de un punto a otro, en un mismo texto, o a otro texto a través
de referencias. De este modo, en lugar de leer el texto de forma continua, en el hipertexto
ciertos términos están relacionados y el texto se puede leer siguiendo diferentes caminos.
Las relaciones en el hipertexto se establecen entre lo que se suele llamar como
referencias, enlaces, vínculos o hipervínculos.
Y, ¿qué es la hipermedia? El término hipermedia no figura en el diccionario de la lengua
española de la RAE pero, podemos buscar un término relacionado con hipermedia,
multimedia. Según el diccionario de la Lengua Española, multimedia es un adjetivo que
significa: que utiliza conjunta y simultáneamente diversos medios como imágenes,
sonidos y texto, en la transmisión de una información.
Por tanto, un sistema multimedia es un sistema de comunicación en el que se emplean
dos o más medios de comunicación distintos de forma concurrente. Un sistema
multimedia puede integrar texto, voz, audio, fotografías, gráficos interactivos, vídeos,
realidad virtual y otros.
Un sistema multimedia proporciona una gran riqueza y una mayor flexibilidad a la hora
de comunicar la información. La calidad multimedia no está restringida al mundo de los
ordenadores así, por ejemplo, un libro acompañado de un CD de música ya es una obra
multimedia. Para algunos autores, hipermedia es un término que nace de la unión del
hipertexto más la multimedia, por tanto, si juntamos las definiciones de hipertexto y
multimedia, podemos obtener la siguiente definición de hipermedia: conjunto
estructurado de diversos medios como textos, gráficos, imágenes y sonidos unidos entre
sí por enlaces y conexiones lógicas para la transmisión de una información.

Si la multimedia proporciona una gran riqueza a la información, el hipertexto aporta una
estructura que permite que la información pueda presentarse y explorarse siguiendo
distintas secuencias de acuerdo a las necesidades y preferencias del usuario. Existen
muchos sistemas que se basan en el hipertexto y la hipermedia pero, la web es el sistema
más conocido y por eso la web se ha convertido en sinónimo de hipertexto e hipermedia.

¿Qué son los lenguajes de marcado? 

Los lenguajes de etiquetas, también conocidos
como lenguajes de marcado o de marcas, son los que nos permiten estructurar un
documento mediante el uso de etiquetas. Los lenguajes de etiquetas no se identifican con
los de programación; esto ocurre principalmente porque los lenguajes de etiquetas no
definen algunos aspectos básicos presentes en los lenguajes de programación, como es
el caso de funciones aritméticas o el uso de variables, por citar algunos ejemplos.

El lenguaje de marcas más conocido y extendido es el HTML (“HyperText Markup
Language”, “Lenguaje de Marcado de Hipertexto”) y es el mismo que Tim Berners-Lee a
inicios de 1990 creó como un subconjunto de SGML (Standard Generalized Markup
Language, otro lenguaje de marcado). HTML es el lenguaje de etiquetas que funciona
como una de las piedras angulares de la World Wide Web, llamado también como la
Web, que no es más que un conjunto de documentos de hipertexto y/o hipermedios
(páginas web) enlazados entre sí y accesibles desde internet.

Tecnologías de software para el desarrollo de páginas web.

Para poder aprovechar al máximo el potencial de HTML5 es fundamental también
comprender el rol de las tecnologías que interactúan con este lenguaje de etiquetas y de
qué manera deben integrarse.
A continuación, nos centraremos en conocer las características principales de CSS,
JavaScript y AJAX.

● Las hojas de estilo en cascada, tal es su traducción del inglés Cascading
Style Sheets (CSS), tienen como función establecer reglas de representación
de un documento en un medio o dispositivo. Mediante estas reglas
podremos establecer medidas, colores o cualquier otra característica de
representación de una página web, para que se vea reflejada en una
pantalla de monitor, de un dispositivo móvil, una tablet, una impresora, un
dispositivo braille o un televisor. La función principal de CSS es, por lo tanto,
la de permitir separar el contenido y la estructura que se define en un
documento HTML, de la representación, que queda a cargo de las hojas de
estilos.

● JavaScript es un lenguaje multiparadigma que requiere de un intérprete
para ser ejecutado, permite la creación de páginas dinámicas, con código
que puede ejecutarse desde el lado cliente, alivianando la tarea del servidor
y disminuyendo la cantidad de peticiones que se le hagan. Por sus
características, resulta útil para validación de formularios, mostrar y aplicar
efectos, y exhibir avisos en pantalla.

● El término AJAX es un acrónimo que proviene de Asynchronous JavaScript
And XML, que, al castellano, podría traducirse como JavaScript asíncrono y
XML. Justamente este es el punto fuerte de AJAX: poder trabajar con datos
de manera asincrónica, valiéndose de JavaScript como lenguaje del lado
cliente para manejar datos que le llegan desde el servidor. De esta manera,
el motor de AJAX trabaja como un intermediario entre el cliente y el
servidor, pero, en lugar de demorar procesos, los administra de tal manera
que es posible, por ejemplo, la recarga de solo algunas partes de una
página web. Esta posibilidad cambia el paradigma de la necesidad de una
recarga completa de la página y permite construir aplicaciones web más
potentes, emulando incluso a muchas de las soluciones que se veían
posibles solo en software de escritorio.

Funcionamiento del navegador

Es importante que todo el mundo tenga acceso a la web, pero también es fundamental
que todos comprendamos las herramientas que utilizamos para acceder a ella. Usamos
navegadores web como Mozilla Firefox, Google Chrome, Microsoft Edge y Apple Safari
todos los días, pero ¿entendemos qué son y cómo funcionan?
Un navegador web te lleva a cualquier lugar de Internet. Recupera información de otras
partes de la web y la muestra en tu escritorio o dispositivo móvil. La información se
transfiere mediante el Protocolo de Transferencia de Hipertexto (HTTP), que define cómo
se transmiten el texto, las imágenes y el video en la web. Esta información debe
compartirse y mostrarse en un formato consistente para que las personas que utilizan
cualquier navegador, en cualquier parte del mundo, puedan ver la información.
Lamentablemente, no todos los fabricantes de navegadores eligen interpretar el formato
de la misma manera. Para los usuarios, esto significa que un sitio web puede funcionar y
verse diferente. Crear una experiencia consistente entre navegadores, para que los
usuarios puedan disfrutar de internet, sin importar el navegador que elijan, se llama
estándares web.
Cuando el navegador web obtiene datos de un servidor conectado a Internet, utiliza un
software llamado motor de renderizado para traducir esos datos en texto e imágenes.
Estos datos están escritos en "lenguaje de marcas de hipertexto" (HTML) y los
navegadores web leen este código para construir lo que vemos, escuchamos y
experimentamos en Internet.
Los hipervínculos permiten a los usuarios seguir una ruta a otras páginas o sitios en la
web. Cada página web, imagen y video tiene su propio Localizador Uniforme de Recursos
(URL), que también se conoce como dirección web. Cuando un navegador visita un
servidor en busca de datos, la dirección web le dice al navegador dónde buscar cada
elemento que se describe en el html, que luego le dice al navegador dónde situarlo en la
página web.

<!doctype html>
<html>
<head>
	<title>Mi primer página</title>
</head>
<body>
<h1>Hola mundo</h1>
<h3>El comienzo de un nuevo proyecto</h3>
<p>Estas visualizando el contenido de <stong>mi primer página</strong></p>
</body>
</html>
















16/junio/2023





Atributos globales

|Atributo|Valor|
|:--------:|:--------:|
|accesskey|caracter|
|*Para generar atajos de teclado para el elemento actual.*|
|class|nombre_clase|
*Se utiliza para proporcionar el nombre de clase para el elemento actual. Se utiliza principalmente con la hoja de estilo*|
|contenteditable|True,False|
|*Determina si el contenido de un elemento es editable o no.*|
|contextmenu|id menú|
|*Define el id para el elemento (<menu>) que se utiliza como menú contextual (aparece un menú al hacer clic derecho) para un elemento.*|
|data|algún valor|
|*Para almacenar datos privados específicos de elementos a los que se puede acceder mediante JavaScript.*|
|dir|rtl,ltr,auto|
|*Especifica la dirección de un contenido dentro del elemento actual.*|
|draggable|true,false,auto|
|*Especifica si el contenido dentro de un elemento se puede mover o no mediante la API de arrastrar y soltar*|
|dropzone|copy,move,link|
|*Especifica la acción que se realiza en el elemento arrastrado cuando se suelta. Por ejemplo: si se copia, mueve o vincula*|
|Hidden| |
|*Para ocultar un elemento de la vista*|
|id|identificador|
|*Especifica una identificación única para el elemento. Con CSS y JavaScript*|
|lang|Código de lenguaje|
|*Idioma principal para el contenido de un elemento.*|
|style|estilo (en línea, header, externo)|
|*Para aplicar estilo a un elemento.*|
|spellcheck|true,false|
|*Especifica si el contenido debe revisarse buscando errores ortográficos (o no)*|
|tabindex|número|
|*Determina el orden de tabulación de un elemento (su indentación).*|
|title|texto|
|*Proporciona el título/nombre/o información adicional al elemento.*|


Semántica
En 2004 Ian Hickson, el autor de la especificación de HTML5, analizó mil millones de páginas web utilizando el motor de búsqueda de Google intentando identificar la manera en la que la web real estaba construida. Uno de los resultados de este análisis fue la publicación de una lista con los nombres de clase más utilizados. Este estudio revela que los desarrolladores utilizan clases (o IDs) comunes para estructurar los documentos, esto llevó a considerar que quizás fuese una buena idea crear etiquetas concretas para reflejar estas estructuras: la web semántica.

En cualquier idioma es esencial comprender el significado de las palabras durante la comunicación y si se trata de una comunicación informática se vuelve aún más crítica. HTML5 proporciona elementos semánticos que facilitan la comprensión del código.

En este sentido la semántica define el significado de palabras y frases, es decir, tener elementos semánticos es equivalente a tener elementos con signficado.

*h2*¿Por qué usar elementos semánticos?

*h3*Mucho más fácil de leer
Probablemente lo primero que notará al mirar el primer bloque de código usando elementos semánticos. Como programador podría estar leyendo cientos o miles de líneas de código, cuanto más fácil sea leer ese código, más fácil será su trabajo. En general, los elementos semánticos también conducen a un código más consistente, HTML5 introduce elementos específicos para poder definir secciones del documento y también características que pretenden hacer de la semántica una capacidad importante para el lenguaje.

En lo que se refiere a la estructura del documento, en HTML4 estábamos acostumbrados a definir las partes del cuerpo mediante el uso de la etiqueta "div". El problema se planteaba en la imposibilidad de asignarles la semántica correspondiente a las diferentes partes, por ejemplo: si bien podíamos aplicar un "id" con el valor "nav" o "footer" (navegación o pie) esto no era más que el valor de un atributo y no le daba un significado semántico al elemento. A partir de HTML5 se definen etiquetas que nos permiten estructurar el cuerpo de una página con una semántica específica para cada elemento:
<header>
<hgroup>
<nav>
<section>
<article>
<aside>
<footer>
<figure>
<figcaption>
<time>
<details>
<summary>
<mark>

Nos permiten definir una estructura semántica en nuestros documentos HTML y a la vez un código mucho más claro de leer tanto para los desarrolladores como también para los agentes informáticos (motores de búsqueda y sus robots, dispositivos electrónicos para facilitar las características de accesibilidad).
