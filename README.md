# Jeannely — Aprende Español

Landing page for Spanish teacher Jeannely, built with [Zola](https://www.getzola.org/).

## Quick Start

```bash
brew install zola        # Install Zola (macOS)
zola serve               # Dev server at http://127.0.0.1:1111
```

## Build for production

```bash
zola build               # Generates public/
```

Deploy the `public/` directory to any static host (Netlify, Vercel, GitHub Pages, Cloudflare Pages, etc.).

## Project Structure

```
├── zola.toml            # Site configuration
├── content/
│   ├── _index.md        # Homepage content + data (services, pricing, testimonials)
│   └── blog/
│       ├── _index.md    # Blog section config
│       └── *.md         # Blog posts
├── static/
│   ├── style.css        # All styles
│   └── images/          # Images
├── templates/
│   ├── base.html        # Layout (nav, footer, head, JS)
│   ├── index.html       # Homepage template
│   ├── blog.html        # Blog listing template
│   └── blog-page.html   # Blog post template
└── public/              # Generated output (do not edit)
```

## Customize

- **Services / Pricing / Testimonials**: Edit the `[[extra.*]]` arrays in `content/_index.md`
- **Styles**: Edit `static/style.css`
- **Contact form**: Replace `https://formspree.io/f/xxx` with your Formspree ID in `templates/index.html`
- **Phone / Email**: Edit in `templates/index.html`

## Deploy to GitHub Pages

1. Push to GitHub
2. Go to repo Settings → Pages
3. Set source to GitHub Actions and use the [Zola GitHub Action](https://github.com/shalzz/zola-deploy-action)
