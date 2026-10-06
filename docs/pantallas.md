# Inventario de pantallas — Vital Dog Cat

Maquetado HTML sin CSS ni JavaScript. Se compararon las ocho capturas del prototipo enviadas por el usuario con los textos, campos, columnas y orden del HTML. Los originales están en `docs/prototipo/`.

## Reparto propuesto

Los integrantes provienen del README. Este reparto debe confirmarse con el equipo; no atribuye aportes ni revisiones que no han ocurrido.

| Página en frontend/ | Pantalla | Referencia en docs/prototipo/ | Responsable propuesto |
| --- | --- | --- | --- |
| admin.html | Inicio del sistema | inicio.jpeg | Luis Sebastian Echavez Carreño |
| login.html | Inicio de sesión | login.jpeg | Luis Sebastian Echavez Carreño |
| inventario.html | Inventario | inventario.jpeg | Luis Sebastian Echavez Carreño |
| nuevo-producto.html | Registrar producto | registrar-producto.jpeg | Luis Sebastian Echavez Carreño |
| ventas.html | Registrar venta | registrar-venta.jpeg | Luis Sebastian Echavez Carreño |
| registro-ventas.html | Registro de ventas | registro-ventas.jpeg | Luis Sebastian Echavez Carreño |
| usuarios.html | Usuarios | usuarios.jpeg | Erik Sebastian Gonzalez Estupiñan |
| nuevo-usuario.html | Usuarios con formulario de alta | agregar-usuario.jpeg | Erik Sebastian Gonzalez Estupiñan |
| editar-usuario.html | Editar usuario | Extensión del enlace Editar; sin captura propia | Erik Sebastian Gonzalez Estupiñan |
| index.html | Bienvenida, equipo y módulos | Ejercicios 1–6 | Luis Sebastian Echavez Carreño |
| registro.html | Registro académico | Ejercicio 7 | Erik Sebastian Gonzalez Estupiñan |
| contacto.html | Contacto | Ejercicio 3 | Erik Sebastian Gonzalez Estupiñan |
| multimedia.html | Video y mapa | Ejercicio 8 | Luis Sebastian Echavez Carreño |
| proveedores.html | Proveedores | Pantalla adicional de NetBeans | Erik Sebastian Gonzalez Estupiñan |
| nuevo-proveedor.html | Nuevo proveedor | Diálogo adicional de NetBeans | Erik Sebastian Gonzalez Estupiñan |

## Comparación con las ocho capturas

- Menú: INICIO, INVENTARIO, USUARIOS, Cerrar sesion y SALIR. Los ejercicios académicos tienen navegación adicional.
- Inicio: bienvenida a ADMINISTRADOR1, cuatro enlaces de funciones y tres estadísticas con asteriscos. Se conserva «STACK BAJO» porque así aparece en la captura.
- Login: Usuario, Contraseña e Iniciar. `admin1` es un placeholder ilustrativo, no un usuario autenticado ni una contraseña expuesta.
- Inventario: Nombre, Categoria, Cantidad, Precio y Fecha vencimiento; ACTUALIZAR LISTA y regreso.
- Producto: nombre, precio unitario, categoría, cantidad en stock y fecha de vencimiento; REGISTRAR PRODUCTO.
- Venta: nombre del cliente, producto, cantidad y fecha; REGISTRAR VENTA.
- Registro de ventas: Cliente, Producto, Cantidad, Costo y Fecha; ACTUALIZAR LISTA.
- Usuarios: Usuario, Rol y Acciones. Admin1 tiene Editar; empleado1 y empleado2 tienen Editar y Borrar. Son los ejemplos de la captura, no datos del SQL. Borrar está deshabilitado porque no hay lógica de eliminación.
- Alta de usuario: listado de fondo, cierre, nombre y tipo de usuario, Agregar. La superposición se representa con una sección en su propia página; CSS determinará el posicionamiento en la próxima actividad.

## Recursos y alcance

El logo usa los píxeles de la imagen original de NetBeans dentro de un viewport SVG embebido. No fue redibujado. Las capturas sirven como documentación: no reemplazan el HTML de campos o tablas.

Los formularios tienen POST, etiquetas, nombres y validación nativa. No hay backend web, autenticación ni almacenamiento. En un servidor estático, enviar datos válidos puede responder 501. Las categorías y el producto de demostración son opciones ficticias porque las capturas no muestran las listas desplegadas. Las tablas con asteriscos conservan los placeholders del diseño.

El mapa muestra la Universidad de Pamplona, sede principal, indicada por el usuario. El video de ejemplo es Big Buck Bunny; ambos recursos requieren Internet.

La rama `feature/maquetado-html` está publicada en GitHub. La API responde `Forbidden`, por lo que la apertura automática del PR está bloqueada. Falta abrir el PR y que un compañero real lo revise. No se han creado ramas ni simulado revisiones en nombre de los integrantes.
