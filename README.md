# Markdown
Resumen del curso Markdown de Linkedin

## ¿Qué es Markdown?
Markdown es un formato de enmarcación de texto, que permite crear texto con formato. Markdown es utilizado en los archivos llamado ***README.md***, los cuales se encuentran en cualquier proyecto de Software, y son utilizados para dar una pequeña descripción de lo que consiste dicho proyecto.

Es un lenguaje de marcado ligero creado por John Gruber que trata de conseguir la máxima legibilidad y facilidad de publicación tanto en su forma de entrada como de salida, inspirándose en muchas convenciones existentes para marcar mensajes de correo electrónico usando texto plano. Se distribuye bajo licencia BSD y se distribuye como plugin (o al menos está disponible) en diferentes sistemas de gestión de contenidos (CMS). Markdown convierte el texto marcado en documentos XHTML utilizando html2text creado por Aaron Swartz. Markdown fue implementado originariamente en Perl por Gruber, pero desde entonces ha sido traducido a multitud de lenguajes de programación, incluyendo PHP, Python, Ruby, Java y Common Lisp.


# ¿Para qué se usa Markdown?
Algunas de las opciones con las que te será más fácil la vida usando Markdown:
* Redacción de correos electrónicos:  es perfecto para escribir correos electrónicos que necesiten tener un formato especial de forma cómoda y rápida.
* Listas de tareas pendientes: perfecto también para aquellas listas de tareas con texto sin formato. Incluso si se desea utilizar una aplicación especializada, como Cheddar para iOS, este también admite Markdown.
* Notas organizadas: similar a las listas de “to do” anteriores, la mayor parte de las aplicaciones para tomar notas son compatibles con Markdown, siendo fácil su organización sin necesidad de tocar el formato.


## MarkDown Básico
### Cabeceras
* MarkDown nos permite escribir cabeceras de la siguiente manera:
Con el signo ***===*** podemos crear cabeceras de primer nivel (títulos), esto relacionado con HTML, es como crear un H1

~~~
Cabecera 1
==========
~~~

* Con el signo ***---*** podemos crear cabeceras de segundo nivel (subtítulos), esto relacionandolo con HTML, eso como crear un H2

~~~
Cabecera 2
----------
~~~

* Otra forma de crear cabeceras es usando ***#***, dependiendo de la cantidad de numerales que se use las cabeceras seran más pequeñas (de un nivel inferior)
~~~
#Cabecera 1
##Cabecera 2
###Cabecera 3
####Cabecera 4
#####Cabecera 5
~~~
Cabe mencionar que usar ***===*** para títulos y ***---*** para subtítulos es igual a usar ***#*** y ***##***, respectivamente.

**Formato**
El formato básico del texto, es decir negritas y cursiva, se pueden realizar de varias maneras:

+ Negrita
Se lo realiza con dos asteriscos (**) al inicio de la palabra o frase y con dos asteriscos al final (**). También funciona con dos guíones bajos (__)

+ Cursiva 

Se lo realiza con un asterisco (*) al inicio de la palabra o frase y con un asteriscos al final (*). También funciona con un guíon bajo (_)

+ Negrita y Cursiva

Se lo realiza con tres asteriscos (***) al inicio de la palabra o frase y con tres asteriscos al final (***). También funciona con tres guíones bajos (___)

***Se pueden emplear indistintamente tanto el asterisco * como el guión bajo _ siempre y cuando no se mezclen y lo que determina el formato es el número de ellos antes y después del bloque de texto a formatear***

**Citas**

Para crear bloques de cita, se emplea el carácter mayor que > antes del bloque de texto. 

**Listas**

Para crear listas enumeradas se coloca el número y un punto seguido de la palabra o frase

1. Listas enumeradas
2. Listas con viñetas

Listas usando viñetas podemos colocar (+, -, *) seguido igualmente de la palabra o frase

+ Listas enumeradas
+ Listas con viñetas


