Tarea 12: Formularios en HTML5

Este proyecto contiene una serie de ejercicios prácticos enfocados en el dominio de la estructura de formularios en HTML5. Se trabajará con la etiqueta principal `<form>` y sus distintos controles de entrada (`<input>`, `<textarea>`, `<select>`, radio buttons, checkboxes), prestando especial atención a la accesibilidad mediante la correcta vinculación de las etiquetas `<label>`.

El proyecto se divide en dos bloques de trabajo: el desarrollo de un formulario completo a partir de unos requisitos técnicos específicos y la maquetación visual de tres formularios a partir de imágenes de referencia.

Estructura del ejercicio:

- `index.html`: Menú principal con acceso a todos los ejercicios del proyecto.
- `formulario_registro.html`: Ejercicio 12.1 - Formulario de registro a partir de enunciado.
- `formulario_estructurado.html`: Ejercicio 12.2 - Réplica de imagen (Formulario estructurado).
- `formulario_cv.html`: Ejercicio 12.3 - Réplica de imagen (Formulario currículum vitae).
- `formulario_producto.html`: Ejercicio 12.4 - Réplica de imagen (Formulario producto).

Enunciados:

1. Formulario de Registro

    Creación de una página web (`formulario_registro.html`) que contenga un formulario con los siguientes campos y controles:
    - Nombre y Apellidos (tipo texto, longitud máxima de 50 caracteres).
    - Sexo (opciones excluyentes: hombre o mujer).
    - Correo electrónico (tipo email).
    - Población (lista desplegable con: Alicante, Madrid, Sevilla y Valencia).
    - Descripción (área de texto multilínea).
    - Casilla de verificación: "Deseo recibir información sobre novedades y ofertas" (activada por defecto).
    - Casilla de verificación: "Declaro haber leído y aceptar las condiciones...".
    - Botón de envío.

    Requisitos técnicos adicionales:
    - El título de la página debe ser: *Formulario de registro - Mi web*.
    - El método de envío del formulario debe ser `GET`.
    - El destino del envío del formulario debe ser `""`.
    - Longitud máxima de 50 caracteres para los controles de Nombre y Apellidos.
    - Casilla "Deseo recibir informaciónsobre novedades y ofertas" activada por defecto.
    - Cada control debe tener asociada su etiqueta para mejorar la usabilidad y accesibilidad.
    - Agrupa los campos relacionados con la etiqueta adecuada.

2. Réplica de Capturas

    Maquetar 3 documentos HTML (`formulario_estructurado.html`, `formulario_cv.html`, `formulario_producto.html`) para que coincidan visual y estructuralmente con las imágenes de referencia proporcionadas, practicando la inserción y agrupación de diferentes controles de formulario.

Nota técnica: Al igual que en ejercicios anteriores, la presentación visual básica se logra con HTML puro, teniendo en cuenta que el diseño final y la validación avanzada se gestionarán en el futuro con CSS y JavaScript. En este sentido, se han agrupado los controles con etiquetas `<p>` para aprovechar sus márgenes y tener un espaciado legible sin usar CSS, aunque la práctica correcta para futuros proyectos será utilizar `<div>`.