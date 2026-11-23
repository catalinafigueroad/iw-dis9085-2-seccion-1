Bitácora exámen Catalina Figueroa
**URL: 
https://catalinafigueroad.github.io/catalinafigueroa-portafolio/

**Link de figma:
https://www.figma.com/design/SXMRTukRwmBfbdIrLTdNKg/catalina-figueroa-ex%C3%A1men-web?node-id=18-232&t=U2rwDPQBQUhJhBDC-1  

**Descripción
Este proyecto consiste en diseñar y desarrollar una página web que funcione como portafolio personal, donde se presenten mis trabajos y proyectos realizados durante mi formación como estudiante de Diseño. A través de una propuesta visual y digital, se busca mostrar mi estilo, habilidades, intereses y proceso creativo, organizando los proyectos de manera atractiva y fácil de explorar.
**Referentes 
Sitios web de referencia 

https://www.sonjavanduelmen.com/
Rescato el uso de colores vibrantes y la aplicación de desenfoques en las fotografías, incorporando textos superpuestos
 
https://danielbrokstad.com/
Rescato el color azul del fondo y la animación del home, donde las imágenes van cambiando por detrás mientras el título permanece estático. Mi propuesta es aplicar este recurso a la presentación de cada proyecto de mi portafolio, mostrando su título sobre una secuencia de imágenes que se alternan en segundo plano. Al hacer clic en el título, se abre el proyecto en más detalle, donde se presentarán todas las imágenes junto con la descripción del proyecto. 
 
https://patshiu.com/ 
De este referente rescato el uso de tipografía escrita a mano, mi idea es yo escribir todo lo que está en la tipografía caveat en el wireframe de baja fidelidad, para que se sienta más personalizado y cercano

Otros referentes (pinterest y behance)
Imagen (referente1.jpeg)
De este rescato la textura del lápiz en el título y también el recurso de un botón rectangular con un cuadrado superpuesto y desfasado en la esquina.
Imagen (referente2.png)
De este referente rescato el uso de semitono en la imagen que le otorga más textura y dimensión, también las letras irregulares combinadas con una tipografía recta y pesada.
Imagen (referente3.jpeg)
En este referente rescato el color rojo vibrante y la superposición del trazo del lápiz que  interactúa con la imagen. 

Avance para el 16/11
Mejora de la bitácora según correcciones de la clase pasada, por ejemplo ser más especifica con las referencias y que rescataba de ellas, aunque ya en el proceso ma alejé un poco de las referencias originales y del wireframe de baja calidad ya que al ir diseñado fui incorporando cosas nuevas aunque la estructura base sigue siendo parecida, decidí incorporar diseños de puntos ornamentales para darle una sensibilidad que juegue con los elementos más digitales. 
Usé IA para crear la base del html 
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portafolio | Catalina Figueroa</title>
</head>

Avance en el figma, en las páginas de los proyectos, en donde invertí los colores y agregé la infotmcaión de cada proyecto y las imagenes correspondientes, actualizando el UI kit a medida que voy avanzando

Para el seguir con el código html
- Comencé creando la estructura principal de la página y definiendo el idioma, el título y la descripción del portafolio.
- Incorporé las tipografías desde Google Fonts y vinculé la hoja de estilos CSS.
- Organicé el contenido en distintas secciones: inicio, sobre mí, proyectos y contacto.
- Agregué los títulos, textos y botones de navegación para poder desplazarse entre las secciones de la página.
- Incorporé imágenes ornamentales como elementos decorativos para acompañar la identidad visual del portafolio.
- Organicé las tarjetas de proyectos y vinculé cada una con su respectiva página.
- También preparé una estructura adaptable a pantallas de celular, definiendo posiciones y tamaños diferentes para escritorio y mobile.

Le pedí a la IA que me ayudara a organizar la estructura inicial del HTML, separando el contenido en distintas secciones para que fuera más fácil trabajar después el diseño con CSS.

Prompt que usé:
"Necesito crear la estructura HTML de un portafolio personal de diseño. Quiero que tenga una sección de inicio, una presentación sobre mí, una galería de proyectos y una sección de contacto. Ayúdame a organizar el código utilizando etiquetas semánticas y sin incorporar todavía los estilos CSS."

