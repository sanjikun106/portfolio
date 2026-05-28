# Portfolio — Darshan Sonawane

Single-page, deck-style portfolio built around the intersection of **quantitative finance** and **product strategy**. Hand-crafted HTML/CSS — no template, no framework — designed with the rhetorical patterns of a winning case-competition deck (action titles, foreshadowing, moneyshot, symmetric treatment, three-scenario thinking).

## Live site

Deployed via GitHub Pages from `main` using the workflow in `.github/workflows/deploy.yml`.

URL: `https://sanjikun106.github.io/portfolio/` *(once Pages is enabled — see below)*

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

Or open `index.html` directly in a browser.

## Stack

- Pure HTML + CSS (single file, ~30 KB)
- Tiny inline JS for scroll-reveal (IntersectionObserver)
- Google Fonts: Instrument Serif, Inter, JetBrains Mono
- Mobile-responsive, dark-mode native, prefers-reduced-motion friendly
- A11y: semantic HTML, sufficient contrast, no JS dependencies for content

## Structure

The page mirrors an 8-section case-comp deck:

| # | Section | Purpose |
|---|---------|---------|
| I | Cover | Positioning headline + tagline |
| II | Executive Summary | Three reasons to hire — symmetric grid |
| III | Moneyshot | The 4 numbers that summarize 18 months of work |
| IV | Work | Two project tracks (Strategy + Quant), each with 4 case cards |
| V | Capabilities | Three-muscle skills grid |
| VI | Background | Education + recognition |
| VII | Recommended Action | Contact CTAs |
| — | Footer | Credit + back-to-top |

## Customizing

Most edits live inside `index.html`. Things you'll likely want to swap:

- `<title>` and the SEO meta description
- LinkedIn URL (currently a placeholder `/in/darshan-sonawane`)
- Resume link (`resume.pdf` — drop your PDF in the repo root)
- Award dates if anything has shifted
- Project metrics if you want to highlight different numbers

## Enable GitHub Pages

1. Push this repo to `github.com/sanjikun106/portfolio`
2. Settings → Pages → Build and deployment → Source: **GitHub Actions**
3. The workflow auto-deploys on every push to `main`

## License

Personal portfolio. Don't copy the content; feel free to study the structure.
