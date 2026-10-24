# FIX IT! Soluciones eléctricas — fixit-electricidad.com

La web de FIX IT! electricidad (@fixitelectricidad), electricistas en La Plata y alrededores.
Sitio estático servido por GitHub Pages en https://fixit-electricidad.com (dominio en `CNAME`, sin www: así lo dejó el dueño en Settings → Pages el 24/10; www y http redirigen ahí).

- **Esta es la fuente del sitio.** La vitrina de demos (`demos.hg-vl.com/demo-fixit/`) es una copia con `noindex`.
- Contacto: solo WhatsApp 221 497-5090 (`CFG.whatsapp` en `index.html`), mail, Instagram y Facebook. Nada llama a una API.
- El tablero «¿Qué te pasa?» (`CFG.problemas`) arma el mensaje de WhatsApp con el problema, dónde, para cuándo y la zona.
- Trabajos: `CFG.trabajos`, uno por post de su Instagram (texto resumido de su caption, lugar = ubicación del post).
- Certificados: `CFG.certificados` vacío = el botón no aparece; completar con el link cuando lo pasen.
- Fotos y videos: de su Instagram, sin retocar (con su marca de agua); los videos sin audio.
- Ficha para Google: el bloque `application/ld+json` (Electrician) en el `<head>`; `robots.txt` y `sitemap.xml` en la raíz.
