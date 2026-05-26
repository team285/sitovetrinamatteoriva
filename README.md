# Matt | AI Automation — Landing

Single-page static landing servita via **Caddy** su Railway.

## Stack

- HTML/CSS/JS vanilla, single-file (`index.html`)
- Caddy come web server (configurato in `Caddyfile`)
- Deploy: Railway (auto-detect Caddyfile via Nixpacks)

## Deploy

Push su branch `main` → Railway redeploy automatico.

Custom domain configurato in Railway → **Settings** → **Domains**.

## Local preview

```bash
# con Caddy installato
caddy run

# oppure con python (semplice)
python -m http.server 8000
```

## File da aggiornare

- `index.html` — link Calendly (cerca `calendly.com/mataiautomation/discovery-call`)
- `index.html` — handle Instagram (cerca `instagram.com/mataiautomation`)
