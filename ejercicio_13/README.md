Tarea 13: Imágenes en HTML5

Este proyecto contiene una serie de ejercicios prácticos enfocados en el dominio de la inserción, estructuración y optimización de imágenes en HTML5.

Se trabajará con la etiqueta principal `<img>` y sus atributos fundamentales (`src`, `alt`, `width`, `height`, `loading`) , prestando especial atención a la semántica visual mediante las etiquetas `<figure`> y `<figcaption>`.

Además, se exploran técnicas avanzadas de imágenes responsive utilizando las etiquetas 
`<picture`> y `<source`> para adaptar los recursos según el formato soportado por el navegador o las dimensiones de la pantalla.

Estructura del proyecto

- `index.html`: Documento principal que contiene todos los ejemplos organizados por niveles de complejidad.
- `img/`: Directorio que almacena las imágenes locales utilizadas en las prácticas, incluyendo pruebas con distintos formatos de nueva generación y tradicionales (JPG, PNG, AVIF, WEBP).

Enunciados y Ejercicios realizados:

1. Inserción Básica y Semántica Visual

    Implementación de los conceptos fundamentales para mostrar imágenes que forman parte del contenido de la web:
    - Rutas y organización: Ejemplos de imágenes ubicadas en la raíz del proyecto y en el directorio dedicado `img/` utilizando rutas relativas.
    - Atributos clave: Aplicación de atributos obligatorios como `alt` para la accesibilidad, definición de dimensiones (`width` y `height`), y optimización del rendimiento mediante carga perezosa (loading="lazy").
    - Agrupación semántica: Uso de la etiqueta contenedora `<figure`> para envolver una imagen (un gráfico de ventas) junto con su respectiva leyenda descriptiva utilizando `<figcaption>`.

2. Imágenes Responsive y Adaptativas

    Creación de un bloque de ejemplos avanzados utilizando fuentes externas y la etiqueta `<picture>` para ofrecer una experiencia adaptada al usuario:
    - Adaptación por tamaño de pantalla (Anchura): Uso del atributo `srcset` directamente en la etiqueta `<img>` para indicar un conjunto de imágenes y permitir al navegador elegir la más adecuada según el ancho (`w`) del dispositivo, evitando descargas pesadas en pantallas pequeñas.
    - Formatos de nueva generación (Fallbacks): Uso de `<picture>` y `<source>` para intentar cargar formatos modernos, ligeros y optimizados (`.avif`, `.webp`), estableciendo una imagen `.jpeg` tradicional como alternativa de seguridad para navegadores antiguos.
    - Art Direction (Media Queries) y Densidad de Píxeles: Implementación del atributo `media` dentro de `<source>` para forzar el cambio dinámico de la imagen mostrada dependiendo de los puntos de ruptura (breakpoints) del ancho de la pantalla (ej. `width >= 900px`). Además, se combina de forma avanzada con el uso de descriptores de densidad (`1x`, `2x`, `3x`) en el atributo `srcset` para servir versiones de alta resolución (HD y FHD) a dispositivos con pantallas Retina o de alta densidad.
