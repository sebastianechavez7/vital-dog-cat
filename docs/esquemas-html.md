# Esquemas de bloques

## Estructura común

```text
body
├── header#encabezado.encabezado
│   ├── a → img (identificación de Vital Dog Cat)
│   └── nav → ul → li → a (pantallas enlazadas)
├── main#contenido.contenido
│   └── contenido de cada pantalla
└── footer.pie-pagina → p → small (© 2026)
```

## Inicio: index.html

```text
main
├── section#bienvenida → h1 + p + enlaces de acceso
├── section#integrantes → h2 + ul → li
├── hr
├── section#objetivo → h2 + p
├── section#modulos → h2 + 3 article.tarjeta-modulo → h3 + p + a
├── section#pasos → h2 + ol → li
└── section#referencia → h2 + figure → img + figcaption
```

## Panel: admin.html

```text
main
├── section#panel → h1 + p + nav → ul → li → a
├── section#funciones → h2 + ul → li → a
└── aside.resumen-inventario → h2 + dl → dt + dd
```

## Listados: inventario.html, usuarios.html, proveedores.html

```text
main
├── h1
├── nav (acciones) → ul → li → a (volver, actualizar, nuevo)
├── p → button (eliminar, deshabilitado sin selección)
└── section#listado → h2 + table
    ├── caption
    ├── thead → tr → th[scope=col]
    └── tbody → tr → td (estado vacío)
```

## Formularios: login.html, registro.html y altas

```text
main
├── h1
├── section.seccion-formulario
│   ├── h2 + p (estado de maqueta)
│   └── form[method=post]
│       ├── fieldset → legend + p → label + input/select
│       │   └── fieldset → legend + radio + label (solo registro)
│       └── p → button[submit] + button[reset]
└── p → a (regreso)
```

Las altas son `nuevo-producto.html`, `nuevo-usuario.html` y `nuevo-proveedor.html`. `ventas.html` usa el mismo esquema como extensión del módulo de ventas.

## Contacto: contacto.html

```text
main
├── h1
├── section#equipo → h2 + dl + p
├── section#contacto → h2 + p + form
│   └── fieldset → legend + label/input + label/textarea
└── p → a (volver al inicio)
```

## Multimedia: multimedia.html

```text
main
├── h1
├── section#video.seccion-video → h2 + p + iframe + enlace alternativo
└── section#ubicacion.seccion-mapa → h2 + p + iframe
```

## Registro de ventas: registro-ventas.html

```text
main
├── h1
├── section#ventas → h2 + table → caption + thead + tbody
└── p → a (registrar venta) + a (volver al panel)
```
