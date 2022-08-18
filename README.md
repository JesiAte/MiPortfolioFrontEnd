# este es el primer intento de modelo de portfolio 17.8.2022

<!--
width: ANCHO
margin: MARGEN, PUEDE TENER DE UNO A CUATRO VALORES QUE SE ASIGNAN EN LOS SENTIDOS DE LAS AGUJAS DEL RELOJ
padding: DESPLAZAMIENTO INTERNO DEL ELEMENTO QUE ESTEMOS TRATANDO DE ORDENAR

% REM Y EM SE AJUSTAN A CUALQUIER DISPOSITIVO


 HTML utiliza "marcas" para etiquetar texto, imágenes y otro contenido para mostrarlo en un navegador Web. Las marcas HTML incluyen "elementos" especiales como <head>, <title>, <body>, <header>, <footer>, <article>, <section>, <p>, <div>, <span>, < img>, <aside>, <audio>, <canvas>, <datalist>, <details>, <embed>, <nav>, <output>, <progress>, <video>, <ul>, <ol> , <li> y muchos otros.

<! DOCTYPE html>  - el tipo de documento. Es un preámbulo requerido

<html> </ html > - el elemento <html>. Este elemento encierra todo el contenido de la página entera y, a veces, se conoce como el elemento raíz.

<head> </head>  - el elemento <head>. Este elemento actúa como un contenedor de todo aquello que desea incluir en la página HTML que no es contenido visible por los visitantes de la página. Incluye cosas como palabras clave (keywords), una descripción de la página que quieres que aparezca en resultados de búsquedas, código CSS para dar estilo al contenido, declaraciones del juego de caracteres, etc.

<meta charset = "utf-8">  - <meta>. Este elemento establece el juego de caracteres que tu documento usará en utf-8, que incluye casi todos los caracteres de todos los idiomas humanos. Básicamente, puede manejar cualquier contenido de texto que pueda incluir. No hay razón para no establecerlo, y puede evitar problemas en el futuro.

<title> </ title >  - el elemento <title> establece el título de tu página, que es el título que aparece en la pestaña o en la barra de título del navegador cuando la página es cargada, y se usa para describir la página cuando es añadida a los marcadores o como favorita.

<body> </body>  - el elemento <body>. Encierra todo el contenido que deseas mostrar a los usuarios web que visitan tu página, ya sea texto, imágenes, videos, juegos, pistas de audio reproducibles, y demás.

<h1>,…, <h6>  Los elementos de encabezado implementan seis niveles de encabezado del documento, <h1> es el más importante, y <h6>, el menos importante. Un elemento de encabezado describe brevemente el tema de la sección que presenta. La información de encabezado puede ser usada por los agentes usuarios, por ejemplo, para construir una tabla de contenidos para un documento automáticamente. Sus etiquetas son <h1>,…, <h6> y </h1>,…, </h6>.

<p>  El elemento <p> (párrafo) es apropiado para distribuir el texto en párrafos. Sus etiquetas son <p> y </p>.

<b>  El elemento HTML <b> indica que el texto debe ser representado con una variable bold, o negrita, de la tipografía que se esté usando. Sin darle al texto importancia adicional. Sus etiquetas son <b> y </b>.

<strong>   El elemento <strong> destaca el texto. Sus etiquetas son <strong> y </strong>. El elemento <strong> le da al texto más énfasis que el elemento <b>, con una importancia más alta semánticamente.

<i>  El elemento HTML <i> muestra el texto marcado con un estilo en cursiva o itálica. Sus etiquetas son <i> e </i>.

<em>   El elemento HTML <em> es apropiado para marcar con énfasis en el texto. El elemento <em> puede ser anidado, con cada nivel de anidamiento indicando un mayor grado de énfasis. Sus etiquetas son <em> y </em>.

<br>  El elemento HTML <br> produce un salto de línea en el texto (retorno de carro). Es útil para escribir un poema o una dirección, donde la división de las líneas es significante.  No lo utilices para incrementar el espacio entre líneas de texto; para ello utiliza la propiedad margin de CSS o el elemento <p>.

<li>  El elemento HTML <li> o elemento de lista declara cada uno de los elementos de una lista. Sus etiquetas son <li> e </li>.

<ol>  El elemento <ol> permite definir listas o viñetas ordenadas con numeración o alfabéticamente. Sus etiquetas son <ol> y </ol>.

<ul>  El elemento HTML <ul> de "lista desordenada" - lista no ordenada. crea una lista no ordenada. Sus etiquetas son <ul> y </ul>.

<div>  El elemento HTML <div> es exclusivamente usado como contenedor para otros elementos HTML. En conjunto con CSS, el elemento <div> puede ser usado para agregar formato a un bloque de contenido. Sus etiquetas son <div> y </div>.

<img>  El elemento HTML <img> posee los atributos src y alt pero no tiene etiqueta de cierre. Se puede representar así <img src = "imagen.png" alt = "Mi descripción de imagen"> Un elemento <img> no encierra contenido. También a este tipo de elemento se lo conoce como elemento vacío. El propósito del elemento <img> es desplegar una imagen en la página web, en el lugar que corresponde según la estructura del documento.
El nombre de archivo de la imagen de origen está especificado por el atributo src. Los navegadores web no siempre muestran la imagen a la que el elemento hace referencia. Es el caso de los navegadores no gráficos (incluidos aquellos usados ​​por personas con problemas de visión), si el usuario elige no mostrar la imagen, o si el navegador es incapaz de mostrarla porque no es válida o soportada. En ese caso, el navegador la reemplazará con el texto definido en el atributo alt

<a>  El Elemento HTML Anchor <a> crea un enlace a otras páginas de Internet, archivos o ubicaciones dentro de la misma página, direcciones de correo, o cualquier otra URL que especifiquemos en sus atributos. Se puede representar así <a href="https://developer.mozilla.org/es/docs/Web/HTML/Element/a"> </a> donde la dirección del enlace está especificada por el atributo href. 
Dentro del atributo href la URL puede escribirse de forma absoluta (incluyendo el dominio) o relativa (sin incluir el dominio) solo para enlaces dentro del mismo dominio. Tanto de una forma u otra, la ruta de carpetas debe especificarse.
Siguiendo con la descripción del atributo href del elemento <a>, podemos dividir los enlaces o links en 3 tipos:

Enlaces internos: son los que se dan entre páginas web del mismo dominio.
Enlaces externos: son los que se dan entre páginas web de distinto dominio.
Enlaces de posición (o marcadores):
A. De un lugar a otro dentro de la misma página.
B. De un lugar a otro lugar concreto de otra página del mismo dominio.
C. De un lugar a otro lugar concreto de una página de otro dominio.-->