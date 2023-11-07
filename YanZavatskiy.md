**Cuaderno de Yan Zavatskiy**

## 1.- ¿Qué es un Lenguaje de marcas?

Un Lenguaje de Marcas es un modo de codificar un documento donde, junto con el texto, se incorporan etiquetas con información adicional relativa a la estructura del texto o su formato de presentación. 
Los Lenguajes de Marcas permiten representar la estructura de un documento, contenido semantico o cualquier tipo de informacion que se quiera utilizar.


## 2.- Evolución de los Lenguajes de marcas

Los lenguajes de marcas empezaron como lenguajes compuestos por codigos de formato que utilizaban los procesadores de texto para el tarea de pasar documentos a la impresora para su posterior impresion, como los lenguajes de programacion, inicialmente estos estaban ligados a las caracteristicas de una maquina, programa o procesadores concrectos, y tampoco habia nada que permitiera abstraerse de las caracteristicas obligadas por el sistema o aplicacion, por lo tanto era dificil expresar de forma independiente la estructura y logica interna del documento. 

Posteriormente, se añadieron como medio de presentación a la pantalla. Los códigos de estilo de visualización anteriores ya no aparecen, y se emplean otros medios para marcados, distintos de la inclusión a mano de cadenas formateadoras, ahora ese proceso se automatiza y basta pulsar una combinación de teclas, o pulsar un botón, para lograr los resultados requeridos. Aunque esto es sólo una abstracción, para su uso interno las aplicaciones siguen utilizando marcas para delimitar aquellas partes del texto que tienen un formato especial.

Este marcado estaba exclusivamente orientado a la presentación de la información, aunque pronto se percataron de las posibilidades del marcado y le dieron nuevos usos que resolvían una gran variedad de necesidades, apareció el formato generalizado.

Dos ejemplos de lenguajes de marcado estanderizados : 

**GML :**

Lenguaje de marcas generalizado de IBM, es un conjunto de macros que implementan etiquetas de marcado para el procesador de texto de IBM, SCRIPT. 

GML fue desarrollado entre 1969 y 1970 por Charles Goldfarb, Edward Mosher y Raymond Lorie.

Al usar GML, un documento recibe un formato que define qué tipo de texto es (en términos de párrafos, cabeceras, listas, tablas, etc.). 
El documento puede ser automáticamente formateado por varios dispositivos simplemente especificando un perfil para el dispositivo. Por ejemplo, es posible dar formato a un documento para impresora láser o de matriz de puntos, simplemente especificando un perfil para el dispositivo en cuestión sin modificar el documento en sí.

**SGML :**
	
¿Qué es el SGML?

El SGML es un modelo internacional que permite estandarizar y definir formalmente un documento electrónico, independientemente del software, la aplicación o el sistema que se utilice.

Esto quiere decir que el SGML permite, como metalenguaje que es, definir diferentes estructuras mediante marcas descriptivas para describir los contenidos de los documentos. Hay que especificar que el SGML no implica una descripción de la apariencia física del documento, ya que esta acción la llevan a cabo las diferentes plataformas que interpretan el documento, como por ejemplo el navegador. 

El SGML define e identifica las diferentes estructuras de contenido del documento según la finalidad o el sentido que tienen en él.




## 3.- Características de los lenguajes de marcas

* Uso del texto plano: Al ser un texto plano cualquier persona puede leer y editar esa información. Los caracteres pueden codificarse en distintas codificaciones.
* Son lenguajes compactos: Las etiquetas de marcas se mezclan con el contenido del mismo.
* Independencia del dispositivo: Al ser independiente del dispositivo nos permite mostrar el contenido en cualquiera de ellos.
* Facilidad de procesamiento: Permite el desarrollo de lenguajes especializadas según el tipo de documento que necesitemos procesar.
* Flexibilidad: Posibilidad de combinación con otros lenguajes.

 ### Algunos ejemplos y caracteristicas especificas de lenguajes :
 
**_XML_**

