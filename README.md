# Bible Garden — Website

Static public websites for the Bible Garden and Lampada apps.

Domains:

- [bible.garden](https://bible.garden) — Bible Garden
- [lampada.bible.garden](https://lampada.bible.garden) — Lampada

## Features

- Coverflow phone carousel with app screenshots
- Canvas firefly particle animation
- Responsive design (Tailwind CSS)
- i18n with localStorage persistence
- Separate Lampada site in `lampada/` with EN/RU translations
- Reserved Lampada routes at `/privacy` and `/support`

## Stack

- HTML + Tailwind CSS (CDN)
- Google Fonts: Lora + Inter
- Vanilla JavaScript
- No build step required

## Run locally

```bash
python3 -m http.server 8080
# open http://localhost:8080

# Preview the Lampada virtual host content
cd lampada && python3 -m http.server 8081
# open http://localhost:8081
```

## License

GPL v3 — see [LICENSE](LICENSE).
