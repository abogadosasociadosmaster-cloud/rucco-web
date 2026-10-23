# Rucco — cómo se usa

- Tienda: `https://<usuario>.github.io/rucco-web/`
- Panel: `.../admin.html` (correo autorizado + contraseña). Desde ahí se cargan productos, precios, stock, fotos (opcionales), WhatsApp e Instagram.
- Para que "Publicar en la web" funcione: GitHub → Settings → Developer settings → Fine-grained tokens → acceso sólo a `rucco-web`, permiso **Contents: Read and write**. Se pega una vez en el panel (queda sólo en ese navegador).
- Sin token: "Descargar products.json" y subirlo al repo reemplazando el existente.
- La contraseña no está escrita en el repo, sólo su huella SHA-256 (`CLAVE_HASH` en admin.html).
