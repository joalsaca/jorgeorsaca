# Dulce Azul · Landing de postres

Web estática publicada en Cloudflare Workers.

- La página está en `public/index.html`.
- El número de WhatsApp se cambia en una sola línea, al final del archivo:
  `const WHATSAPP = "51999999999";` (código de país + número, solo dígitos).
- `wrangler.jsonc` le indica a Cloudflare que publique la carpeta `public/`.
- Cada push a la rama de producción se publica solo.
