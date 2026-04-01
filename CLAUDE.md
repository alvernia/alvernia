# alvernia/website — Renaud Wellens personal site

## Context
Minimalist personal site hosted on GitHub Pages via Jekyll.
Targeted at **recruiters and employers**.

## Identity
- **Name**: Renaud Wellens
- **Brand**: AlverniA
- **Tagline FR**: Lead Tech · CTO · Expert en transformation numérique
- **Tagline EN**: Tech Lead · CTO · Digital Transformation Expert
- **Brand tagline**: Exceeding expectations, one project at a time.
- **Location**: Liège, Belgium

## Links
- GitHub: https://github.com/alvernia
- LinkedIn: https://www.linkedin.com/in/rwellens
- Email: hello@alvernia.io

## Domains
Domains alvernia.io, alvernia.be (and others) are available.
The repo is `alvernia/alvernia` — the custom domain will be configured on GitHub Pages.

## Tech stack
- **Jekyll** (static site generator, natively supported by GitHub Pages)
- **Custom CSS** — no framework, no JS dependency
- `prefers-color-scheme` for automatic dark/light mode (AlverniA palette)
- Manual FR/EN language toggle (no i18n lib, just minimal vanilla JS)

## Color palette (AlverniA)
- Dark navy: `#002b49`
- Cyan technical blue: `#00cfff`
- White: `#ffffff`

## Assets
- Icon logo (mountain in circle): `assets/img/logo-icon.png`
- AlverniA wordmark: `assets/img/logo-wordmark.png`
  → to be copied from `../Branding/`

## Jekyll structure
```
website/
├── CLAUDE.md
├── README.md
├── _config.yml
├── index.html          ← single page
├── assets/
│   ├── css/
│   │   └── main.css
│   └── img/
│       ├── logo-icon.png
│       └── logo-wordmark.png
└── _data/
    └── i18n.yml        ← FR/EN strings
```

## Constraints
- **Single page** — no navigation, no blog
- **Zero dependency** — no npm, no bundler, no CSS framework
- **Minimalist** — name, tagline, 3 links (GitHub / LinkedIn / Contact), language toggle
- Content vertically centered on the page
