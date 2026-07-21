# rgnera-media

Imágenes de los carruseles de **RGNERA** (@rgnera.mx) en JPEG 1080×1350,
usadas como origen público para la API de publicación de Instagram.

La API de Instagram descarga las imágenes por URL pública y **solo acepta JPEG**,
por eso este repositorio existe y por eso es público.

Se regenera desde la fábrica de contenido con:

    python export_jpg.py     # PNG 2160x2700 -> JPEG 1080x1350
    python sync_media.py     # copia a este repo y hace commit

Estructura: `publish/{id-del-post}/01.jpg, 02.jpg, ...`
