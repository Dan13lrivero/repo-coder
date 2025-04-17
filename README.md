# Daniel Rivero - Página Web Personal

Este es el sitio web personal de Daniel Rivero, un músico y artista dedicado a la música en vivo, clases de música, y proyectos relacionados. La web incluye secciones sobre sus servicios, su biografía, un blog, y un formulario de contacto para consultas, colaboraciones y contrataciones musicales.

## Estructura del Proyecto

El proyecto está compuesto por los siguientes archivos y directorios:

- **index.html**: Página principal del sitio.
- **about_me.html**: Sección sobre mí, donde se cuenta la historia y trayectoria de Daniel Rivero.
- **services.html**: Información sobre los servicios ofrecidos por Daniel (clases, contrataciones, etc.).
- **blog.html**: Blog con artículos, videos y reflexiones sobre música.
- **contact.html**: Formulario de contacto para consultas y contrataciones.
- **assets/**: Contiene imágenes y otros recursos estáticos del sitio.
  - **img/**: Imágenes utilizadas en el sitio.
- **css/**: Contiene el archivo CSS compilado desde SCSS.
  - **style.css**
- **scss/**: Carpeta donde se organiza el código SCSS.
  - **main.scss**: Archivo principal que importa todos los partials con `@use`.
  - **_variables.scss**: Variables globales (colores, fondos, etc.).
  - **_mixins.scss**: Mixins reutilizables como `flexbox` y `wh`.
  - **_animations.scss**: Animaciones personalizadas con `@keyframes` y clases como `.fadeIn`.
  - **_base.scss**: Reset y estilos generales del sitio.
  - **_components.scss**: Estilos de componentes como `.social_box`, `.redes`, `.container`, etc.
  - **_mediaqueries.scss**: Media queries para distintos dispositivos.

## Características

- **Diseño Responsivo**: El sitio se adapta a distintos tamaños de pantalla (desktop, tablet, móvil) utilizando `media queries` organizadas en un partial.
- **SCSS Modular**: Uso de SCSS con `partials`, `variables`, `mixins`, `@extend` y `nesting`, facilitando el mantenimiento y escalabilidad del proyecto.
- **Animaciones**: Incluye una animación personalizada de desvanecimiento (`fadeIn`) creada con `@keyframes`.
- **Interactividad**: Carrusel de imágenes, efectos `hover` y enlaces a redes sociales.
- **Optimización SEO**: Metadatos como `description` y `keywords` para mejorar la visibilidad en buscadores.
- **Uso de Bootstrap**: El framework facilita un diseño moderno, limpio y adaptable.

## Funcionalidades

1. **Navegación**: Barra superior con enlaces a las secciones principales del sitio.
2. **Blog**: Espacio para compartir contenido relacionado con la carrera musical de Daniel.
3. **Formulario de Contacto**: Permite enviar mensajes para clases, contrataciones o colaboraciones.
4. **Redes Sociales**: Enlaces a Instagram, YouTube, Facebook, entre otras plataformas.

## Tecnologías Utilizadas

- **HTML5**: Estructura básica del sitio web.
- **SCSS**: Preprocesador CSS usado con `@use` y organización por partials.
- **CSS3**: Estilos visuales personalizados, animaciones y efectos.
- **Bootstrap**: Framework para facilitar el diseño responsivo.
- **JavaScript (AOS)**: Animaciones al hacer scroll.

## Licencia

Este proyecto es de uso personal y no está destinado a la distribución comercial.

2025 Daniel Rivero | Todos los derechos reservados.
