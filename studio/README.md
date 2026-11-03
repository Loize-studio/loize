# LOIZÉ — tienda online actualizada (noviembre 2026)

Sitio HTML/CSS/JS para GitHub Pages. Incluye 20 modelos de catálogo, fotografías reales, logotipo LOIZÉ, nuevo isotipo con rayos, filtros, bolsa de compra y pedido por WhatsApp.

## Publicación
1. Descomprimí el ZIP.
2. Subí **todos los archivos y carpetas que están dentro** a la raíz de tu repositorio GitHub (index.html en la raíz).
3. En Settings → Pages → Deploy from a branch → main → /(root) → Save.
4. Esperá a que GitHub publique el sitio.

## IMPORTANTE: comprobar antes de publicar
- **WhatsApp**: el número heredado de la versión anterior es `5491172347062`. Número confirmado. Si necesitás modificarlo, cambialo en `app.js` (`CONFIG.whatsapp`) y en el enlace del pie de `index.html`.
- **Rompeviento blanco**: talle M confirmado.
- **Remera deportiva vendida**: no se descontó ninguna variante porque no se confirmó color y talle.
- **Calza Oxford negra M**: no figura disponible.
- **Pantalón ancho celeste**: S y L disponibles; M vendido.
- **Pantalones azul marino y gris**: se registraron M y L en ambos colores a $34.000.
- **Conjunto bordó**: usa la misma campera bordó M y bermuda bordó L. El carrito impide reservar a la vez el conjunto y sus piezas por separado.

## Stock y limitaciones
`productos.json` contiene modelos, precios, variantes y stock. Las compras se solicitan por WhatsApp; **no hay sincronización automática entre distintos clientes ni descuentos de stock al concretar una venta**. Actualizá el JSON manualmente después de cada venta. El carrito impide superar el stock mostrado dentro de la sesión del comprador, pero no bloquea pedidos simultáneos entre personas distintas.

Los productos antiguos provienen de la versión anterior y los nuevos ingresos de las fotos y datos compartidos. Revisá todo el inventario antes de difundir la tienda.

## Correcciones de esta entrega
- Se normalizaron nombres de las imágenes bordó para evitar fallas en GitHub Pages.
- Se crearon versiones transparentes del logotipo y del isotipo originales.
- Se corrigieron tamaño y proporción de tarjetas y fotos sin alterar las fotografías.
- Se confirmó el talle M del rompeviento blanco.

## Correcciones del catálogo (03/11/2026)
- Calzas flare con vivos, azul y negra se muestran en la categoría Calzas.
- Se quitó la variante negra M vendida de la publicación «Pantalón deportivo» para evitar duplicar la calza flare negra S. Se conserva la variante celeste S de esa publicación.
- Pantalón parachute celeste M: foto original provista por el usuario, guardada como img/parachute_celeste_original.webp.
- Se conservan las demás fotos, talles, precios, logos y diseño.
