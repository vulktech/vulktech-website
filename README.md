# Vulktech Website

Landing page for Vulktech - a product development company focused on shipping ideas fast.

## Tech Stack

- [Astro](https://astro.build/) 5.x
- [Tailwind CSS](https://tailwindcss.com/) 3.x
- Inter font (Google Fonts)

## Features

- Responsive dark-themed design
- Custom brand colors (vulk-dark, vulk-blue, vulk-graphite, vulk-cyan)
- Social media links (X, LinkedIn, Instagram, Linktree)
- Contact CTA linking to email
- Component-based architecture

## Project Structure

```
src/
├── components/     # Reusable Astro components
│   ├── StatusBadge.astro
│   └── SocialLinks.astro
├── layouts/        # Page layouts
│   └── Layout.astro
├── pages/          # Route pages
│   └── index.astro
└── styles/         # Global styles
    └── global.css
public/             # Static assets
```

## Getting Started

```bash
# Install dependencies
pnpm install

# Start development server
pnpm dev

# Build for production
pnpm build

# Preview production build
pnpm preview
```