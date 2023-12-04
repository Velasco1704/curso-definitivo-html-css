# Resumen de Curso Definitivo de HTML y CSS

## Que es el Front-end

<p><strong>Front-end</strong>: Especialidad dedicada al desarrollo en el lado del cliente, abarcando las interacciones presentes en una página web. Aquí entran en juego las animaciones y los estilos que impactan directamente al usuario. Los profesionales del Front-end se valen de tecnologías fundamentales como HTML, CSS y JS, reconocidas como estándares interpretados por los navegadores. Además, aprovechan Frameworks de CSS, proporcionando fragmentos previamente construidos que simplifican la integración en nuestros sitios web, optimizando así los tiempos de desarrollo.

Los Front-end también utilizan Frameworks y librerías de JS que posibilitan la construcción de productos con capacidad de escalabilidad más rápida y una interacción más robusta. Por el lado del CSS se encuentran los Preprocesadores de CSS los cuales proporcionan características extra al CSS. Y por ultimo están compiladores y empaquetadores de JS, como Babel y Webpack, que contribuyen significativamente al proceso de desarrollo.</p>

## Deferencias entre Sitos Web Estáticos y Sitios Web Dinámicos

<p><strong>Sitos Web Estáticos</strong>: La información que contiene permanece constante y estática, sin actualizarse mediante la interacción del usuario. Es adecuada para landing pages (páginas informativas) o blogs, ya que su contenido será siempre uniforme para todos los usuarios.</p>

<p><strong>Sitios Web Dinámicos</strong>: Actualizan su información con respecto a la interacción del usuario. Dependen de una base de datos, de donde extrae e ingresa información. Serán diferentes, dependiendo del usuario que la use.</p>

## Anatomía de un HTML

![HTML](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%2817%29-f08bb2df-26d7-4221-aebc-c84dd0b015e1.jpg "HTML")

## Etiquetas mas usadas de HTML

