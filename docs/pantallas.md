# Inventario de pantallas — Vital Dog Cat

Entrega de maquetado HTML, sin CSS ni JavaScript, basada en la guía suministrada. La referencia disponible es `veterinaria(avance2).zip`, proyecto Java Swing de NetBeans. No se suministró un enlace o archivo de Figma; la coincidencia con ese prototipo queda pendiente de revisión.

## Pantallas y reparto propuesto

Los nombres de los integrantes provienen del README. Este reparto es una propuesta para organizar la entrega, no una afirmación de que cada integrante ya realizó o revisó estas páginas.

| Página | Pantalla o ejercicio | Referencia | Responsable propuesto |
| --- | --- | --- | --- |
| `frontend/index.html` | Inicio, presentación, integrantes y módulos | README y ejercicios 1–6 | Luis Sebastian Echavez Carreño |
| `frontend/login.html` | Inicio de sesión | `Login_vista.java` | Luis Sebastian Echavez Carreño |
| `frontend/admin.html` | Panel principal | `Admin_vista.java` | Luis Sebastian Echavez Carreño |
| `frontend/inventario.html` | Gestión de inventario | `Inventario_vista.java` | Luis Sebastian Echavez Carreño |
| `frontend/nuevo-producto.html` | Nuevo producto | Diálogo de `Controlador.java` | Luis Sebastian Echavez Carreño |
| `frontend/usuarios.html` | Gestión de usuarios | `Usuarios_vista.java` | Erik Sebastian Gonzalez Estupiñan |
| `frontend/nuevo-usuario.html` | Nuevo usuario | Diálogo de `Usuarios_vista.java` | Erik Sebastian Gonzalez Estupiñan |
| `frontend/proveedores.html` | Gestión de proveedores | `Proveedores_vista.java` | Erik Sebastian Gonzalez Estupiñan |
| `frontend/nuevo-proveedor.html` | Nuevo proveedor | Diálogo de `Controlador.java` | Erik Sebastian Gonzalez Estupiñan |
| `frontend/registro.html` | Registro con los campos de la clase 7 | Ejercicio de la guía, adicional a NetBeans | Erik Sebastian Gonzalez Estupiñan |
| `frontend/contacto.html` | Contacto y enlace de regreso | Ejercicio de la clase 3 | Erik Sebastian Gonzalez Estupiñan |
| `frontend/multimedia.html` | Video, mapa y atributos globales | Ejercicio de la clase 8 | Luis Sebastian Echavez Carreño |
| `frontend/ventas.html` | Registrar venta | Extensión del botón del panel; no hay vista desarrollada en el ZIP | Luis Sebastian Echavez Carreño |
| `frontend/registro-ventas.html` | Registro de ventas | Extensión del botón del panel y modelo de venta; no hay vista desarrollada en el ZIP | Luis Sebastian Echavez Carreño |

## Decisiones de maquetado

- Se conservan los nombres de módulos, acciones y columnas presentes en NetBeans. Los diálogos de alta se representan como páginas HTML enlazadas.
- Las tablas muestran un estado vacío; no se inventan registros reales ni se publican datos personales o contraseñas del SQL.
- `registro.html` es el ejercicio académico con nombre, correo, contraseña, fecha de nacimiento, ciudad, tipo de usuario y aceptación de términos. No reemplaza el formulario de administración `nuevo-usuario.html`.
- Los formularios tienen etiquetas, nombres, tipos y validación nativa. Usan POST y un ancla local como destino provisional. No existe backend web: enviar un formulario válido desde un servidor estático no guarda datos y puede responder 501. No se implementan autenticación, permisos ni eliminación real.
- El SVG del encabezado es una identificación textual provisional. `img/referencia-login.png` es la imagen original de NetBeans, sin editar. No se afirma que estas imágenes hayan sido exportadas desde Figma.
- El video incrustado es un ejemplo público de libre acceso (Big Buck Bunny). El mapa utiliza la Universidad de Pamplona, indicada por el usuario; se tomó como referencia su sede principal en Pamplona, Norte de Santander.
- Los iframes dependen de Internet y de las políticas de YouTube y Google Maps. Sus títulos y el enlace alternativo del video permiten identificar su contenido.

## Pendiente de la entrega grupal

Confirmar el reparto con los integrantes, comparar las páginas con Figma y reemplazar los recursos provisionales con las exportaciones originales. La implementación está en la rama local `feature/maquetado-html`; la publicación en GitHub y la revisión cruzada real por un compañero no se han realizado.
