# Movilidad

App web (PWA) para iPhone con rutinas guiadas de estiramiento y movilidad.

## Publicar en GitHub Pages
1. Crea un repositorio nuevo (por ejemplo `movilidad`).
2. Sube estos archivos a la raíz: `index.html`, `manifest.json`, `sw.js`, `icon-180.png`, `icon-192.png`, `icon-512.png`.
3. En el repositorio: Settings > Pages > Source: `Deploy from a branch` > rama `main`, carpeta `/ (root)`.
4. Espera un minuto y abre `https://TU-USUARIO.github.io/movilidad/` en Safari.

## Instalar en el iPhone
Safari > Compartir > Añadir a pantalla de inicio. Se abre como una app y funciona sin conexión.

## Notas
- Los datos (sesiones, tests, ajustes) se guardan solo en el iPhone. Hay copia de seguridad en Ajustes.
- Si el iPhone está en silencio, no sonarán los pitidos.
- Para actualizar la app, sube el `index.html` nuevo y cambia el nombre de la caché en `sw.js` (`movilidad-v2`).
