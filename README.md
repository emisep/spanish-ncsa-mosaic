NCSA Mosaic en español
(Texto original por alandipert)
===========

![GitHub visto con Mosaic](http://github.com/downloads/alandipert/ncsa-mosaic/github.png "GitHub con Mosaic")

Aquí está NCSA Mosaic 2.7, uno de los primeros navegadores web con interfaz gráfica.
Si utilizas Ubuntu o algo por el estilo, tu máquina del tiempo está lista para partir, sólo sigue las instrucciones más abajo para podercompilar e iniciar el programa.

Muchas gracias a [Sean MacLennan y Alan Wylie](http://seanm.ca/mosaic/) por hacer el trabajo duro, y, por supuesto, nos sacamos el sombrero en honor a Marc Andreessen, Eric Bina y el resto del equipo de desarrolladores de [NCSA](http://www.ncsa.illinois.edu/) que dieron un gran golpe.  ¡Muchas gracias!

Compilar
--------

* Primero, instala estos paquetes:

      sudo apt-get install build-essential libmotif-dev libjpeg62-dev libpng12-dev x11proto-print-dev libxmu-headers libxpm-dev libxmu-dev

* Luego, comienza a compilar con:

      make linux

* ... y arranca!

      src/Mosaic
