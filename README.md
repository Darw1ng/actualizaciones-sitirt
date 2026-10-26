# Actualizaciones · DeveloperSitirt

Espejo del canal de actualizaciones de nuestros sistemas. Los sistemas instalados lo consultan solos; no hay nada que bajar a mano desde aquí.

- `pos-estable` → `pos-estable.json`: el manifiesto de la versión vigente del punto de venta, firmado (Ed25519).
- `pos-<versión>` → el instalador de esa versión.

Cada sistema revisa la firma con la llave pública que trae adentro, y el instalador por su tamaño y su sha256 firmados. Si algo no cuadra, no se instala.
