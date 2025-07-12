Guía Básica de Uso — Biblioteca UI "HolaWeb"
============================================

Descripción general
-------------------
Esta biblioteca de componentes de interfaz de usuario (UI) ha sido desarrollada
utilizando HTML y CSS avanzado, sin JavaScript. Permite reutilización,
modularidad y coherencia visual en sitios y aplicaciones web. Está basada
en un proyecto de una empresa creativa llamada "HolaWeb", pero puede
adaptarse fácilmente a otros tipos de sitios o servicios digitales.

Estructura del proyecto
------------------------
/holaweb-ui/
├── index.html           -> Página de demostración de los componentes
├── style.css            -> Hoja de estilos con variables y diseño avanzado
└── /img/                -> Carpeta de imágenes para las tarjetas
    ├── diseno-web.jpg
    ├── branding.jpg
    ├── logo.jpg         -> Icono que aparece en la pestaña del navegador
    └── desarrollo.jpg

Componentes incluidos
---------------------
- Navbar responsivo: con menú hamburguesa sin usar JavaScript.
- Tarjetas con imagen: incluyen título, texto y botón que abre un modal.
- Modal: ventana emergente funcional sin JavaScript.
- Formulario de contacto: incluye validación HTML5 y tooltip de error.
- Tooltip: aparece solo cuando el usuario interactúa con campos inválidos.
- Badge: insignias visuales para marcar contenido nuevo.
- Acordeón (FAQs): secciones plegables usando etiquetas <details>.
- Footer: pie de página con enlaces simulados a redes sociales.

Diseño visual y estilo
----------------------
Paleta de colores:
  - Primario: #4A90E2
  - Secundario: #50E3C2
  - Fondo claro: #F5F7FA
  - Texto oscuro: #333

Tipografía:
  - Segoe UI, sans-serif

Características:
  - Uso de variables CSS para mantener consistencia visual.
  - Sombras suaves y bordes redondeados.
  - Pseudo-clases avanzadas como :hover, :focus:invalid.
  - Estructura semántica clara con HTML5.

Diseño responsivo
------------------
Se usó Flexbox, Grid y Media Queries para que todos los componentes se adapten
correctamente en pantallas pequeñas. El menú cambia a hamburguesa en móviles.

Validación y accesibilidad
---------------------------
- Los campos del formulario usan validación HTML5.
- Los mensajes de error (tooltips) aparecen al interactuar.
- Modal accesible con botón de cierre manual.
- Código organizado y semántico para facilitar futuras ampliaciones.

Cómo reutilizar los componentes
-------------------------------
1. Copiar los archivos index.html y style.css a tu proyecto.
2. Usar los componentes como plantillas y ajustar textos o imágenes.
3. Personalizar los colores y variables si deseas aplicar tu propio branding.
4. Asegurarte de mantener el orden y estructura CSS para conservar coherencia.

Autor
-----
Nombre: Kenin Avila
Carrera: Tecnologías de la información y comunicación
Universidad: Universidad Técnica de Manabí
Docente: Ing. Enrique Macías.

Estado del proyecto
-------------------
- Cumple con los criterios de CSS avanzado.
- Modular, responsivo y bien estructurado.
- Nombre del sitio: HolaWeb
