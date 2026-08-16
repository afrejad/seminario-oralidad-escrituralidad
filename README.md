# Seminario de Oralidad y Escrituralidad — sitio espejo

Sitio estático preparado para GitHub Pages.

## Estructura

- `index.html`: página de presentación.
- `unidad-1.html` a `unidad-4.html`: páginas de cada unidad.
- `assets/styles.css`: estilos generales del sitio.
- `404.html`: página para enlaces inexistentes.

## Cómo poner el contenido de Moodle

1. Abre `index.html` y busca el comentario `PEGA AQUÍ EL HTML DE LA PÁGINA DE PRESENTACIÓN DEL MOODLE`.
2. Reemplaza la `section` que contiene la clase `paste-zone` por tu código HTML de Moodle.
3. Haz lo mismo en cada archivo `unidad-X.html`.
4. Si el HTML de Moodle tiene estilos en línea (`style="..."`), puedes conservarlos.
5. Para enlaces entre páginas usa rutas relativas, por ejemplo `unidad-2.html`.

## Publicación rápida en GitHub Pages

1. Crea un repositorio nuevo, por ejemplo `seminario-oralidad-escrituralidad`.
2. Sube todos estos archivos respetando la carpeta `assets`.
3. Ve a **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)` y guarda.
6. GitHub mostrará la dirección pública del sitio en la sección Pages.

## Consejo para las lecturas

Lo más estable es enlazar las lecturas desde repositorios institucionales, DOI, revistas, bibliotecas o Drive con permisos de lectura. No subas a un repositorio público archivos con restricciones de derechos de autor si no tienes permiso para redistribuirlos.
