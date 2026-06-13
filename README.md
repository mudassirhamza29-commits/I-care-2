# I-Care Services ICC

A production-grade, fully responsive website for **I-Care Services ICC** — a community-based support hub in Stanmore, London.

## Tech Stack

- **Next.js 15** with App Router
- **TypeScript** (strict mode)
- **Tailwind CSS v4** (CSS-first config)
- **Framer Motion v11** for animations
- **Lucide React** for icons
- **React Hook Form + Zod** for form validation

## Pages (16 routes)

| Route | Description |
|-------|-------------|
| `/` | Home — Hero, Services Grid, Stats, Testimonials, CTA |
| `/about` | About Us — Story, Values, Approach, Delivery Types |
| `/services` | Services Overview — 7 service cards, How It Works |
| `/services/health-social-care` | Health & Social Care detail page |
| `/services/welfare-support` | Welfare Support detail page |
| `/services/housing-support` | Housing Support detail page |
| `/services/general-health` | General Health detail page |
| `/services/mental-health` | Mental Health detail page (sensitive) |
| `/services/family-support` | Family Support detail page (sensitive) |
| `/services/sexual-health` | Sexual Health detail page (sensitive) |
| `/get-support` | Self-referral form, contact options, crisis info |
| `/for-professionals` | Professional referral form, partnership info |
| `/resources` | Downloadable guides, external signposting |
| `/contact` | Contact form, map, opening hours |
| `/news` | Blog grid, featured post, newsletter signup |
| `/team` | Team member cards, join the team CTA |

## Getting Started

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Start production server
npm start
```

The development server runs on `http://localhost:3000` by default.

## Project Structure

```
src/
├── app/(main)/           # All page routes
├── components/
│   ├── forms/            # React Hook Form components
│   ├── home/             # Home page sections
│   ├── layout/           # Navbar, Footer, PageTransition
│   ├── resources/        # Resource filtering
│   ├── shared/           # PageHero, ServicePageTemplate, ServiceCard
│   └── ui/               # Button, Card, Badge, AnimatedSection, etc.
├── hooks/                # useScrollAnimation, useCountUp
├── lib/                  # animations.ts, constants.ts, utils.ts
└── types/                # TypeScript interfaces
```

## Design System

| Token | Value |
|-------|-------|
| Navy | `#2E3250` |
| Orange | `#F4845F` |
| Coral | `#E8574A` |
| Purple | `#5B3FA6` |
| Cream | `#FAF8F4` |

## Features

- **Page transitions** — Fade + slide animations on every route change
- **Scroll animations** — Elements animate in as they enter the viewport
- **Responsive design** — Mobile-first, works on all screen sizes
- **Accessibility** — WCAG 2.1 AA compliant, focus-visible rings, reduced motion support
- **Forms** — Self-referral, professional referral, and contact forms with Zod validation
- **FAQ accordions** — Animated open/close on service pages
- **Resource filtering** — Category tabs with animated layout transitions

## Contact

- **Address:** 48 Bellamy Drive, Stanmore, London, HA7 2DB
- **Phone:** 020 8040 0433
- **Email:** i-caree@outlook.com
- **Registration:** 16861714 (Company Limited by Guarantee)