![Etiquetas de HTML](https://static.platzi.com/media/user_upload/html-13c81740-4f89-4aeb-8e1b-1c5df3188df4.jpg "Etiquetas de HTML")

## Estructura de HTML:head

![head image](https://static.platzi.com/media/user_upload/IMG_2482-8ed7b477-9bdc-44e5-951e-b76fcd8449c1.jpg "Etiquetas de HTML")

![head image](https://static.platzi.com/media/user_upload/IMG_2483-b30a2a81-cc35-4117-9fd3-4808624f97b5.jpg "head")

## Estructura de HTML:body

<p><strong>body</strong> es la etiqueta que identifica la parte visible de nuestro sitio web. Dentro del body, se añadirán las etiquetas para marcar los elementos visuales del sitio web, como logotipo, menús de navegación, contenido principal, entre otrs. Es muy importante usar HTML semántico y no llenar todo de <div> para que nuestro sitio sea mejor interpretado por el navegador y, por lo tanto, más accesible.</p>

### Etiquetas del cuerpo del documento (body):

<ul>
  <li><strong>article:</strong> diferencia partes del contenido que pueden vivir por sí mismas.</li>
  <li><strong>nav:</strong> para hacer menús de navegación.</li>
  <li><strong>aside:</strong> contenido menos relevante, como publicidad, etc.</li>
  <li><strong>section:</strong> sirve para diferenciar las secciones principales del contenido.</li>
  <li><strong>header:</strong> cabecera del documento.</li>
  <li><strong>footer:</strong> pie de página del documento.</li>
  <li><strong>h1 - h6:</strong> títulos de nuestro sitio web.</li>
  <li><strong>table:</strong> tablas de contenidos, similar a la estructura de las hojas de cálculo.</li>
  <li><strong>ul y ol:</strong> listas de items.</li>
  <li><strong>div:</strong> cualquier división para organizar el contenido.</li>
  <li><strong>h1 a h6:</strong> son etiquetas para indicar títulos con un estilo que destaca del resto.</li>
  <li><strong>article:</strong> es la parte de nuestro contenido que puede vivir por sí mismo. Pueden haber tantos artículos como proyectos o eventos tenga nuestro portafolio.</li>
  <li><strong>p:</strong> define el texto de un párrafo.</li>
  <li><strong>small:</strong> aplica una apariencia de texto reducido en tamaño.</li>
  <li><strong>strong:</strong> aplica al texto un formato de negritas.</li>
  <li><strong>a:</strong> corresponde a un ancla o enlace a una URL interna o externa del documento.</li>
  <li><strong>img:</strong> con esta etiqueta podemos enlazar imágenes en el documento.</li>
  <li><strong>figure:</strong> le da un contexto semántico a las imágenes.</li>
</ul>

## Anatomía de una etiqueta de HTML

<p>Una etiqueta HTML puede tener tantos atributos como desees, y cada atributo tiene su propia función. En el siguiente ejemplo, veremos la forma en la que se compone una etiqueta HTML:</p>

![image](https://i.postimg.cc/k4s9SqbT/Anatom-a-de-Etiqueta.png "image")

<ul>
  <li>No todas las etiquetas llevan una etiqueta de cierre. Las que llevan un cierre son aquellas que albergan un contenido que nos dice a dónde nos va a llevar (nombre de la página, nombre del link).</li>
  <li>Lo que va dentro de la etiqueta de apertura es un atributo (nombre del atributo = href y el valor del atributo es la url).</li>
  <li>El contenido + la etiqueta = Elemento</li>
</ul>

## Tipos de imágenes

<p>Las imágenes representan una pieza fundamental al momento de mostrar contenido para web. Aquí conoceremos los principales tipos de imágenes web y sus formatos.</p>

### Lossless (sin pérdida)

<ul>
  <li>Capturan todos los datos del archivo original.</li>
  <li>No se pierde nada del archivo original.</li>
  <li>Puede comprimirse, pero podrá reconstruir su imagen al estado original.</li>
</ul>

### Lossy (con pérdida)

<ul>
  <li>Se aproximan a su imagen original.</li>
  <li>Podría reducir la cantidad de colores en su imagen o analizar la imagen en busca de datos innecesarios.</li>
  <li>Por consiguiente, puede reducir su tamaño, lo que mejora el tiempo de carga de la página, pero pierde su calidad.</li>
  <li>Los archivos tipo lossy son mucho más livianos que los archivos tipo lossless, por lo que son ideales para usar en sitios en donde el tamaño del archivo y la velocidad de descarga son importantes.</li>
</ul>

![image](https://static.platzi.com/media/user_upload/table%20for%20diferent%20images-42fdf349-a492-4ff5-afbd-1f437c804e4a.jpg "image")

### Formatos de imagen para web

<ul>
  <li><strong>GIF (Graphics Interchange Format):</strong> Formato de imagen sin pérdida, no se puede comprimir.</li>
  <li><strong>PNG 8 (Portable Network Graphics):</strong> Formato de imagen sin pérdida, uso de colores de 256, se utiliza para logotipos e iconos para la página.</li>
  <li><strong>PNG 24 (Portable Network Graphics):</strong> Formato de imagen sin pérdida, utilización de colores ilimitados, alta calidad; si intentamos comprimir, no ayudará demasiado por la gran cantidad de colores.</li>
  <li><strong>JPG / JPEG (Photographic Experts Group):</strong> Formato de imagen con pérdida, perdemos calidad a la hora de comprimirlas, pero llegan a ser óptimas para la carga en la página web.</li>
  <li><strong>SVG - Vector (Scalable Vector Graphics):</strong> Formato de imagen muy ligero sin pérdida, con SVG no perdemos calidad, ya que está compuesta por vectores.</li>
  <li><strong>WebP:</strong> Es un formato gráfico en forma de contenedor que sustenta tanto compresión con pérdida como sin ella. Fue desarrollado por Google.</li>
</ul>

# CSS

## Pseudo<strong>clases</strong> y Pseudoelementos

![image](https://static.platzi.com/media/user_upload/Artboard%202%20-%20copia-3a849126-d009-4481-85b7-9ef9162b2c42.jpg "image")

![image](https://static.platzi.com/media/user_upload/Artboard%202%20-%20copia-3a849126-d009-4481-85b7-9ef9162b2c42.jpg "image")

## Anatomía de una regla de CSS

<p>La anatomía de una regla de CSS consta de varias partes:</p>

<ul>
  <li><strong>Selector:</strong> Es el elemento HTML al que se le aplicará el estilo. Puede ser un elemento específico, una clase o un identificador. Por ejemplo, el selector "p" se aplica a todos los elementos de párrafo en el documento HTML.</li>
  <li><strong>Declaración:</strong> Es una sola regla que especifica qué propiedad del elemento se desea estilizar. Por ejemplo, "color: red;" define el color del texto como rojo.</li>
  <li><strong>Propiedad:</strong> Es el nombre del estilo que se desea aplicar al elemento. Por ejemplo, "color" es una propiedad que define el color del texto.</li>
  <li><strong>Valor de la propiedad:</strong> Es el valor específico que se asigna a la propiedad. Por ejemplo, "red" es un valor de la propiedad "color" que define el color del texto como rojo.</li>
</ul>

![image](https://static.platzi.com/media/user_upload/csspartes-bab7ca8d-dfa6-46c7-9b10-30ee879e5ef4-5ed97a22-4702-4cbf-a0a5-55bcacdf1583.jpg "image")

## Herencia

<p>Herencia y sus valores: <strong>Inherit</strong>. Este es un valor por medio de una keyword que especifica que, a la propiedad que se la apliquemos debe de heredar los valores de su elemento padre. Podemos decir que la palabra <strong>Inherit</strong> significa “Usa el valor de mi padre”, si el elemento padre no tiene definido dicho valor el navegador seguirá el DOM hasta que encuentre un elemento superior que lo contenga, y en ultima instancia de no tenerlo ningún elemento superior se aplicara el valor por defecto.</p>

<ul>
  <li><strong>Initial:</strong> Este valor pertenece a la especificación CSS3 y, al aplicarlo a una propiedad, estamos dando el valor inicial y predefinido por el navegador en cuestión.</li>
  <li><strong>Upset:</strong> Este valor unset es una combinación entre inherit e initial. Al utilizar este valor en una propiedad, esta tratará de heredar el valor de su elemento padre si este está disponible. De no ser así, este valor colocará el valor de la propiedad en su valor inicial, como si usáramos inherit e initial juntos.</li>
</ul>

![image](https://www.w3.org/wiki/images/2/2f/Inheritance.png "image")

## Especificidad en selectores

<p>La especificidad se determina según el tipo de selector, como los selectores de clase, ID y elementos, así como el orden en que se aplican las reglas.</p>

<ul>
  <li>Los <strong>!important</strong> estarán por encima de los demás estilos. Sin embargo, son mala práctica y no se deberían usar.</li>
  <li>Los estilos embebidos en el HTML, es decir inline styles, están por encima de las <strong>clases</strong> y IDs. Sin embargo, también se deberían evitar.</li>
  <li>Los <strong>IDs</strong> están por encima de las <strong>clases</strong>. Los IDs son específicos; si se usa uno en un archivo HTML, ya no se podrá repetir más en ese mismo archivo. Mientras que las <strong>clases</strong> sí se pueden repetir en cualquier elemento.</li>
  <li>Un <strong>estilo de etiqueta</strong> es el último valor que el navegador tiene en cuenta antes de tomar los estilos por defecto de esa etiqueta. Los <strong>estilo de etiqueta</strong> son los que menos peso tienen.</li>
</ul>

![image](https://static.platzi.com/media/user_upload/8.Especificidad%20en%20selectores-1b4be9d0-ed66-4e86-b72e-071f0ba80091.jpg "image")

## Combinadores: Adjacent Siblings

<p>Los combinadores en CSS son operadores que se utilizan para establecer relaciones entre selectores y seleccionar elementos específicos en función de su estructura y posición en el documento HTML.</p>

<ul>
  <li>El combinador de hermano general se representa con el símbolo de tilde (~) y se coloca entre dos selectores. El selector a la izquierda selecciona el elemento anterior y el selector a la derecha selecciona los elementos hermanos generales que siguen al elemento anterior.</li>
  <li>El combinador de hermanos adyacentes se representa con el símbolo de signo más (+) y se coloca entre dos selectores. El selector a la izquierda selecciona el elemento anterior y el selector a la derecha selecciona el elemento adyacente que sigue al elemento anterior.</li>
  <li>El combinador "Hijo" se representa con el símbolo de mayor que (>). Se coloca entre dos selectores, donde el selector a la izquierda selecciona el elemento padre y el selector a la derecha selecciona los elementos hijos directos del elemento padre. Los estilos especificados se aplicarán solo a los elementos hijos directos.</li>
  <li> El combinador "Descendiente" se representa con un espacio en blanco. Se utiliza para seleccionar elementos que son descendientes de otro elemento, sin importar si son hijos directos o no. Los estilos especificados se aplicarán a todos los elementos descendientes que cumplan con la selección.</li>
</ul>

![image](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%2864%29-d9e9849d-5ced-4933-b653-eb9e6113f124.jpg "image")

## Medidas

<p><strong>Medida absoluta</strong>: el valor de este no cambia y siempre sera el mismo asi la pagina cambie su tamaño, las medidas absolutas son: . mm = milímetros cm = centímetros in = pulgada pc = picas px = pixel .</p>

<p><strong>Medidas relativas</strong>: estas medidas heredan el tamaño o se basan en algún tamaño que se allá seleccionado y el valor ira cambiando según si la pagina cambia de tamaño, las medidas relativas son : . % em rem</p>

## Web fonts

<p>Las <strong>Web Fonts</strong> son grupos familiares de fuentes, los navegadores web poseen fuentes predeterminadas y dependiendo del mismo cada uno de ellos posee estilos diferentes.</p>

### Algunas Generic Families

<ul>
  <li><strong>Serif</strong>: Son un tipo de fuente de estilo formal o clásico como Times New Roman.</li>
  <li><strong>Sans-serif</strong>: No tienen acabado en las puntas, como: Verdana.</li>
  <li><strong>Cursive</strong>: Son las que tienen estilo cursivo.</li>
  <li><strong>Monospace</strong>: Son tipos de fuentes con espaciado entre las letras, como: Roboto mono.</li>
</ul>

## Responsive design

<p>El <strong>responsive design</strong> es una técnica de diseño web que busca que los sitios se adapten y respondan de manera óptima a diferentes dispositivos y tamaños de pantalla, brindando una experiencia de usuario consistente y agradable.</p>

## Estrategias de responsive

### Mostly fluid

![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT4qvW9ZnwL5B-CpUCgFWFbKM3HW0EhmQYH4DXGTRgiih0soYxYNHAbySrTnco-w-f1lXk&usqp=CAU "image")

### Layout shifter

![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSZJ4SvSnqBDCWrhW5GN5MwzW9Bt3Ht6ROlS_oiLJZlCg&s "image")

### Column Drop

![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSFNLh-N2DqdT3iFo2_f5m3oolbhWt2JhLs_fCL2GB4RDrQhk1XPpDHSvvepSuW6QrEkvw&usqp=CAU "image")

## Que es la Accesibilidad

<p>La accesibilidad en HTML se refiere a la práctica de diseñar y desarrollar sitios web de manera que sean accesibles y utilizables por todas las personas, incluyendo aquellas con discapacidades o limitaciones. La accesibilidad busca garantizar que todas las personas, independientemente de sus habilidades o circunstancias, puedan acceder y utilizar la información y funcionalidades de un sitio web.</p>

## Malas practicas de CSS Y HTML

<ul>
  <li>Utilizar tanto id en CSS</li>
  <li>Utilizar el !important</li>
  <li>Utilizar la etiqueta dentro del archivo HTML</li>
  <li>Utilizar el atributo style dentro de las etiquetas HTML</li>
  <li>Utilizar div para contener todo ignorando los header, nav, section, article, etc.</li>
  <li>No utilizar la etiqueta form para hacer formularios</li>
  <li>Utilizar las etiquetas select y option para hacer selectores o menús desplegables.</li>
  <li>No nombrar el primer archivo HTML del proyecto como index.html</li>
  <li>No tener archivos .css para cada pantalla de un proyecto.</li>
  <li>Tener todo el CSS junto en un solo archivo.</li>
  <li>No ponerle el atributo alt a una imagen</li>
  <li>Poner imágenes dentro de div en vez de figure</li>
  <li>Utilizar textos solo en mayúscula en HTML, en vez de utilizar el atributo de CSS, text-transform, con el valor uppercase. Ya que al hacer esto pareciera que estuvieras gritando.</li>
  <li>Poner videos que se reproduzcan solos.</li>
  <li>No optimizar las imágenes.</li>
  <li>No tener cuidado de cuál es el formato ideal para las imágenes y su respectivo peso.</li>
  <li>No tener cuidado con la respectiva semántica de HTML, y con la sintaxis adecuada para CSS.</li>
  <li>No cerrar las etiquetas que se cierran en sí mismas como br</li>
  <li>No comentar partes esenciales de tu código.</li>
  <li>No poner el atributo autocomplete=”valor” en los campos de tu formulario para hacerle la vida más fácil al usuario.</li>
  <li>No usar el atributo required en los campos obligatorios de tu formulario como una primera capa de seguridad.</li>
</ul>
