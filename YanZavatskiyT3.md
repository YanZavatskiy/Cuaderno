**Cuaderno de Yan Zavatskiy**
**TEMA 3**


## HTML y su evolución

HTML, o HyperText Markup Language, es el lenguaje estándar utilizado para crear y diseñar páginas web. Su evolución a lo largo de los años ha sido significativa, adaptándose a las necesidades cambiantes de la web y las tecnologías emergentes, a continuacion, tenemos un resumen de sus versiones desde su inicio : 

  * HTML 1.0: La primera versión básica de HTML lanzada en 1993.
  
  * HTML 2.0: Introdujo elementos adicionales como formularios y tablas en 1995.
  
  * HTML 3.2: Trajo mejoras en diseño y presentación con soporte para CSS en 1997.
  
  * HTML 4.01: Presentó mejoras en la semántica y la estructura del documento en 1999, así como soporte mejorado para formularios y scripts.
  
  * XHTML: Una reformulación de HTML como una aplicación de XML, que mantuvo la estructura de HTML 4.01 pero con una sintaxis más estricta.

* HTML5: La versión más reciente y robusta, lanzada en 2014. Introdujo una amplia gama de nuevas características, como elementos semánticos, reproducción de video y audio nativa, gráficos vectoriales escalables (SVG), soporte para canvas para gráficos dinámicos, API de arrastrar y soltar, soporte para geolocalización, almacenamiento local y mucho más. HTML5 también mejoró la accesibilidad y la capacidad de SEO (Optimizacion de motor de busqueda) de las páginas web. Además, HTML5 marcó un cambio hacia el desarrollo web móvil y responsivo.

   ![Imagen de Evolucion HTML](https://webblog559388436.files.wordpress.com/2018/04/slide_2.jpg?w=437&h=334)

## XHTML diferencias, ventajas y desventajas con respecto a HTML

XHTML es un lenguaje mas estricto, razon por la que se puso en desuso, algunas de las diferencias clave son:

 * **Sintaxis XML:**

 * XHTML es una reformulación de HTML como una aplicación de XML, lo que significa que sigue una sintaxis más estricta y bien formada.

**Compatibilidad con XML:**

 * XHTML es compatible con XML, lo que permite utilizar herramientas XML para procesar documentos XHTML.

**Estructura y etiquetas:**

XHTML tiene una estructura más estricta y define un conjunto de etiquetas más preciso que HTML.

**Ventajas de ello :**

  * **Interoperabilidad:**
    
  Al seguir las reglas de XML, los documentos XHTML son más interoperables entre diferentes plataformas y dispositivos.
    
  * **Mantenibilidad:**
    
  La sintaxis más estricta de XHTML facilita la detección y corrección de errores, lo que resulta en una mejor mantenibilidad del código.
  
  * **Compatibilidad futura:**
    
   XHTML es compatible con las tecnologías web emergentes y puede ser elogiado por los estándares web en constante evolución.

**Desventajas:**

* **Compatibilidad con navegadores antiguos:**
  
  Algunos navegadores antiguos pueden tener problemas para interpretar documentos XHTML correctamente, lo que puede resultar en problemas de visualización.
  
* **Curva de aprendizaje:**
  
  La sintaxis más estricta de XHTML puede requerir un tiempo de aprendizaje adicional para los desarrolladores acostumbrados a HTML.

* **Compatibilidad con herramientas de desarrollo:**
  
  Algunas herramientas de desarrollo pueden tener problemas con la sintaxis XML de XHTML, lo que puede dificultar el desarrollo y la depuración de aplicaciones web.
  En resumen, XHTML ofrece una sintaxis más estricta y bien formada en comparación con HTML, lo que puede mejorar la interoperabilidad y la mantenibilidad del código, pero puede presentar desafíos de      compatibilidad con navegadores antiguos y herramientas de desarrollo.






## Estructura de un documento HTML

**Cabecera HTML:**
  * **Title:** Define el título del documento que se muestra en la pestaña del navegador.
  * **Meta:** Proporciona metadatos sobre el documento, como el conjunto de caracteres utilizado y la descripción del contenido.
  * **Style:** Contiene estilos CSS que se aplicarán al documento.
  * **Link:** Enlaza el documento con hojas de estilo externas.
  * **Script:** Define scripts JavaScript que se ejecutarán en el documento.

**Cuerpo HTML**

**Elementos de Bloque**
  
  * **Encabezados h1 a h6:** 
   Proporcionan títulos y subtítulos jerárquicos en una página web, donde h1 es el más importante y h6 el menos importante.
  
  * **Párrafos p:** 
   Define un párrafo de texto en una página web.
  
  
  * **Listas no ordenadas ul y ordenadas ol:** 
   ul crea una lista desordenada, mientras que ol crea una lista ordenada.
  
  * **Elementos de lista li:**
   Define un elemento de lista dentro de una lista ul o ol.
 
  * **Divisiones div:**
   Se utiliza para dividir el contenido de una página web en secciones o grupos lógicos.
  
  * **Secciones section:**
   Representa una sección temática de contenido, como capítulos, encabezados, pies de página o cualquier otra sección de una página web.
  
  * **Artículos article:**
   Define un contenido independiente que puede estar relacionado con el contenido principal de la página web.
  
  * **Cabeceras de página header:**
   Define la cabecera o encabezado de una página web, que generalmente contiene logotipos, títulos y elementos de navegación.
  
  * **Pie de página footer:**
   Define el pie de página de una página web, que suele contener información de copyright, enlaces legales y datos de contacto.
  
  * **Menús de navegación nav:**
   Define una sección de navegación de una página web, que generalmente contiene enlaces a otras páginas o secciones del sitio.
  
  * **Elementos de formulario form:**
   Define un formulario HTML que permite a los usuarios enviar datos a un servidor web.
  
  * **Tablas table:**
   Define una tabla en una página web para organizar datos en filas y columnas.
  
  * **Bloques de cita blockquote:**
   Define una cita larga en una página web, que generalmente se muestra con un sangrado del margen izquierdo.
  
  * **Elementos de encabezado header, footer, aside, nav:**
   Define partes específicas de una página web como la cabecera, el pie de página, la barra lateral o el menú de navegación.
  
  * **Elementos de sección section, article:**
   Define secciones específicas del contenido de una página web, que pueden tener su propio encabezado, pie de página y estructura interna.
  
  * **Elemento multimedia img:**
   img muestra imágenes en una página web.
  
  * **Otros elementos estructurales y semánticos:**
   Incluyen elementos como aside, figure, figcaption, main, details, summary, entre otros, que proporcionan una estructura y significado semántico al contenido de una página web.
  
  **Elementos de Línea**
    

   **Listas:**
   
   * **unordered list (Unordered List):** Se utiliza para crear listas de elementos que no tienen un orden específico, como una lista de ítems de navegación o de elementos destacados.
   * **ordered list (Ordered List):** Se utiliza para crear listas de elementos que tienen un orden específico, como una lista de pasos en un proceso o una lista numerada de instrucciones.
   * **list item (List Item):** Define un ítem de lista dentro de una lista desordenada o ordenada.
   
   **Tablas:**
   
   * **table (Table):** Se utiliza para organizar datos en filas y columnas, como una hoja de cálculo. Es útil para mostrar información tabular de manera estructurada.
   * **table row (Table Row):** Define una fila en una tabla, donde se colocan los datos.
   * **table header (Table Header):** Define un encabezado de columna o fila en una tabla, indicando el significado o la categoría de los datos en esa columna o fila.
   * **table data (Table Data):** Define un dato en una celda de tabla, proporcionando el contenido real que se mostrará en la tabla.
     
   **Formularios:**
     
   * **form (Form):** Se utiliza para recopilar datos del usuario. Puede contener diversos elementos de entrada como campos de texto, botones de opción, casillas de verificación, etc.
   * **input (Input):** Define un campo de entrada dentro de un formulario, como un campo de texto, una casilla de verificación o un botón de opción.
   * **select (Select):** Se utiliza para crear menús desplegables, donde el usuario puede seleccionar una opción de una lista.
   * **textarea (Textarea):** Se utiliza para crear áreas de texto multilínea donde el usuario puede ingresar texto extenso, como comentarios o descripciones.
   * **button (Button):** Define un botón dentro de un formulario que puede ser utilizado para enviar el formulario o realizar alguna acción específica.
   * **label (Label):** Se utiliza para asociar texto descriptivo con un elemento de formulario, lo que mejora la accesibilidad y la usabilidad del formulario al proporcionar etiquetas claras para los campos de entrada.
     
 **Elementos Multimedia para HTML5**
 
   Algunos elementos nuevos han sido introducidos cuando salio HTML5, que nos permiten las siguientes etiquetas:
   
   * **audio (Audio):** Permite incrustar archivos de audio en una página web para que los usuarios puedan reproducirlos.
   * **video (Video):** Permite incrustar archivos de video en una página web para que los usuarios puedan reproducirlos.
   * **source (Source):** Define múltiples fuentes de medios, como audio o video, para que el navegador pueda elegir la más adecuada según el formato y la compatibilidad del dispositivo.
   * **track (Track):** Se utiliza para especificar pistas de texto o subtítulos que se pueden incrustar en archivos multimedia de audio o video.



## Herramientas de edición y desarrollo web.

Las Herramientas de edición y desarrollo web es software y plataformas informaticas utilizadas por desarrolladores y diseñadores para crear, editar, depurar y administrar sitios web y aplicaciones web.
Algunos ejemplos son :

 * **Editores de texto avanzados:** Visual Studio Code, Sublime Text, Atom.
 * **Entornos de desarrollo integrado (IDE):** WebStorm, PhpStorm, Eclipse.
 * **Frameworks y bibliotecas de JavaScript:** React.js, Angular, Vue.js.
 * **Sistemas de gestión de contenido (CMS):** WordPress, Drupal, Joomla.
 * **Herramientas de control de versiones:** Git, GitHub, GitLab.
 * **Herramientas de diseño web:** Adobe XD, Figma, Sketch.
 * **Herramientas de pruebas y depuración:** Chrome DevTools, Firefox Developer Tools, Selenium.

