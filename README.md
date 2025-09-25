# Sitio estático — Ethos Vector

Este paquete contiene un Home robusto (HTML + CSS) listo para publicar en GitHub Pages y usar con Cloudflare.

## Archivos
- `index.html` — página principal con secciones: Hero, KPIs, Servicios, Proceso, Casos, Nosotros, Contacto.
- `styles.css` — estilos del sitio (paleta navy/teal).
- `assets/logo.svg` — **reemplázalo** por tu logo real si quieres.
- `assets/favicon.svg` — ícono simple.

## Configurar enlaces
- En `index.html`, reemplaza:
  - `https://wa.me/56XXXXXXXXX` por tu WhatsApp Business.
  - `action="https://formspree.io/f/your-id"` por el endpoint real de Formspree (u otro backend de formularios).

## Cómo subirlo a GitHub
1. Entra a tu repo `ethosvector.github.io`.
2. Haz clic en **Add file → Upload files**.
3. Arrastra **todos** los archivos (incluida la carpeta `assets`).
4. Commit.
5. Ve a **Settings → Pages** y en **Custom domain** confirma `ethosvector.cl`. Marca **Enforce HTTPS**.

## DNS (Cloudflare)
- Registros A para `@` (4 IPs de GitHub Pages).
- CNAME para `www` → `ethosvector.github.io`.
- SSL/TLS: modo **Full**, y activa **Always Use HTTPS** y **Automatic HTTPS Rewrites**.
- (Opcional) Regla de redirección `www → raíz` con 301.

¡Listo! Cualquier duda, escribe en WhatsApp 😉
