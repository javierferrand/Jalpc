---
id: 25
title: 'Gu&iacute;a para abrir programas r&aacute;pidamente desde el teclado'
date: 2007-06-01T23:02:56+00:00
author: Javier F.
layout: post
guid: http://vidaenorden.com/blog/como-iniciar-aplicaciones-rapidamente-desde-el-teclado/
permalink: /guia-para-abrir-programas-rapidamente-desde-el-teclado/
tags:
  - atajos de teclado
  - enlaces
  - guía
  - windows
---
Este es uno de esos _&#8216;trucos&#8217;_ que empiezan por curiosidad y terminan siendo indispensables al interactuar con el pc. Estoy hablando hoy de iniciar las aplicaciones en unos pocos pasos utilizando únicamente el teclado, sin el mouse, sin ir a Inicio -> Programas ->, etc., etc., etc., y tener que buscar ese enlace en un montón de menús.

La idea detrás de esto es sacar provecho del diálogo _&#8216;Ejecutar&#8217;_ el cual invocamos con la combinación de teclas **Win+R** (Windows+Run) y allá escribir el nombre o la abreviación que escojamos de la aplicación que queremos abrir. La tecla **Win**, es aquella que tiene dibujada la banderita/logotipo de Windows y se encuentra en la posición inferior izquierda del teclado, al lado de la tecla **Alt**. Bueno, empecemos:

**1. Crear una carpeta.** Crearemos una carpeta donde pondremos todos los enlaces que queremos utilizar como _&#8216;lanzadores&#8217;_ de las aplicaciones. Particularmente, guardo mis enlaces junto con mis documentos y archivos importantes en una partición aparte; la mía tiene como nombre: _&#8216;shortcuts&#8217;_. En el ejemplo mi carpeta tiene ya todos los enlaces, en su caso estará vacía.

