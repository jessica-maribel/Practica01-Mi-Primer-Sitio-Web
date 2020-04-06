# Practica01-Mi-Primer-Sitio-Web

Universidad Politecnica Salesiana
Carrera de Computacion
Autor: Jessica Maribel Guncay Carchipulla 

La pagina web se desarrollo en base al tema "Estilo de Vida Saludable"
Contiene ocho paginas que lleva como nombre
  1 index.html
  2 vida-sana.html
  3 nutricion.html
  4 ejercicio.html
  5 mente.html
  6 descanso.html
  7 habits.html
  8 contactanos.html

Para mejor distribucion de las imagenes, audios y videos utilizadas dentro de la pagina
se crearon carpetas para imagenes, audios y videos

Documentacion

####<!DOCTYPE html >   nos sirve para indicar que nuestro documento está escrito siguiendo la estructura determinada por un DTD
####<html lang="es">   se utiliza para indicar el idioma del contenido de un elemento
####<head>    esta etiqueta nos sirve para la cabecera del documento, contiene como títulos
####<title>    etiqueta para dar título a la página .html
####<meta charset="utf-8"   />   establece una codificación de caracteres como signos de puntuación, tildes 
####<body  bgcolor="turquoise"> esta etiqueta sirve para el cuerpo del documento y lo que contiene como imágenes, videos, enlaces, entre otros. Tambien el bgcolor se utiliza en HTLM4 para darle color 
####<header> // la etiqueta header sirve para darle la cabecera a nuestra pagina donde va el título, logotipo y algunos mas 
####<nav> //estas etiquetas se implementan después del header ya no forma parte, nos sirve para realizar menu, donde se colocará enlaces internos para moverse dentro del sitio web. 
####<ul> //para una no ordenada lista, y se representa por <li>
####<ol> para listas ordenadas y se representa por <li>
####<li><a href="archivo">¿Quiénes Somos?</a></li>  se representa para un enlace, en este caso para abrir archivo index.html  y el href sirve para dirección URL o path
####<h1 style="background-color: cornsilk;"> esta etiqueta establece encabezados, tomando en cuenta h1 mayor tamaño hasta h6 menor tamaño
####<section> nos sirve para englobar un texto que guardan relación entre ellos podemos agregar artículos, títulos o encabezados
####<a name="seccion1"> sirve para dar destino a un vínculo, en este caso para abrir la sección 
####<article> esta se ubica dentro de la etiqueta section que se utiliza para dividir y ordenar contenidos en el interior de la página. 
####<p> se coloca dentro de la etiqueta articule se utiliza para párrafos del texto 
####<img src="ubicacion" alt="Estilo de vida Sana"/> etiqueta que se utiliza para agregar imágenes dentro del documento se utiliza el path relativo o absoluto
####Src= el url donde se encuentra la imagen
####Alt=sirve para texto alternativo, información de la imagen 
####<aside> esta etiqueta la usamos fuera de la etiqueta section, se utiliza para información que no esta relacionada con el contenido de la pagina
####<table style="height: 250px; width: 950px;" border="2"> esta etiqueta define el comienzo y final de la tabla 
####Style sirve para dar información de estilo, como height, width, border
####<caption> sirve para darle titulo a la tabla
####<tr> sirve para el comienzo y final de una table 
####<th colspan="3"> representa las celdas de encabezado en la tabla, colspan se utiliza para combinar celadas 
####<video controls width="420" height="240">
####<source src="videos/salud.mp4" type="video/mp4">
####</video>  esta etiqueta sirve para insertar videos que se encuentran en nuestro ordenador; controls muestra los controles como pausa, volumen en la página web, src ubicación o url del video. 

####iframe width="560" height="315" src="https://www.youtube.com/embed/1Y-OUvvesRg" 
####allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" 
####allowfullscreen></iframe> esta etiqueta nos permite insertar URL de otra página en la página actual, como reproducir videos de YouTube.

####<audio src="audios/mente.mp3" controls >
####</audio> esta etiqueta sirve para generar audio, controls muestra los controles como pausa, volumen en la página web, src ubicación o url del audio. 

####<footer> esta etiqueta se utiliza para el pie de página, se pone enlaces como correo, teléfonos, copyright
####<a href="tel:0969937042">  crea enlace para llamar a un numero de teléfono
####<a href="malito:gjessica@est.ups.edu.ec"> crear enlace para enviar un correo electrónico

Para la visualizacion de la pagina web se desarrollo una rama 
 https://jessica-maribel.github.io/Practica01-Mi-Primer-Sitio-Web/
