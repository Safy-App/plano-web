# plano-web

Landing comercial de **Plano**, una app de gestión de finanzas
personales por **Safy App S.L.**

🌐 **Web**: https://plano-web.netlify.app
📱 **App**: https://safy-crm.netlify.app/personal.html

## Stack

HTML/CSS/JS vanilla en un solo archivo (`index.html`). Sin npm, sin
build, sin backend. Deploy automático en Netlify al hacer push a `main`.

## Estructura

- `index.html` — landing completa
- `assets/` — logo
- `icons/` — favicons y Open Graph image
- `netlify.toml` — configuración Netlify (publish raíz + headers de seguridad)

## Desarrollo

Abre `index.html` directamente en el navegador. No requiere servidor.

```bash
open index.html
```

Para publicar cambios:

```bash
git add . && git commit -m "..." && git push
```

Netlify despliega automáticamente en 1-2 minutos.

## Licencia

© Safy App S.L. — Todos los derechos reservados.
