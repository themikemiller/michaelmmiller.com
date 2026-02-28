# Mike Miller Resume Site

**Live URL:** https://michaelmmiller.com
**Tech:** Single-file HTML + inline CSS/JS + GSAP from CDN
**Fonts:** Outfit (headings) + Inter (body) + JetBrains Mono (data) via Google Fonts

---

## File Structure

```
├── index.html      ← The entire site (HTML + CSS + JS)
├── favicon.svg     ← MM. favicon (blue accent)
├── CONTENT.md      ← ⚠️ SOURCE OF TRUTH for all text content
├── CHANGELOG.md    ← Version history
├── README.md       ← This file
├── robots.txt      ← SEO crawl rules
├── sitemap.xml     ← Sitemap
└── 404.html        ← Error page
```

---

## ⚠️ Content Workflow

**CONTENT.md is the single source of truth for all copy on this site.**

When making changes:

1. **Design/style changes only?** → Edit `index.html` directly. Don't touch the words.
2. **Content/copy changes?** → Update `CONTENT.md` FIRST, then update `index.html` to match.
3. **Full redesign?** → Read `CONTENT.md` for all copy. Build new design around it. Never rewrite copy during a redesign.

This prevents accidentally changing Mike's carefully written content during style updates.

---

## Versioning

This site uses **git tags** for versioning:

| Tag  | Description |
|------|-------------|
| v1.0 | Original site (pre-redesign) |
| v2.0 | Design overhaul (blue-teal palette, new fonts, MMD-style certs) |
| v2.1 | Content fix (restored original copy) + favicon |
| v3.0 | Premium JS enhancements (GSAP, counters, theme toggle, tilt, glow) |

**To view a previous version:**
```bash
git checkout v1.0 -- index.html   # Restore original
git checkout v3.0 -- index.html   # Back to latest
```

**To create a new version after changes:**
```bash
git add -A
git commit -m "v3.1 — Description of changes"
git tag -a v3.1 -m "v3.1 - Short description"
```

---

## JavaScript Features (v3.0+)

- **GSAP 3 + ScrollTrigger** — Scroll-triggered animations throughout
- **Animated stat counters** — Numbers roll up when visible
- **Hero typing effect** — "deliver" types out with cursor blink
- **Dark/light theme toggle** — Sun/moon button in nav
- **Scroll progress bar** — Blue-to-teal gradient at top
- **Active nav highlighting** — Current section highlighted in nav
- **3D card tilt** — Subtle perspective shift on card hover
- **Mouse glow** — Radial gradient follows cursor on dark theme
- **Smooth scroll** — Nav links offset for fixed header

---

## External Dependencies

- Google Fonts (Outfit, Inter, JetBrains Mono)
- GSAP 3.12.5 + ScrollTrigger (cdnjs CDN)
- Google Analytics (GA4: G-NGP153D8WS)
