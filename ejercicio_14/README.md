Tarea 14: Etiquetas multimedia en HTML5

Este proyecto contiene una serie de ejercicios prácticos enfocados en el dominio de la inserción y configuración de contenido multimedia e incrustado en HTML5.

Se trabajará principalmente con las etiquetas `<iframe>`, `<video>` y `<audio>`, así como con sus atributos fundamentales (`src`, `width`, `height`, `controls`, `autoplay`), prestando especial atención a la compatibilidad de formatos y las políticas de reproducción de los navegadores.

Además, se exploran técnicas de anidamiento de contextos de navegación y el uso de múltiples fuentes de respaldo mediante la etiqueta `<source>`.

Estructura del proyecto

- `index.html`: Documento principal que funciona como menú de navegación, conteniendo los enlaces a todos los ejemplos organizados por tipo de etiqueta.
- `assets/`: Directorio principal de recursos estáticos, subdividido en `imagenes/`, `audios/` y `videos/`, que almacena los archivos locales utilizados en las prácticas con distintos formatos (MP4, WebM, MP3, AAC, FLAC).
- `Archivos HTML secundarios`: Documentos específicos e individuales para cada ejercicio práctico (`iframe_externo.html`, `etiqueta_video.html`, `formulario_registro.html`, etc.).

Enunciados y Ejercicios realizados:

1. Inserción de Contenido con Iframe

    Implementación de contextos de navegación anidados para mostrar recursos externos e internos en la página:
    - **Contenido básico**: Ejemplos de incrustación de páginas web externas y documentos HTML internos (como un formulario de registro personalizado).
    - **Servicios de terceros**: Inserción de un reproductor de YouTube configurado con parámetros en la URL (`autoplay=1`, `mute=1`) para respetar las políticas del navegador, y mapas de Google Maps.
    - **Navegación dinámica**: Uso combinado del atributo `name` en el `<iframe>` y el atributo `target` en una lista de enlaces `<nav>` para cambiar el contenido del marco interactivo sin recargar la página principal.

2. Reproducción de Video Local

    Inserción y control de contenido audiovisual alojado localmente utilizando la etiqueta `<video>`:
    - **Atributos clave**: Configuración de la interfaz de usuario con `controls`, reserva de espacio en pantalla con `width` y `height`, y uso del atributo `poster` para mostrar una imagen de portada antes de iniciar la reproducción.
    - **Compatibilidad de formatos (Fallbacks)**: Implementación de múltiples etiquetas `<source>` para ofrecer el video en diferentes formatos (`.mp4`, `.webm`), asegurando el soporte en distintos navegadores, junto con un texto de respaldo para versiones obsoletas.

3. Reproducción de Audio Local

    Implementación de flujos de sonido integrados en el documento web mediante la etiqueta `<audio>`:
    - **Interfaz y controles**: Uso del atributo `controls`, indispensable para que el usuario pueda visualizar el reproductor e interactuar con el archivo de sonido (play, pausa, volumen).
    - **Fuentes alternativas**: Uso de múltiples etiquetas `<source>` para cargar el mismo archivo de audio didáctico en diferentes formatos y calidades (MP3, AAC, FLAC) maximizando la compatibilidad universal, además de incluir el correspondiente mensaje de advertencia.