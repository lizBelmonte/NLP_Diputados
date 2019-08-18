# ¿Qué hicieron los Diputados de la LXIII Legislatura?
(Según sus palabras)

Con este código analizo el desempeño de los Diputados de la LXIII Legislatura, la cual corresponde al periodo de 01 septiembre 2015 a 31 agosto 2018. Utilizando como base los Informes de actividades de diputados de la LXIII Legislatura,
publicados en la [Gaceta Parlamentaria](http://gaceta.diputados.gob.mx/)  

## Archivos disponibles en txt:

  * [Diputados](https://github.com/lizBelmonte/NLP_Diputados/blob/master/data.json)

La información que contiene el archivo es la siguiente:

* Doc_Name: corresponde al nombre con el que el archivo fue descargado originalmente.
* Entidad: estado de la República del Diputado.
* Grupo: grupo Parlamentario (partido político) al que pertenece el Diputado.
* Nombre: Nombre del Diputado.
* text: el informe como tal y sin limpiar.

## Paquetes destacados:

  * `pdftools` también de rOpenSci, para extraer el contenido de los archivos en formato pdf;

## Contenido:

Es importante señalar que no todos los Diputados presentaron su informe, y que en algunos casos no se pudo extraer el texto de la versión de PDF.
En resumen, se cuenta con los informes de 340 Diputados.

Los cuales están distribuidos por Partido Político de la siguiente manera:

![Diputados por partido](https://github.com/lizBelmonte/NLP_Diputados/blob/master/gfx/partidos.png)

La distribución de los informes por Estado del país al que representan se muestra en la siguiete figura:

![Diputados por estado](https://github.com/lizBelmonte/NLP_Diputados/blob/master/gfx/estados.png)
