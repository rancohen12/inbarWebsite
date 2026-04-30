# INBI - Inbar Cohen Landing Page

Lead-generation landing page for **Inbar Cohen**, an interior designer specializing in rental and temporary apartments.

🌐 **Live:** https://roy-asraf1.github.io/inbarWebsite/

## About

The site presents Inbar's three service tiers (INBI Lite / Focus / Complete), her story and approach, target personas, and direct contact channels. Built as a single-page Hebrew (RTL) landing page focused on driving WhatsApp leads.

## Tech Stack

- Plain **HTML / CSS / JavaScript** — no build step, no framework
- **Rubik** font (Google Fonts)
- Hosted on **GitHub Pages**

## Structure

```
site/
├── index.html       # All page content
├── styles.css       # Styles + responsive layout
├── script.js        # Mobile menu + scroll reveal
├── .nojekyll        # Disables Jekyll on GitHub Pages
└── images/          # Photos, logos, brand graphics
```

## Brand

| Token | Hex |
|---|---|
| Cream (background) | `#fff5ea` |
| Dark (text)        | `#393939` |
| Green (accent)     | `#33956f` |
| Pink (highlight)   | `#fec1bc` |
| Orange (process)   | `#C84F1E` |

## Local Development

```bash
cd site
python3 -m http.server 8000
# open http://localhost:8000
```

## Deployment

Pushing to `main` automatically updates the live site (GitHub Pages, ~1 min).

```bash
git add .
git commit -m "your message"
git push
```

## Contact

- **Phone / WhatsApp:** 052-2332878
- **Email:** inbiart@gmail.com
- **Instagram:** [@inbi_art](https://instagram.com/inbi_art)
