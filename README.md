# Jeannely — Aprende Español

Landing page for Spanish teacher Jeannely. Built with plain HTML, CSS, and JavaScript.

## Testing Locally

Open the file directly in your browser:

```bash
open index.html
```

### Responsive Testing

1. Open `index.html` in Chrome
2. Press `Cmd+Option+I` (Mac) / `Ctrl+Shift+I` (Windows/Linux) to open DevTools
3. Click the **Toggle Device Toolbar** icon (or press `Cmd+Shift+M` / `Ctrl+Shift+M`)
4. Test different device presets: iPhone, iPad, desktop

### HTML Validation

Validate your HTML at: https://validator.w3.org/
Paste the page URL (once deployed) or upload the file directly.

### Link Check

Click all navigation links, the CTA button, email, WhatsApp, and social links to ensure they work.

## Deploy to GitHub Pages

### 1. Create a GitHub repository

Go to https://github.com/new and create a repo (e.g. `jeannely-spanish`). Keep it **public** (GitHub Pages is free on public repos).

### 2. Push the code

```bash
cd /path/to/webside
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/jeannely-spanish.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repo on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under **Branch**, select `main` and `/ (root)`, then click **Save**
4. Wait ~2 minutes

### 4. Your site is live at

```
https://YOUR_USERNAME.github.io/jeannely-spanish/
```

### Custom Domain (optional)

In the Pages settings, enter your custom domain under **Custom domain** and add the required DNS records with your provider.

## Customize

- **Phone number**: Edit `href="https://wa.me/521234567890"` in `index.html`
- **Email**: Edit `jeannely@example.com` in `index.html`
- **About text**: Edit the text in the `#about` section
- **Prices/packages**: Add new service cards in the `#services` section
