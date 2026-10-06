# Entrega de maquetado HTML

## Abrir las páginas

Abra `frontend/index.html` en un navegador. No requiere NetBeans, Java, MySQL ni instalar dependencias. Todos los enlaces internos usan rutas relativas.

También puede usar un servidor estático desde la raíz del repositorio:

```bash
python3 -m http.server 8000 --directory frontend
```

La entrega contiene únicamente HTML e imágenes, sin CSS ni JavaScript. La apariencia predeterminada del navegador es intencional: la guía deja los estilos para la siguiente actividad.

## Actividades realizadas

| Clase | Evidencia |
| --- | --- |
| 1 | Documentos HTML5, idioma español, UTF-8, viewport y títulos propios. Bienvenida en `index.html`. |
| 2 | Presentación con `strong` y `em`, integrantes, objetivo, separador y derechos de autor en `index.html`. |
| 3 | Imágenes con `alt` y enlaces de ida y vuelta entre inicio y contacto. |
| 4 | Menús con `nav`, `ul`, `li` y `a`; pasos de uso con `ol`. |
| 5 | Tablas de inventario, usuarios, proveedores y ventas con `caption`, `thead`, `tbody` y encabezados. |
| 6 | `header`, `main`, `section`, `footer` y tres `article` con estructura común en inicio; `aside` en el panel. |
| 7 | `registro.html` con nombre, correo, contraseña, fecha, ciudad, radios, términos y envío; campos enlazados con sus etiquetas. |
| 8 | `multimedia.html` con video y mapa incrustados; comentarios que explican tres clases y un identificador. El mapa muestra la Universidad de Pamplona, sede principal. |
| 9 | Inventario en `docs/pantallas.md`, esquemas en `docs/esquemas-html.md` y maquetado de pantallas enlazadas. |

## Verificación realizada

- Las 15 páginas pasaron el **Nu HTML Checker** local, versión `26.10.6`, sin errores. Es el motor de validación HTML usado por el servicio del W3C; no se afirma que se haya enviado la entrega a la web del W3C.
- Chromium abrió las 15 páginas y comprobó un solo `h1` y `main`, metadatos, identificadores únicos, imágenes cargadas y ausencia de CSS y JavaScript.
- Se comprobaron 138 enlaces internos y 8 formularios con etiquetas y nombres de campo.
- Los ocho formularios bloquearon el envío vacío mediante la validación nativa del navegador.
- En registro se verificaron datos ficticios válidos, rechazo de correo inválido y contraseña corta, y restablecimiento de campos, radios y términos.
- La estructura se revisó con etiquetas correctamente anidadas e indentación de dos espacios.
- El video y mapa externos no se incluyen en las comprobaciones de disponibilidad: requieren conexión y pueden estar sujetos a restricciones del proveedor.

## Alcance y pendientes

Los formularios son maquetas: no hay backend web, persistencia ni inicio de sesión real en HTML. El proyecto Java adjunto no fue modificado. Las ocho capturas suministradas están mapeadas en docs/pantallas.md y preservadas en docs/prototipo/.

Se compararon las ocho capturas del prototipo y se utiliza el logo original del proyecto Java. El reparto de integrantes es propuesto; no se atribuyen aportes ni revisiones que no han ocurrido. La rama `feature/maquetado-html` está publicada en GitHub. No se pudo abrir el Pull Request desde este entorno porque la API respondió `Forbidden`. La apertura del PR y la revisión real por un compañero siguen pendientes.
