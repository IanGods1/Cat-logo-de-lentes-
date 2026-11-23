# Catálogo de Lentes

Página para ver el catálogo de lentes del proveedor, elegir cuántos se quieren de cada uno
y mandar el pedido por WhatsApp (con fotos).

**Dirección:** https://iangods1.github.io/Cat-logo-de-lentes-/

## Cómo se usa
- Toque **+** / **−** debajo de cada foto para poner la cantidad. Toque la foto para verla en grande y agregar una nota.
- Toque la barra verde **🛒 Ver y enviar** → **📸 Enviar con fotos** → elija WhatsApp y al proveedor.
  Cada foto lleva escrito abajo el número, la cantidad y la nota.
- El botón **❓** de la página explica todo paso a paso.

## Cambiar las fotos por un catálogo nuevo
1. Copie el link del álbum de Google Fotos que mandó el proveedor.
2. En la página toque **🔄**, pegue el link y toque **Actualizar catálogo**.
3. En 2 a 5 minutos quedan solo las fotos nuevas.

**Con PDF o fotos:** en 🔄 → *Opción 2* → *📄 Elegir archivos*, escoja uno o varios PDF o fotos y toque
*Subir y actualizar*. Cada página de un PDF se vuelve una foto. Puede *Reemplazar todo* o *Agregar al final*.

La primera vez el botón 🔄 pide una clave de GitHub (los pasos están en la misma pantalla).
Sin clave: en GitHub → **Actions → Actualizar catálogo → Run workflow**, pegue el link y confirme.

## Archivos
- `index.html` – la página.
- `catalogo.json` y `fotos/` – el catálogo actual (los cambia el proceso de actualizar).
- `lib/pdf.min.js` y `lib/pdf.worker.min.js` – lector de PDF ([PDF.js](https://mozilla.github.io/pdf.js/), licencia Apache 2.0).
- `.github/workflows/actualizar-catalogo.yml` y `.github/scripts/actualizar-catalogo.js` – bajan las fotos del álbum.
