# Conquer Academy - Plataforma de Formación Full Stack

Este proyecto consiste en el desarrollo integral de la arquitectura web para **Conquer Academy**, una academia de formación técnica especializada en el sector del desarrollo de software. El sitio web ha sido construido priorizando la semántica de HTML5, la accesibilidad y el rendimiento en la carga de recursos.

## 🚀 Características Principales

- **Arquitectura Semántica:** Uso riguroso de etiquetas HTML5 (`<main>`, `<section>`, `<article>`, `<address>`) para un SEO optimizado y accesibilidad mejorada.
- **Imágenes Responsivas:** Implementación de la etiqueta `<picture>` para servir diferentes resoluciones según el dispositivo, mejorando los tiempos de carga (Web Performance).
- **Formularios Avanzados:** Sistemas de Registro y Login con validaciones nativas, tipos de entrada específicos (`email`, `url`, `date`) y soporte para carga de archivos multimedia.
- **Blog Tecnológico:** Secciones detalladas sobre tendencias actuales como WebXR, Edge Computing, Inteligencia Artificial y Seguridad Zero Trust.
- **Diseño Modular:** Estructura de navegación coherente con headers y footers unificados a través de todas las páginas.

## 📁 Estructura del Proyecto

```text
├── /img                     # Directorio de recursos visuales
│   ├── /blog                # Imágenes específicas de noticias
│   ├── /cursos              # Imágenes de la oferta educativa
│   └── (Logos, portadas y fotos generales)
├── /paginas                 # Documentos HTML internos
│   ├── /blog                # Páginas específicas de noticias
│   ├── /cursos              # Páginas de cursos específicos
│   ├── registro.html        # Formulario de alta de nuevos alumnos     
│   ├── contacto.html        # Ubicación, datos de empresa y soporte
│   └── (Resto de páginas de la academia)
├── index.html               # Página principal / Landing
├── README.md                # Documentación del proyecto
└── (Iconos y favicons para múltiples dispositivos)
```

## 🛠️ Tecnologías Utilizadas

- **HTML5:** Estructuración avanzada y formularios.

- **Soporte Multimedia:** Etiquetas de video, audio e integración de mapas vía `<iframe>`.

- **Favicons & Metadatos:** Configuración completa para dispositivos móviles y redes sociales (Open Graph / SEO).

## 📝 Detalles de Implementación

- **Validación de Formularios:** Se han implementado atributos como `required`, `maxlength`, `minlength` y `pattern` para asegurar la integridad de los datos antes del envío al servidor.

- **Seguridad en la Transmisión:** El formulario de registro utiliza el tipo de codificación `multipart/form-data` para el manejo correcto de archivos binarios (fotos).

- **Interconectividad:** Mapa web completo que permite la navegación fluida entre todas las secciones mediante rutas relativas optimizadas.

Este proyecto refleja los estándares actuales de desarrollo web frontend enfocado en la claridad del código y la experiencia de usuario.

Nota técnica: Este proyecto se enfoca exclusivamente en la arquitectura semántica con HTML puro. La presentación visual y las validaciones dinámicas avanzadas se delegarán a futuras capas de CSS y JavaScript respectivamente.