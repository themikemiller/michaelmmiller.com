# Changelog — Mike Miller Resume Site

## [3.0] — 2026-02-28

### Premium JavaScript Enhancements
- **GSAP 3 + ScrollTrigger**: Replaced IntersectionObserver with GSAP for all scroll animations. Staggered card reveals, sliding timeline items, parallax on hero background glow.
- **Animated stat counters**: Stats (39%, ~$1.7M, 100+, 12%) count up from 0 when scrolling into view.
- **Hero typing animation**: The word "deliver" types out character by character with cursor blink.
- **Dark/light theme toggle**: Sun/moon toggle in nav. Full light theme with white backgrounds, dark text, blue accents preserved. Smooth transitions.
- **Scroll progress bar**: 3px blue-to-teal gradient bar at the very top showing scroll progress.
- **Active nav highlighting**: Current section's nav link highlights as user scrolls.
- **3D tilt hover effects**: Approach, diff, speak, and cert cards tilt subtly on mouse hover (3-4° max, perspective effect).
- **Mouse glow cursor effect**: Subtle radial gradient glow follows the mouse across the dark background.
- **Smooth scroll offset**: Nav links scroll to sections with offset for fixed nav height.

### Documentation
- **CONTENT.md**: Created single source of truth for all site copy. Any content changes should be made here first, then reflected in index.html.
- **README.md**: Added developer workflow documentation.

### Technical
- Added GSAP 3.12.5 + ScrollTrigger from cdnjs CDN.
- All original content preserved exactly (verified against CONTENT.md).
- File grew from ~850 lines to ~1380 lines (JS enhancements).

---

## [2.1] — 2026-02-28

### Content Fix
- Restored all original copy that was accidentally rewritten in v2.0.
- Added blue `MM.` favicon matching MMD's style but with blue accent instead of purple.

---

## [2.0] — 2026-02-28

### Design Overhaul
- **Color scheme**: Replaced single blue accent with blue-to-teal gradient system (inspired by MMD). Background shifted from `#0f1117` to deeper navy `#0b0f1a`. New token system with `--blue`, `--teal`, `--green`, `--gold` accents.
- **Typography**: Swapped fonts from Source Serif 4 / Plus Jakarta Sans to **Outfit** (headings) + **Inter** (body) + **JetBrains Mono** (data/labels).
- **Cert badges**: Hybrid approach — MMD-style gradient text badges arranged in MMRS card layout with full cert name + issuer. Color-coded by org.
- **Hero section**: Dropped profile photo. Text-forward with gradient headline and dual CTAs.
- **Grid background, card hover effects, staggered animations.**

---

## [1.0] — 2026-02-28 (tagged retroactively)

### Initial Release
- Original resume site with dark theme, single blue accent, Source Serif 4 + Plus Jakarta Sans fonts, SVG cert icons, profile photo hero.
