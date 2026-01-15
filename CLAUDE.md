# CLAUDE.md

This file provides context for Claude Code when working on this project.

## Project Overview

Vulktech website - a landing page for a product development company focused on shipping ideas fast.

## Tech Stack

- **Framework**: Astro 5.x
- **Styling**: Tailwind CSS 3.x with custom configuration
- **Fonts**: Instrument Sans (body), Syne (display headings)
- **Package Manager**: pnpm

## Commands

```bash
pnpm dev      # Start development server (http://localhost:4321)
pnpm build    # Build for production
pnpm preview  # Preview production build
```

## Project Structure

```
src/
├── components/     # Reusable Astro components
├── layouts/        # Page layouts (Layout.astro)
├── pages/          # Route pages (file-based routing)
└── styles/         # Global CSS (global.css)
public/             # Static assets
```

## Design System

### Brand Colors (Tailwind classes)

- `vulk-dark` (#050508) - Primary background
- `vulk-darker` (#020203) - Darker variant
- `vulk-blue` (#0037fb) - Primary accent
- `vulk-cyan` (#00d4ff) - Secondary accent
- `vulk-graphite` (#6b7280) - Muted text
- `vulk-muted` (#9ca3af) - Secondary muted text

### Typography

- Body text: `font-sans` (Instrument Sans)
- Display headings: `font-display` (Syne)

### Custom CSS Classes

Located in `src/styles/global.css`:
- `.gradient-text` - Blue to cyan gradient text
- `.glow-border` - Hover glow effect for buttons
- `.hero-bg` - Dark background with subtle radial gradient
- `.bg-noise` - Noise texture overlay
- Animation utilities: `.animate-in`, `.animate-in-scale`, `.animate-in-fade`
- Delay utilities: `.delay-1` through `.delay-6`

## Key Files

- `astro.config.mjs` - Astro configuration with Tailwind integration
- `tailwind.config.cjs` - Custom colors, fonts, and animations
- `src/layouts/Layout.astro` - Base HTML layout with font loading
- `src/pages/index.astro` - Main landing page
