# mohammadsaadati80.github.io

Personal academic website of **Mohammad Saadati** — a single-page portfolio built with Jekyll and served via GitHub Pages.

Live site: https://mohammadsaadati80.github.io

## Structure

- `_layouts/home.html` — the self-contained homepage (styles, markup, and scripts inline; fonts via Google Fonts)
- `_pages/about.md` — the homepage entry point (`permalink: /`, `layout: home`)
- `images/profile3.png` — profile photo / favicon
- `files/` — linked PDFs (CV, posters)
- `_config.yml` — Jekyll configuration

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.
