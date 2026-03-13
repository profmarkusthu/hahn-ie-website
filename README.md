# HAHN-ie Website

Website für [hahn-ie.com](https://hahn-ie.com) — gebaut mit Hugo.

## Lokal testen

```bash
hugo server -D
# → http://localhost:1313
```

## Content bearbeiten

| Seite | Datei |
|-------|-------|
| Homepage | `content/_index.md` |
| About | `content/about/_index.md` |
| Services | `content/services/_index.md` |
| Publications | `content/publications/_index.md` |
| Contact | `content/contact/_index.md` |
| Impressum | `content/impressum/_index.md` |

Design/Layout: `layouts/_default/baseof.html`
Konfiguration: `hugo.toml`

## Deployment

Push to `main` → Netlify baut automatisch.

Build command: `hugo --gc --minify`
Publish directory: `public`
