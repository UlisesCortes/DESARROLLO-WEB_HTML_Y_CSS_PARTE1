# Modulo 5 : Cómo se construlle una pagina web bien estructurada

## 1. Presentación 
Crear tablas para datos tabulados te será de gran ayuda para acumular datos y llevar a cabo un mejor análisis de estos. Añadir imágenes puede serte de gran ayuda ya que hará tu página web más atractiva al usuario que la visite.

Conceptos clave:
- Existen servicios de hosting, gratis y de pago.

## 2. HTML: juego de caracteres
Para el español. UTF-8 Sin BOM y ISO-8859-1 (Latin 1) puede ser la solución a todos los problemas que se presenten a la hora de utilizar un juego de caracteres. ISO-8859-15 o Latin 9 te puede servir para escribir el carácter "€".
Conceptos clave: 
- UTF-8 sin BOM
- Latin1 para europa occidental
- ``<meta: http-equiv="Content-Type" content="text/html; chartest=utf-8"> /``
- ``<meta charset="utf-8" />``

## 3. HTML: el juego de caracteres y los editores de texto
BOM o Byte Order Mark define el carácter unicode que se utiliza para indicar el orden de los bytes de un fichero de texto al principio del mismo. Uno de los consejos más importantes es utilizar UTF-8 sin BOM ya que te ayudará a mezclar textos en cualquier idioma.

Conceptos clave:
- BOM significa Byte Order Mark
- UTF-8 sin BOM te ayudará a mezclar textos en cualquier idioma.

## 4. HTML: tablas
Una tabla html es una forma gráfica de representar información de manera esquematizada, ordenada y compacta. Las tablas HTML se organizan en filas y celdas. La etiqueta table indica el inicio y el cierre de la tabla. El resto de etiquetas estarán recogidas entre . La etiqueta representa una nueva fila en la tabla.

