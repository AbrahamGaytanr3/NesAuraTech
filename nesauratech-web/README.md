# NesAura Tech — sitio web

Página de NesAura Tech (León, Guanajuato): servicios, cotizador en vivo que envía a WhatsApp, promociones y contacto.

Sitio estático (HTML + imágenes), listo para GitHub Pages.

## Publicar en GitHub Pages

1. Crea un repositorio público en GitHub llamado `nesauratech`.
2. Sube esta carpeta:
   ```bash
   git remote add origin https://github.com/AbrahamGaytanr3/nesauratech.git
   git push -u origin main
   ```
3. En el repositorio: **Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)`** → Save.
4. En 1–2 minutos queda en `https://abrahamgaytanr3.github.io/nesauratech/`.

## Si cambia la dirección del sitio

La imagen de vista previa (cuando compartes el enlace en WhatsApp o Facebook) usa una dirección completa en `index.html`, línea `og:image`. Si usas otro usuario, otro nombre de repositorio o un dominio propio, actualízala.

## Dominio propio (opcional)

Crea un archivo `CNAME` con el dominio (por ejemplo `nesauratech.com`) y configura el DNS según la guía de GitHub Pages.
