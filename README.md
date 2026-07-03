# abedbarakat.me

Personal portfolio — live at [abedbarakat.me](https://abedbarakat.me).

Single-file site: vanilla HTML/CSS/JS, no framework, no build step, no trackers.

## Features
- i18n in 5 languages (EN/IT/DE/AR + Swiss German) with RTL support
- Light/dark theme, scroll-driven project reveals, View Transitions morph
- CSS-only animated project previews, custom canvas cursor
- Hosted on a DigitalOcean droplet behind Caddy (automatic HTTPS)

## Deploy
```
scp index.html root@SERVER:/var/www/portfolio/
scp media/* root@SERVER:/var/www/portfolio/media/
```
