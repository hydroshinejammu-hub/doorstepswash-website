# DoorstepsWash Jammu — Website

Static website for DoorstepsWash Jammu (doorstep car & bike wash).

- No login or customer accounts — bookings go through WhatsApp.
- `index.html` — home page
- `booking.html` — booking form (WhatsApp handoff)
- `privacy.html`, `terms.html` — legal pages (DPDP Act, 2023 compliant)
- `mgr-413df040.html` — admin panel (pricing only), talks to the
  [doorstepswash-backend](https://github.com/) Cloudflare Worker
- `app.js`, `app.css`, `images.js` — site logic, styles, and embedded images

## Deploy
Static files — deploy as-is to Cloudflare Pages, Netlify, GitHub Pages, etc.
