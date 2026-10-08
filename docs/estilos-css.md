# Actividad de estilos CSS — Vital Dog Cat

## Actividades de la guía

| Clase | Implementación | Cómo demostrarla |
|---|---|-|
| 1. Conexión | Una hoja compartida, fondo y fuente en cuerpo, color de h1 | Abrir cual página e inspeccionar el enlace de estilos |
| 2. Selectores | Descendientes en nav, hover/focus/active, filas y pasos pares con nth-child, tarjeta destacada | Pasar el cursor por enlaces y observar filas alternativas |
| 3. Colores | Variables en :root para primario, secundario, texto, fondos, bordes, error y éxito; colores aplicados con var() | Cambiar una variable en DevTools y observar los componentes |
| 4. Tipografía | Open Sans, fuente serif para títulos del panel, escala h1/h2/h3/p/small, títulos centrados y botones en mayúsculas | Revisar los estilos calculados y tamaños |
| 5. Caja | Restablecer, cuadro de borde, relleno, margen, ancho máximo, bordes redondeados y sombras | Inspeccionar una tarjeta en Elementos y su modelo de caja |
| 6. Posición | Encabezado pegajoso; une bloque en línea; insignia absoluto dentro de tarjeta relativo; panel de alta supervisión y cierre positivo | Desplazarse en Inicio y abrir Agregar usuario |
| 7. Caja flexible | Encabezado con logo y menú; navegación con gap; tareas de integrantes con flex-wrap; pastel al final en las páginas públicas | Reducir la ventana y ver código se acomodan los elementos |
| 8. Rojo | Galería auto-fit/minmax; tarjeta destacada con span 2; sistema con grid-template-areas para encabezado, menú, contenido y pie | Mostrar Inicio y Panel principal en escrito y móvil |


## Paleta y tipografía


| Variable | HEX | Uso |
|---|---|-|
| --color-primario | #0759a4 | Encabezado del sistema y login |
| --secundario de color | #2aa6e6 | Acciones y botones |
| --menú de color | #0a3d68 | Barra lateral y pie |
| --color-activo | #2d74b4 | Opinión de menú activa |
| --color-texto | #172633 | Texto principal |
| --fondo de color | #f3f6f9 | Páginas académicas |
| --superficie de color | #ffffff | Contenido y campos blancos |
| --panel de color | #cdd8dd | Tablas y resumen |
| --color-borde | #269ed6 | Campos y tareas |
| --error de color | #d71920 | Cierre del panel de usuario |
| --exito de color | #207044 | Variable disponible para futuros estados de éxito |
| --modal de color | #d9ddff | Formulario de agregar usuario |

Abierto Sans se eligió como aproximación a la tipografía sans serif visible en el prototipo; Georgia y Times New Roman son los respaldos serif para los tejidos. No se conocen los nombres y sueños originales de Figma.

El texto de los botones celestes es oscuro para mejorar el contraste; en los botones azul oscuro se mantiene blanco. Los colores de fondo conservan el aspecto del prototipo.

## Adaptación e importancia

- Escritorio: barra lateral, login en dos columnas, funciones del panel en tabla y formularios de producto/venta en dos columnas.
- Hasta 900 px: espacios y hombres más compactos.
- Hasta 600 px: menú en filas, inicio de sesión apilado, campos y funciones en una columna, tareas adaptadas y formulario de usuario en el fluido normal.
 Actividad de estilos CSS — Vital Dog CatLa hoja externa 
| --- | --- | -- | Las etiquetas del formulario superpuesto siguen accesibles, une su presentación usa marcadores de posición como en la enfermedad.
- Los formularios continúan siendo maquetas sin backend. El CSS no implementa inicio de sesión, registro, eliminación ni guardado.

