# ¿Qué hicieron los Diputados de la LXIII Legislatura?
(Según sus palabras)

Con este código analizo el desempeño de los Diputados de la LXIII Legislatura, la cual corresponde al periodo de 01 septiembre 2015 a 31 agosto 2018. Utilizando como base los Informes de actividades de diputados de la LXIII Legislatura,
publicados en la [Gaceta Parlamentaria](http://gaceta.diputados.gob.mx/)  

## Archivos disponibles en txt:

  * [Diputados](https://github.com/d4tagirl/uruguayan_parliamentary_session_diary/raw/master/data/diputados.csv)

## Paquetes destacados:

  * `robotstxt` de [rOpenSci](https://ropensci.org/), para ver si la sección del sitio web que quiero navegar permite ser accedida por un robot 🤖;
  * `rvest`, para explorar la web y descargar los Diarios de Sesiones;
  * `pdftools` también de rOpenSci, para extraer el contenido de los archivos en formato pdf;

## Contenido:

Es importante señalar que no todos los Diputados presentaron su informe, y que en algunos casos no se pudo extraer el texto de la versión de PDF.

En resumen, se cuenta con los informes de 340 Diputados los cuales están distribuidos por Partido Político de la siguiente manera:

![Frecuencia de las sesiones de Diputados y Senadores](https://github.com/lizBelmonte/NLP_Diputados/blob/master/gfx/partidos.png)
