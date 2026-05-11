# CLAUDE.md

## Objective

Build a custom mobile-first artist website for Matt Hollis.

The site must:

- Prioritize portrait-oriented layouts.
- Behave like a native mobile application.
- Present artwork images with full-screen viewing, swipe navigation, captions, and pinch-to-zoom.
- Support multiple views of sculptures.
- Maintain excellent accessibility and performance.
- Be structured for later addition of hand-drawn SVG graphics and subtle animation.

## Development Principles

1. Mobile-first.
2. File-based content; no CMS initially.
3. Accessibility by default.
4. Progressive enhancement.
5. Small, verifiable implementation slices.
6. Production-ready code.

## Required Routes

- /
- /gallery
- /news
- /timeline
- /studio
- /contact

## Verification Commands

- npm run lint
- npx tsc --noEmit
- npm run build

## Primary Libraries

- Next.js
- TypeScript
- Tailwind CSS
- PhotoSwipe
- Optional Framer Motion

Read all files in `/docs` before beginning implementation.
