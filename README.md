# Custom Shopify Theme

Shopify 2.0 theme — built by Youni-G5.

## Structure

```
├── assets/           → CSS, JS, fonts, images
├── config/           → Theme settings schema & data
├── layout/           → theme.liquid, password.liquid
├── locales/          → Translation files (en, fr)
├── sections/         → Shopify sections (header, footer, main-*, ...)
├── snippets/         → Reusable Liquid snippets
└── templates/        → JSON templates (Shopify 2.0)
```

## Development

```bash
# Install Shopify CLI
npm install -g @shopify/cli @shopify/theme

# Dev server
shopify theme dev --store=your-store.myshopify.com

# Push to store
shopify theme push
```