![image](https://user-images.githubusercontent.com/86896526/129458230-cff14269-5cce-42bb-acdf-eb9bc56b364d.png)

Conceptos clave:
- usar tablas solo para tablsa, no para maquetar la pagina.

## 5. HTML: imágenes
Las imágenes son el elemento principal que confiere a la web su carácter de hipermedia. La etiqueta para insertar una imagen, en HTML, es < img \>. Esta etiqueta tiene dos atributos obligatorios, src y alt. El atributo src indica la ruta en la que se encuentra la imagen mientras que el atributo alt es el texto alternativo que se debe visualizar cuando la imagen aún no se ha cargado o no se puede cargar por diversas razones. Además < img \> tiene varios atributos opcionales, entre ellos ismap y usemap para definir mapas de imagen. Los mapas de imagen o imágenes sensibles son imágenes que contienen zonas sensibles, que son enlaces a otras páginas web. Se pueden procesar en el lado del cliente (usemap) y en el lado del servidor (ismap).

Conceptos clave:
- Hipermedia
- <img/> <img src="img/logo.gift" alt="Logo de la empresa"/>
- * src: ruta
- * alt: textos si es qeu no llega a acargar la imagen
  Atributos opcionales:
* width y height: ancho y largo
* longdesc.
* ismap y usermap: par redirrigir del lado del cliente y lado servidor
- Formatos graficos:
- jpeg
- gif
- png
- 

## 6. HTML: validación del código
HTML es un lenguaje y por lo tanto tiene su vocabulario y su gramática. Para estar seguros de que nuestro código HTML es correcto y no contiene errores hay que validar el código fuente. Existen diferentes versiones de HTML y en la actualidad conviven HTML 4.01, XHTML 1.0 y HTML5. Lo primero que hay que hacer al empezar a escribir una web es decidir que versión de HTML vas a utilizar. Esta versión se indica con la instrucción < !DOCTYPE > al principio del código. La validación del código fuente se realiza a través de una herramienta. Esta herramienta puede ser gratuita o de pago. Una vez que pasamos el validador podemos ver los errores que tiene nuestra web. Es importante ir resolviendo los errores en el orden en el que aparecen, es decir, del primero al último, ya que a veces al resolver los primeros desaparecen los demás.

Conceptos clave:
- <!Doctype>
- Validar Pagina html
- Existen Diferentes versiones de HTML
- se utiliza para indicar la versión de HTML que se está utilizando

## 7 HTML5: introducción
El elemento mark (<mark>) representa a un trozo de texto remarcado o resaltado al cual los autores pueden referirse desde otro documento, con el fin de analizarlo o explicarlo. Por su parte, el elemento de HTML Header (<header>) representa un grupo de ayudas introductorias o de navegación. Puede contener algunos elementos de encabezado, pero también otros elementos como un logo, una sección que aglutine secciones de encabezados, una formulario de búsqueda, etc.
  
Conceptos clave:
- 

## 8. HTML5: ¿Qué es HTML5?
Con el uso de Caché los recursos deseados se almacenan de forma local, lo que produce una mejora del rendimiento. Se descargan los contenidos necesarios y se trabaja cómodamente en local.
Conceptos clave:
-

## 9. HTML5: de HTML4 a HTML5
La etiqueta < aside > se utiliza para facilitar información adicional a la etiqueta principal, que la completa. Ejemplos de ella son noticias, anuncios etc. Etiquetas como < figure > no se utilizan únicamente para imágenes, también son usadas para fragmentos de código o realizar citas. Utiliza < figcaption > para definir el título de una imagen.

  Conceptos clave:
  Etiquetas
- article
- figure
- figcaption
- main

## 10. HTML5: Nuevas funcionalidades en formularios (parte 1)
La gestión los elementos que componen los formularios de forma nativa permite prescindir de Javascript para realizar validaciones de formulario por parte del cliente. Es compatible entre distintos navegadores. Ahorra tiempo y ancho de banda porque evita que se envíe si no es válido e informa al usuario de que los valores introducidos no cumplen con los requisitos definidos.
  
Conceptos clave:
INPUT  
- url.
- tel.
- email.
- number.
- color.
- search.
- range.
- datetime.
- datetime-local.
- date.
- month.
- week.
- time.

## 11. HTML5: Nuevas funcionalidades en formularios (parte 2)
Modernizr es una microlibrería de Javascript que permite conocer la compatibilidad del navegador del usuario con la tecnología HTML y CSS3. Una vez detectada toma medidas utilizando el Polyfill correspondiente (librería de Javascript) y modifica lo que sea necesario. El utilizar en el desarrollo controles avanzados nativos facilita la labor del desarrollador que no se tiene que preocupar por la compatibilidad de los navegadores, además de suponer un ahorro de tiempo y ancho de banda ya que, por un lado permite que no se envíe el formulario sino es válido, e informa al usuario de que alguno de los valores introducidos no cumple con los requisitos definidos.
  
Conceptos clave:
-autocomplete.
- autofocus.
- min.
- max.
- step.
- pattern.
- placeholder.
- required.
* microlibrerías de javascript detectan las incopatibilidades
* Polyfills son librerias Javascript que adaptan HTML5 y CSS3
  Utilizar controles avanzados nativos en el desarrollo.

## 12. HTML5: Ejemplo de formulario
Muy buena pagina de ejemplo en el video
Cuando la etiqueta label recibe el foco automáticamente se lo cede al control asociado. Dentro de los dos tipos de asociaciones de etiquetas, con los controles de formulario debemos considerar, por temas de adaptabilidad, aquella que maneje correctamente las tecnologías asistidas. La asociación directa no es uno de los dos tipos de asociación de etiquetas que existen.
Conceptos clave:
-

## 13. HTML5: ¿Por qué es importante escribir código correcto? (1/3)
Efectivamente, tal y como indica el estándar, debe utilizarse una única etiqueta HTML. Siempre es aconsejable que, como desarrollador, verificar el código y para ello, en W3C, dispone de un validador. Es muy importante atender a las características específicas de las etiquetas para evitar errores. Aunque no es muy probable, a veces, los navegadores fallan, pero se debe comprobar que no atiende a problemas de desarrollo. Es recomendabñe realizar siempre un testeo de calidad en al menos 3 o 4 navegadores para poder detectar incompatibilidades y poder subsanarlas a tiempo.
  
Conceptos clave:
- Fallos de los navegadores.
- Problemas de compatibilidad entre los navegadores.
- Soporte de HTML por los navegadores.
- Errores en el código HTML.

## 14. HTML5: ¿Por qué es importante escribir código correcto? (2/3)

Conceptos clave:
- Etiqueta <b> sin cerrar.
- Etiqueta <span> sin cerrar.
- Comillas del valor de un atributo sin cerrar (2 versiones).
- Valor del atributo size de la etiqueta "input" incorrecto.

## 15. HTML5: ¿Por qué es importante escribir código correcto? (3/3)
El DOM (Document Object Model) es una recomendación del W3C. El DOM es una interfaz de programación de aplicaciones para documentos válidos HTML y bien construidos XML. Define la estructura lógica de los documentos y el modo en que se accede y manipula. Para entender por qué los navegadores se comportan de forma diferente hay que comparar el DOM que construye cada navegador a partir del código HTML de la página.
  
Conceptos clave:
-

## 16. [A+] HTML: ¿migrar a un nuevo juego de caracteres?
Para escribir un texto y que se entienda correctamente se debe utilizar el juego de caracteres adecuado. Las migraciones se realizan cuando la página web da problemas o en el momento de conectarse a otro sistema con otra codificación, pero si no da problemas, no es aconsejable realizar una migración. Migrar un sitio web de una codificación a otra es más sencillo en Linux y macOS X ya que se realiza por línea de comandos. El comando file permite conocer el tipo y la codificación de un fichero y el comando iconv convierte la codificación de un fichero de una codificación a otra.
Conceptos clave:
-

## 17. [A+] XML: HTML y XHTML

XHTML es el lenguaje de marcado pensado para sustituir a HTML como estándar para las páginas web. En su versión 1.0 XHTML es solamente la versión de XML de HTML por lo que tiene, básicamente, las mismas etiquetas y funcionalidades, pero cumple las especificaciones más estrictas de XML. XHTML es más estricto que HTML por lo que tienen varias diferencias. Una de ellas es que en XHTML los elementos vacíos siempre llevan etiqueta de cierre y en HTML no es necesario. Otra de ellas está relacionada con el valor de los atributos: en XHTML siempre llevan comillas, cuando en HTML no es imprescindible.
  
Conceptos clave:
* En XHTML los elementos vacios sempre llevan etiqueta de cierre.
* En XHTML los valores de los atributos tienen que llevar siempre comillas.
  
      
# Extras
  
El juego de caracteres es una de las cosas más simples del mundo web pero de las que más problemas ocasiona. Es importante ser consistente con el formato de los ficheros que compongan tu página web.
  
Hace unos años las páginas web no tenían imágenes y solo se componían de texto. La ausencia de imágenes puede causar que el sitio web sea totalmente inútil. Un mapa de imagen es una imagen que contiene zonas activas que son enlaces a otras páginas. El mapa de imagen se puede procesar desde el lado del cliente o desde el lado del servidor.
  
HTML es el lenguaje con el que se crean las páginas web desde que Tim Berners-Lee creara la primera página web a finales de los noventa. Hasta hace unos años, los estándares de desarrollo web se diseñaban a partir de HTML4, pero más adelante se desarrolló el HTML5. Este nuevo estándar no es completamente diferente que el modelo anterior, sino que agrega nuevas etiquetas, otras etiquetas han desaparecido porque han quedado obsoletas y se han añadido atributos a las etiquetas que se han mantenido.
    
Una de las características más importantes que nos trae el nuevo estándar HTML5 son los nuevos elementos disponibles para el manejo de formularios ya que nos permite gestionarlos de manera nativa pudiendo así prescindir de JavaScript. Pero, además, poder prescindir de JavaScript nos proporciona otros beneficios como, por ejemplo, lograr un comportamiento más intuitivo de los formularios en beneficio de los usuarios y también reducir la complejidad de desarrollar un formulario.
