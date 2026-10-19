# Manual independiente MULTINET 360

Sitio estático en español. No usa Supabase, claves, API ni credenciales. La selección de cargo es navegación, no control de acceso. Todo el contenido es público si se publica en GitHub Pages.

## Publicar

1. Crear un repositorio exclusivo para el manual, por ejemplo `MULTINET360-manual`.
2. Subir **solo el contenido de esta carpeta** a la raíz del repositorio. No subir el proyecto CRM, archivos Excel, `.env`, carpetas locales ni respaldos.
3. En Settings → Pages, seleccionar Deploy from a branch, rama `main`, carpeta `/ (root)` y guardar.
4. Compartir la URL que entregue GitHub Pages. No hay que configurar base de datos ni contraseñas.

## Contenido y mantenimiento

`content.js` contiene procedimientos y cargos; `app.js` filtra y busca; `style.css` define la presentación. `images/` contiene ilustraciones SVG originales de recorridos, no capturas de clientes. No hay dependencias externas, analítica ni CDN.

Revisado contra el código de frontend el 19 de octubre de 2026. Cuando cambie un botón o procedimiento, actualizar el manual y su fecha. Las reglas pendientes se señalan expresamente. Las imágenes son esquemas didácticos, no evidencia de una operación real.

Para revisar localmente: abrir `index.html`, o ejecutar un servidor estático sobre esta carpeta. La impresión genera la guía abierta; seleccionar una guía antes de imprimir.
