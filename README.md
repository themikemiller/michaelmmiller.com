# Mike Miller Resume Site

**Live URL:** https://michaelmmiller.com
**Tech:** Single-file HTML + inline CSS/JS + GSAP from CDN
**Fonts:** Outfit (headings) + Inter (body) + JetBrains Mono (data) via Google Fonts
**Built by:** [Mike Miller Development](https://www.mikemillerdevelopment.com)

---

## File Structure

```
├── index.html              ← The entire site (HTML + CSS + JS)
├── favicon.svg             ← MM. favicon (blue accent)
├── mike-miller-senior-scrum-master.JPG ← Social sharing preview image
├── CONTENT.md              ← ⚠️ SOURCE OF TRUTH for all text content
├── CHANGELOG.md            ← Version history
├── README.md               ← This file
├── robots.txt              ← SEO crawl rules
├── sitemap.xml             ← Sitemap
├── 404.html                ← Error page
└── .gitignore              ← Keeps junk files out of git
```

---

## Content Workflow

**CONTENT.md is the single source of truth for all copy on this site.**

When making changes:

1. **Design/style changes only?** → Edit `index.html` directly. Don't touch the words.
2. **Content/copy changes?** → Update `CONTENT.md` FIRST, then update `index.html` to match.
3. **Full redesign?** → Read `CONTENT.md` for all copy. Build new design around it. Never rewrite copy during a redesign.

---

## Branches

| Branch | Purpose |
|--------|---------|
| `main` | Live production site |
| `archive/v1-original` | Original site before v4.0 redesign (kept for reference) |

---

## JavaScript Features (v4.x)

- **GSAP 3 + ScrollTrigger** — Gentle scroll-triggered fade-up animations
- **Animated stat counters** — Numbers roll up when visible
- **Dark/light theme toggle** — Saves preference, detects OS setting
- **Scroll progress bar** — Blue-to-teal gradient at top
- **Active nav highlighting** — Current section highlighted in nav
- **Mouse glow** — Radial gradient follows cursor (dark theme only)
- **Smooth scroll** — Nav links offset for fixed header
- **Email obfuscation** — Contact email assembled via JS to prevent spam scraping

---

## External Dependencies

- Google Fonts (Outfit, Inter, JetBrains Mono)
- GSAP 3.12.5 + ScrollTrigger (cdnjs CDN)
- Google Analytics (GA4: G-NGP153D8WS)
