# PMP Performance — Salla Theme

Independent custom Twilight theme for the PMP Performance Salla store.

## Design

- Black, white, and PMP red visual system
- Desktop and mobile layouts matched to the approved preview
- Custom header, home page, product presentation, workshop form, and footer
- Arabic and English content while preserving the approved left-to-right layout

## Salla integration

The theme uses native Salla components for:

- Search
- Main navigation
- Account and localization
- Cart
- Live products, prices, stock, and add-to-cart actions
- Payments, trust badges, contacts, and social links

## Development

Requirements:

- Node.js 22.18+ or 24.11+
- pnpm

```bash
pnpm install
pnpm run development
pnpm run production
```

Production assets are generated in `public/`.

## Publishing

Connect this repository to a private theme in the Salla Partners Portal, then use Salla CLI or the portal workflow to preview and publish it to the PMP Performance store.

This project uses Salla's official Twilight starter architecture and is maintained as a separate PMP Performance theme.