Después de construir la página principal, comencé a hacer páginas independientes para presentar cada proyecto. En este caso, trabajé en la página de Nicho, manteniendo la misma identidad visual del Home para que existiera continuidad entre ambas.
- Incorporé un botón «Volver» para regresar a la sección de proyectos del inicio.
- Organicé el contenido con el nombre del proyecto, su categoría y una breve descripción.
- Agregué una cita y tres conceptos que explican las ideas principales detrás del proyecto.
- Incorporé las imágenes de las portadas, exploraciones gráficas y dobles páginas de la revista.
- Organicé las imágenes mediante posiciones y dimensiones específicas para construir una composición editorial similar a la diagramación original.
- Adapté la distribución para escritorio y celular utilizando nuevamente las variables de posición y tamaño.

Me ayudé con estre prompt:
"Necesito crear una página individual para cada proyecto de mi portafolio. Quiero incluir un botón para volver al inicio, el nombre del proyecto, una descripción y varias imágenes. Necesito que las imágenes tengan posiciones y tamaños personalizados para poder organizar la composición como en mi diseño de Figma. También quiero que se adapte a una versión mobile."

Y para las otras dos paginas de proyectos hice lo mismo, copié el código de la primera y fui modificando los textos, imágenes y posiciones.

Para el css primero definí los colores principales del portafolio mediante CSS Variables, para poder reutilizarlos en las distintas páginas. Establecí una paleta de azul, verde, negro, blanco y rojo, además de incorporar las tres tipografías que había seleccionado desde Google Fonts.

Después trabajé en la diagramación. Como mi diseño estaba construido a partir de una composición libre, similar a un collage, necesitaba que los elementos mantuvieran posiciones específicas. Para conseguirlo utilicé `position: absolute` y CSS Variables que me permitían controlar la ubicación, el ancho, el alto y el tamaño de los textos.

También trabajé en los siguientes aspectos:
- Tipografía: asigné diferentes `font-family` y `font-weight` para títulos, botones y textos.
- Botones y tarjetas: definí sus colores, bordes y tamaños utilizando propiedades como `background`, `color`, `border` y `font-size`. También incorporé cambios visuales al interactuar con ellos.
- Diseño responsive: adapté las composiciones para celular utilizando `@media queries`, creando posiciones y dimensiones diferentes para cada elemento según el tamaño de pantalla.
- Interacciones: incorporé cambios de color y apariencia utilizando pseudo-classes como `:hover`, `:focus-visible` y `:active`, junto con `transition` para suavizar los cambios.
- Animaciones: preparé estilos para la aparición de elementos al desplazarse por la página mediante `@keyframes`, además de efectos de escritura y movimiento de ornamentos.
- Imágenes: diseñé la estructura visual de una ventana para ampliar las imágenes de los proyectos, utilizando propiedades como `position: fixed`, `opacity`, `visibility` y `z-index`.

Ayuda de la IA:
No me acuerdo del prompt que ocupé pero fue para que me creara la base (le dí acceso al figma), luego yo fui modificando los aspectos esenciales, también me ayudó con las animaciónes y vincularlas después con el java script.

Java script lo hice todo con ayuda de la IA, le pedí:
Aparición al hacer scroll: títulos, textos, tarjetas y fotos aparecen suavemente al entrar en pantalla, de forma escalonada.
"Catalina Figueroa" se escribe letra por letra al cargar la página, con un cursor parpadeante.
Texto "revuelto" en los botones: al pasar el mouse por botones y tarjetas, las letras se mezclan se ordenan solas, un efecto "glitch" que convina con la fuente pixelada.
Parallax en los ornamentos: los ornamentos del fondo se mueven un poco más lento que el scroll y dan profundidad (solo en desktop).
Ver fotos en grande: en las páginas de proyecto, al hacer clic en una imagen se abre ampliada sobre fondo azul. Se cierra con clic, con la ✕ o con Esc.
Ornamentos se forman punto por punto.

Aprendizajes:
Aprendí a llevar un diseño desde Figma a una página web funcional, utilizando HTML, CSS y JavaScript en Visual Studio Code. Aprendí a estructurar contenidos con HTML, modificar tamaños, colores, posiciones y espacios con CSS. También aprendí a adaptar los diseños a distintos tamaños de pantalla mediante el diseño responsive.
Uno de mis mayores aprendizajes fue entender que diseñar una página y desarrollarla son procesos diferentes, y que muchas veces es necesario probar, corregir y ajustar el código hasta conseguir el resultado esperado. Esto me ayudó a desenvolverme con mayor autonomía y a resolver problemas durante el desarrollo.
