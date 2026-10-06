# Actividad de estilos CSS — Vital Dog Cat

La hoja externa `frontend/css/estilos.css` está enlazada en las 15 páginas. No hay estilos en línea, etiquetas `style`, JavaScript ni uso de `!important`. La entrega HTML anterior permanece en el historial de Git.

## Actividades de la guía

| Clase | Implementación | Cómo demostrarla |
| --- | --- | --- |
| 1. Conexión | Una hoja compartida, fondo y fuente en body, color de h1 | Abrir cualquier página e inspeccionar el link de estilos |
| 2. Selectores | Descendientes en nav, hover/focus/active, filas y pasos pares con nth-child, tarjeta destacada | Pasar el cursor por enlaces y observar filas alternas |
| 3. Colores | Variables en :root para primario, secundario, texto, fondos, bordes, error y éxito; colores aplicados con var() | Cambiar una variable en DevTools y observar los componentes |
| 4. Tipografía | Open Sans, fuente serif para títulos del panel, escala h1/h2/h3/p/small, títulos centrados y botones en mayúsculas | Revisar los estilos calculados y tamaños |
| 5. Caja | Reset, border-box, padding, margen, max-width, bordes redondeados y sombras | Inspeccionar una tarjeta en Elements y su modelo de caja |
| 6. Posición | Encabezado sticky; enlaces inline-block; insignia absolute dentro de tarjeta relative; panel de alta superpuesto y cierre posicionado | Desplazarse en Inicio y abrir Agregar usuario |
| 7. Flexbox | Encabezado con logo y menú; navegación con gap; tarjetas de integrantes con flex-wrap; pie al final en las páginas públicas | Reducir la ventana y ver cómo se acomodan los elementos |
| 8. Grid | Galería auto-fit/minmax; tarjeta destacada con span 2; sistema con grid-template-areas para encabezado, menú, contenido y pie | Mostrar Inicio y Panel principal en escritorio y móvil |

El prototipo tiene fondos planos; no se añadió un degradado ni un fondo fotográfico que no aparece en sus capturas. Esa parte condicional de la clase 3 no aplica.

## Paleta y tipografía

Las capturas JPEG no incluyen metadatos de Figma. Estos valores son aproximaciones visuales, no mediciones exactas exportadas del archivo original:

| Variable | HEX | Uso |
| --- | --- | --- |
| --color-primario | #0759a4 | Encabezado del sistema y login |
| --color-secundario | #2aa6e6 | Acciones y botones |
| --color-menu | #0a3d68 | Barra lateral y pie |
| --color-activo | #2d74b4 | Opción de menú activa |
| --color-texto | #172633 | Texto principal |
| --color-fondo | #f3f6f9 | Páginas académicas |
| --color-superficie | #ffffff | Contenido y campos blancos |
| --color-panel | #cdd8dd | Tablas y resumen |
| --color-borde | #269ed6 | Campos y tarjetas |
| --color-error | #d71920 | Cierre del panel de usuario |
| --color-exito | #207044 | Variable disponible para futuros estados de éxito |
| --color-modal | #d9ddff | Formulario de agregar usuario |

Open Sans se eligió como aproximación a la tipografía sans serif visible en el prototipo; Georgia y Times New Roman son los respaldos serif para los títulos. No se conocen los nombres y tamaños originales de Figma.

Se enlaza Google Fonts según la guía. Como Google Fonts respondió 403 desde este entorno, se incluye una copia local de Open Sans (400, 600 y 700) obtenida del paquete oficial de Fontsource, con licencia OFL en `frontend/fonts/LICENSE-open-sans.txt`. La página prioriza esa copia: puede usar su tipografía aunque Google Fonts no esté disponible. No se requieren servicios externos para el CSS ni para las fuentes locales.

El texto de los botones celestes es oscuro para mejorar el contraste; en los botones azul oscuro se mantiene blanco. Los colores de fondo conservan el aspecto del prototipo.

## Adaptación y alcance

- Escritorio: barra lateral, login en dos columnas, funciones del panel en cuadrícula y formularios de producto/venta en dos columnas.
- Hasta 900 px: espacios y menú más compactos.
- Hasta 600 px: menú en filas, login apilado, campos y funciones en una columna, tarjetas adaptadas y formulario de usuario en el flujo normal.
- Las tablas permiten desplazamiento horizontal dentro de su panel sin desbordar toda la página.
- Las etiquetas del formulario superpuesto siguen accesibles, aunque su presentación usa placeholders como en el diseño.
- Los formularios continúan siendo maquetas sin backend. El CSS no implementa inicio de sesión, registro, eliminación ni guardado.

## Entrega

Rama de trabajo: `feature/estilos-css`. Para actualizar la página publicada desde main, la rama debe revisarse y fusionarse mediante un Pull Request. No se ha simulado revisión de un compañero ni fusionado la actividad automáticamente.

## Verificación realizada

- Las 15 páginas pasaron Nu HTML Checker 26.10.6 sin errores.
- Chromium abrió las 15 páginas a 1440 × 1000 y 390 × 844 px, comprobando estilos conectados, imágenes y fuentes locales cargadas, campos visibles y ausencia de desbordamiento horizontal.
- Se verificaron hover, foco de teclado, encabezado sticky, galería Grid, tarjeta destacada de dos columnas, Flexbox en integrantes, áreas del panel y navegación entre pantallas.
- Se comprobó que el registro bloquea el envío vacío y que el cierre de Agregar usuario regresa al listado.
- Las pruebas bloquearon recursos HTTPS externos deliberadamente para comprobar que las fuentes locales permiten usar el sitio sin Google Fonts. Video y mapa siguen requiriendo Internet.
- Se revisaron visualmente capturas del inicio, panel, login, inventario y alta de usuario en ambos tamaños.
