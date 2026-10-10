# Stéphanie Nadeau — Portfolio

Static, responsive English-language portfolio site for GitHub Pages.

## Preview locally

From this directory, run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Structure

- `index.html` — homepage, services, AI and systems practice, seven applied case studies, language/localization work, client sectors, method, profile, rates and contact.
- `case-studies/` — seven public-facing case-study pages.
- `css/styles.css` — shared responsive styling.
- `js/site.js` — mobile navigation.
- `assets/` — logo and existing language-project visuals.

## Case studies

1. Custom AI Skill Development: Literary Voice Modeling
2. LLM Prompt Engineering & Logic Routing
3. Drive-to-Notion Migration Pipeline
4. DataBerry Nexus — Gmail Workflow Automation & Information Management
5. DataBerry — Gmail Finance Manager
6. The Sims 4 — Linguist Career Mod
7. Caifan — Accounting System Implementation & Operations Automation

The public pages deliberately omit the internal editorial and verification notes from the Word working documents. Claims about development status, operational use, metrics and testing are worded to distinguish implemented functionality from intended scope and reported results.

## Publishing

The site remains a static HTML/CSS/JavaScript project. Upload the contents of this folder to the repository root used by GitHub Pages. Keep the `assets`, `case-studies`, `css` and `js` folders alongside `index.html`.
