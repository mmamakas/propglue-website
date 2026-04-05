# PropGlue Marketing Website

Professional sales and marketing website for PropGlue property management platform.

## Features

- 🎨 Modern, clean design
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Fast loading (single HTML file, no dependencies)
- 🎯 Clear value proposition
- 💼 Professional testimonials
- 💰 Transparent pricing
- 📧 Lead capture (demo requests)

## Pages

- **Homepage** (`index.html`) — Main landing page with features, use cases, pricing, and CTA

## Local Development

```bash
# Serve locally
python3 -m http.server 8000
# Open http://localhost:8000
```

## Deployment

### Option 1: Cloudflare Pages (Recommended)

1. Push to GitHub
2. Connect to Cloudflare Pages
3. Auto-deploy on push

### Option 2: Manual Deploy

```bash
npx wrangler pages deploy . --project-name=propglue-website
```

## Tech Stack

- Pure HTML/CSS (no build step)
- Google Fonts (Inter)
- Vanilla JavaScript (minimal)
- Cloudflare Pages hosting

## Customization

### Colors

Edit CSS variables in `<style>`:
```css
:root {
  --primary: #002D72;      /* Primary blue */
  --accent: #FF5910;       /* Accent orange */
  --bg: #F8FAFC;          /* Background */
}
```

### Contact Email

Update in HTML:
```html
<a href="mailto:YOUR_EMAIL@example.com">
```

### Pricing

Edit pricing cards in HTML (around line 450)

## License

Proprietary - Greenwire Solutions
