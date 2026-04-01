# alvernia/website — Site personnel de Renaud Wellens

## Contexte
Site personnel minimaliste hébergé sur GitHub Pages via Jekyll.
Destiné aux **recruteurs et employeurs**.

## Identité
- **Nom** : Renaud Wellens
- **Marque** : AlverniA
- **Tagline FR** : Lead Tech · CTO · Expert en transformation numérique
- **Tagline EN** : Tech Lead · CTO · Digital Transformation Expert
- **Localisation** : Liège, Belgique

## Liens
- GitHub : https://github.com/alvernia
- LinkedIn : https://www.linkedin.com/in/rwellens
- Email : rwellens@gmail.com

## Domaines
Les domaines alvernia.io, alvernia.be (et autres) sont disponibles.
Le repo est `alvernia/alvernia` — le domaine custom sera configuré sur GitHub Pages.

## Stack technique
- **Jekyll** (static site generator, natif sur GitHub Pages)
- **CSS custom** — pas de framework, pas de dépendance JS
- `prefers-color-scheme` pour le mode dark/light automatique (palette AlverniA)
- Toggle manuel FR/EN (pas de lib i18n, juste du JS vanilla minimal)

## Palette couleurs (AlverniA)
- Navy foncé : `#0d2d3e`
- Teal/bleu acier : `#3a7fa8`
- Blanc : `#ffffff`
- Gris clair (light mode bg) : `#f8fafc`

## Assets
- Logo icône (montagne en cercle) : `assets/img/logo-icon.png`
- Wordmark AlverniA : `assets/img/logo-wordmark.png`
  → à copier depuis `../Branding/`

## Structure Jekyll cible
```
website/
├── CLAUDE.md
├── _config.yml
├── index.html          ← page unique
├── assets/
│   ├── css/
│   │   └── main.css
│   └── img/
│       ├── logo-icon.png
│       └── logo-wordmark.png
└── _data/
    └── i18n.yml        ← textes FR/EN
```

## Contraintes
- **Une seule page** — pas de navigation, pas de blog
- **Zéro dépendance** — pas de npm, pas de bundler, pas de framework CSS
- **Minimaliste** — nom, tagline, 3 liens (GitHub / LinkedIn / Contact), toggle langue
- Contenu centré verticalement sur la page