[![Crear una carpeta](http://localhost/blog/wp-content/uploads/2007/06/01_win-run_shortcuts_crear_carpeta.jpg)](http://localhost/blog/wp-content/uploads/2007/06/01_win-run_shortcuts_crear_carpeta.jpg "Crear una carpeta")
  
<!--more-->


  
**2. Incluir la ruta de la carpeta en las variables de entorno de Windows.** Debemos incluir la ruta completa a la carpeta que recién creamos en las opciones de configuración de las variables de entorno. Hacemos click derecho sobre el ícono de _&#8216;Mi PC&#8217;_ en el escritorio de Windows, seleccionamos la pestaña de _&#8216;Opciones avanzadas&#8217;_ y allí hacemos click en _&#8216;Variables de entorno&#8217;_.

[![Variables de entorno](http://localhost/blog/wp-content/uploads/2007/06/02_win-run_shortcuts_variables-de-entorno.jpg)](http://localhost/blog/wp-content/uploads/2007/06/02_win-run_shortcuts_variables-de-entorno.jpg "Variables de entorno")

Aquí vamos al segundo recuadro, seleccionamos la variable de sistema _&#8216;Path&#8217;_ y hacemos click en el botón _&#8216;Modificar&#8217;_. Allí incluiremos la ruta completa de nuestra carpeta para los enlaces, en mi caso es `d:/javier_f/shortcuts`. Note que los valores de variable están separados por punto y coma (;), no olvidemos incluirlo. A partir de este punto, todos los enlaces que incluyamos en nuestra carpeta se podrán ejecutar desde el diálogo _&#8216;Ejecutar&#8217;_.

[![Modificar path](http://localhost/blog/wp-content/uploads/2007/06/03_win-run_shortcuts_modificar_path.jpg)](http://localhost/blog/wp-content/uploads/2007/06/03_win-run_shortcuts_modificar_path.jpg "Modificar path")

[![Modificar variable](http://localhost/blog/wp-content/uploads/2007/06/04_win-run_shortcuts_modificar-variable.jpg)](http://localhost/blog/wp-content/uploads/2007/06/04_win-run_shortcuts_modificar-variable.jpg "Modificar variable")

**3. Copiar los enlaces.** En este punto, vamos a copiar los enlaces de las aplicaciones o programas favoritos a la carpeta creada y les cambiaremos el nombre por uno más corto o una abreviación para iniciar y recordar los programas más fácilmente. Vamos a arrastrar uno de los enlaces del menú de programas a la carpeta recién creada; en el ejemplo tomé el enlace a OpenOffice-Calc, lo arrastré con el click derecho del mouse a la carpeta nueva y seleccioné _&#8216;copiar&#8217;_. Allí me queda el enlace con el nombre &#8216;OpenOffice.org Calc&#8217;

[![Arrastrar enlace](http://localhost/blog/wp-content/uploads/2007/06/05_win-run_shortcuts_arrastrar_enlace.jpg)](http://localhost/blog/wp-content/uploads/2007/06/05_win-run_shortcuts_arrastrar_enlace.jpg "Arrastrar enlace")

[![Copiar enlace](http://localhost/blog/wp-content/uploads/2007/06/06_win-run_shortcuts_copiar_enlace.jpg)](http://localhost/blog/wp-content/uploads/2007/06/06_win-run_shortcuts_copiar_enlace.jpg "Copiar enlace")

[![Nuevo enlace](http://localhost/blog/wp-content/uploads/2007/06/07_win-run_shortcuts_nuevo_enlace.jpg)](http://localhost/blog/wp-content/uploads/2007/06/07_win-run_shortcuts_nuevo_enlace.jpg "Nuevo enlace")

**4. Cambiar el nombre del enlace.** A este nuevo enlace le cambiamos ahora el nombre, elegí _&#8216;oocalc&#8217;_. Con esto ya podemos iniciar la hoja de cálculo de OpenOffice desde el diálogo _&#8216;Ejecutar&#8217;_.

[![Cambiar de nombre al enlace](http://localhost/blog/wp-content/uploads/2007/06/08_win-run_shortcuts_cambio-de-nombre-enlace.jpg)](http://localhost/blog/wp-content/uploads/2007/06/08_win-run_shortcuts_cambio-de-nombre-enlace.jpg "Cambiar de nombre al enlace")

**5. Ejecutar la aplicación.** Invocamos el diálogo _&#8216;Ejecutar&#8217;_ con la combinación de teclas **Win+R**, allí escribimos el nombre que pusimos en nuestro recién creado enlace: _&#8216;oocalc&#8217;_ -sin las comillas-, damos _&#8216;Enter&#8217;_ y listo, Open Office Calc abre con una hoja de cálculo lista para trabajar.

[![Ejecutar](http://localhost/blog/wp-content/uploads/2007/06/09_win-run_shortcuts_ejecutar.jpg)](http://localhost/blog/wp-content/uploads/2007/06/09_win-run_shortcuts_ejecutar.jpg "Ejecutar")

[![Iniciando aplicación](http://localhost/blog/wp-content/uploads/2007/06/10_win-run_shortcuts_oocalc_inicado.jpg)](http://localhost/blog/wp-content/uploads/2007/06/10_win-run_shortcuts_oocalc_inicado.jpg "Iniciando aplicación")

Así como podemos iniciar aplicaciones, podemos también abrir carpetas, en este caso creamos un acceso directo a las mismas, lo arrastramos o movemos hasta la carpeta de enlaces y cambiamos el nombre por alguno de mejor recordación o abreviado. En la primera gráfica se ven algunos de mis enlaces a carpetas: _&#8216;docs&#8217;_ para _&#8216;Mis Documentos&#8217;_, _&#8216;desktop&#8217;_ para el _&#8216;Escritorio&#8217;_, _&#8216;downloads&#8217;_ para mis descargas de archivos e incluso tengo una llamada _&#8216;atajos&#8217;_ que es un enlace a la carpeta que contiene los enlaces mismos de que trata este _post_