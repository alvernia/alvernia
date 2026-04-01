# AlverniA — Personal Site

Personal site for **Renaud Wellens** — Tech Lead · CTO · Digital Transformation Expert.

Live at: [alvernia.io](https://alvernia.io)

## Stack

- [Jekyll](https://jekyllrb.com/) — static site generator (GitHub Pages native)
- Custom CSS — no framework, no JS dependencies
- Vanilla JS — FR/EN language toggle with `localStorage` persistence
- `prefers-color-scheme` — automatic dark/light mode

## Color palette

| Token | Value | Usage |
|-------|-------|-------|
| Dark navy | `#002b49` | Background, text |
| Cyan | `#00cfff` | Accent, brand "iA" |
| White | `#ffffff` | Text on dark |

## Run locally

```bash
# Install Ruby 3.3+ via rbenv (first time only)
brew install rbenv ruby-build
echo 'eval "$(rbenv init -)"' >> ~/.zshrc && source ~/.zshrc
rbenv install 3.3.0 && rbenv local 3.3.0

# Install dependencies and serve
gem install bundler
bundle install
bundle exec jekyll serve --livereload
```

Site available at `http://localhost:4000`.

## Structure

```
website/
├── index.html        # Single page
├── assets/
│   ├── css/main.css  # All styles
│   └── img/          # Logo assets
└── _data/
    └── i18n.yml      # FR/EN strings
```
