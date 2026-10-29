# LOIZÉ — tienda online

Sitio estático listo para publicar en GitHub Pages. No requiere instalar nada, compilar ni contratar servidor.

## Publicar en GitHub

1. Descomprimí el ZIP.
2. En GitHub creá un repositorio **público** llamado `loize-web`.
3. En el repositorio elegí **Add file → Upload files** y subí **el contenido de esta carpeta** (no el ZIP). `index.html`, `styles.css`, `app.js`, `productos.json` y la carpeta `img` deben quedar en la raíz del repositorio.
4. Confirmá los archivos con **Commit changes**.
5. Abrí **Settings → Pages → Build and deployment** y elegí **Deploy from a branch**, rama `main`, carpeta `/(root)`, y **Save**.
6. Esperá la publicación y abrí `https://TU-USUARIO.github.io/loize-web/`.

## Cambiar precios, talles, stock o fotografías

Editá `productos.json` desde GitHub (ícono del lápiz) y confirmá los cambios. Cada producto tiene `name`, `price` y `variants`. Cada variante contiene `color`, `size`, `img` y `stock`. Para sumar imágenes, subilas a `img/` y usá su ruta relativa en el JSON. Para cambiar textos o diseño: `index.html` y `styles.css`.

## WhatsApp

Configurado en `app.js`: `5491172347062`. El carrito abre WhatsApp con un mensaje de pedido y subtotal. **No cobra ni reserva stock automáticamente.** La disponibilidad final, envío y pago se coordinan por WhatsApp.

## Antes de compartir

- Verificá que los productos, fotografías, talles, precios y cantidades sean correctos.
- Probá el carrito y el envío del mensaje desde un celular.
- Revisá especialmente el stock: este sitio es estático y **no descuenta unidades cuando otra persona hace un pedido**. Para inventario en tiempo real se necesita un backend o plataforma de e-commerce.
- Abrí la web desde GitHub Pages, no con doble clic en `index.html`: algunos navegadores bloquean `fetch()` de archivos locales.

Instagram: https://www.instagram.com/loize.studio/