![Imagen de lenguaje XML ](https://blog.hubspot.es/hs-fs/hubfs/xml%20file%20example%20storing%20names%20and%20test%20scores%20of%20students-1.png?width=650&name=xml%20file%20example%20storing%20names%20and%20test%20scores%20of%20students-1.png)

* La información se dispone de forma jerárquica.
* Los datos incorporan etiquetas y marcajes que definen a los datos, es decir, explican qué es y qué significa cada conjunto de datos.
* Las bases de datos que utilizan XML pueden albergar diferentes tipos de datos.
* Los datos son presentados en orden. Es decir, en un documento XML el orden en el que aparecen los elementos es el orden de los datos, lo cual no sucede en las bases de datos relacionales basadas en registros y columnas.

**_HTML_**

![Imagen de lenguaje HTML ](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a6/HTML_source_code_example.svg/300px-HTML_source_code_example.svg.png)

* Es fácil de usar y entender.
* Es utilizado para crear páginas web.
* Permite describir hipertextos.
* Está fundamentado por una serie de breves códigos escritos en un registro de texto por el desarrollador del sitio web.
* Es multiplataforma, por lo que se puede acceder desde cualquier lugar y dispositivo.
* No es necesario estar en línea para que el lenguaje HTML funcione correctamente, ya que se puede codificar una página web sin conexión alguna, es decir, es posible almacenar todo un sitio web en una computadora y luego transferir los registros a la web.
* Todos los elementos de un documento HTML constan de una etiqueta de inicio, un bloque de texto y una etiqueta de cierre.
* Tiene un despliegue rápido.
* Es reconocido y admitido por cualquier tipo de explorador web.
* Permite archivos pequeños.
* Su lenguaje es estático.
* Las etiquetas son limitadas.


**_JSON_**

![Imagen de lenguaje JSON ](https://www.info-computer.com/modules/dbblog/views/img/post/como-abrir-los-archivos-json.png)

* Consiste en pares "clave - valor"
* Los valores pueden cadenas, números o boleanos, así como otros objetos JSON, con cualquier nivel de anidación
* Es un formato flexible, ligero y fácilmente transferible a través de las redes

**_YAML_**

![Imagen de lenguaje YAML ](https://www.redhat.com/sysadmin/sites/default/files/inline-images/emacs.jpg)

* Los contenidos en YAML se describen utilizando el conjunto de caracteres imprimibles de Unicode, bien en UTF-8 o UTF-16

* La estructura del documento se denota indentando con espacios en blanco; sin embargo no se permite el uso de caracteres de tabulación para sangrar
* Los miembros de las listas se denotan encabezados por un guion con un miembro por cada línea, o bien entre corchetes y separados por coma espacio
* Los vectores asociativos se representan usando los dos puntos seguidos por un espacio. en la forma "clave: valor", bien uno por línea o entre llaves y separados por coma seguida de espacio
* Un valor de un vector asociativo viene precedido por un signo de interrogación, lo que permite que se construyan claves complejas sin ambigüedad
* Los valores sencillos (o escalares) por lo general aparecen sin entrecomillar, pero pueden incluirse entre comillas dobles, o comillas simples
* En las comillas dobles, los caracteres especiales se pueden representar con secuencias de escape similares a las del lenguaje de programación C, que comienzan con una barra invertida
* Se pueden incluir múltiples documentos dentro de un único flujo, separándolos por tres guiones los tres puntos indican el fin de un documento dentro de un flujo
* Los nodos repetidos se pueden denotar con un ampersand y ser referidos posteriormente usando el asterisco
* Los comentarios vienen encabezados por la almohadilla y continúan hasta el final de la línea
* Los nodos pueden etiquetarse con un tipo o etiqueta utilizando el signo de exclamación seguido de una cadena que puede ser expandida en una URL



## 4.- XML: definición y características del metalenguaje

El lenguaje de marcado extensible o XML es un lenguaje o mas bien, meta-lenguaje, que permite definir y almacenar datos de forma que puedan compartirse, ya que admite el intercambio de informacion entre distintos sistemas, tales como sitios web, bases de datos o aplicaciones, tiene una serie de reglas predefinidas que facilitan la transmision de datos como archivos a traves de cualquier red, ya que el destinatario de este archivo utiliza las mismas reglas para poder leer los datos.

XML en su base esta compuesto de los **_siguientes elementos_** :

La primera primera declaracion que se escribe en XML es el prologo, define la versión de XML usada. Hasta ahora sólo hay una, la 1.0 
Además, en la declaración especificamos la codificación del documento, que puede ser, por ejemplo, US-ASCII o UTF-8. 
Tambien se puede incluir una declaración de documento autónomo ( o standalone ), que controla qué componentes de la DTD son necesarios para completar el procesamiento del documento.

Los símbolos de marcado, denominados etiquetas en XML, se utilizan para definir los datos en el documento.
Por ejemplo, para representar los datos de una librería, puede crear etiquetas como < libro >, < título > y < autor >.

Los atributos de XML se utilizan para distinguir entre elementos del mismo nombre. Cuando no se desea crear un nuevo elemento de cada situación. Por lo tanto, el uso de un atributo puede agregar un poco más en detalle a la hora de diferenciar dos o más elementos similares.

![Imagen de lenguaje XML2 ](https://www.abrirllave.com/xml/images/persona-xml-chrome.gif)
