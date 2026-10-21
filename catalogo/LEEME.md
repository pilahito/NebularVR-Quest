# Catálogo de entornos de NebularVR

La Tienda de la app lee `catalogo.json` de esta carpeta (raw.githubusercontent.com) y descarga solo los archivos
que él lista. Para añadir un entorno: sube un panorama 360° **2:1** (JPG o PNG, máx. 8192×4096 y 40 MB) aquí y
añade su entrada con `id` (minúsculas, números, `_` o `-`), `name`, `file`, `sha256`, `size` (bytes), `category`
(`nature`, `sky`, `scifi`, `urban`, `interior`, `anime`, `cartoon`, `other`), `author`, `license`, `sun`, `energy`.
Calcula el hash con `sha256sum archivo.jpg`. La app rechaza cualquier descarga cuyo hash no coincida.

Los 4 entornos incluidos son imágenes procedurales originales de NebularVR (CC0).
