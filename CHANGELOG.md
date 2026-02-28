# Changelog — Mike Miller Resume Site

## [3.1] — 2026-02-28

### UX & Spacing
- **Tighter section spacing**: Reduced section padding from 5.5rem to 3.5rem (2.5rem mobile). Less wasted scroll between sections.
- **Nav shrink on scroll**: Nav bar subtly compresses padding when user scrolls down.

### Light Theme Overhaul
- **Softer palette**: Light mode background shifted from harsh white to `#eef1f5` with SVG noise texture overlay.
- **Nav stays dark**: Nav bar keeps its dark appearance in light mode (deliberate design choice, not a bug).
- **Moon icon**: Theme toggle now swaps between sun and moon SVG icons.

### Nav Branding
- **MM. — Mike Miller**: Updated nav logo to MMD-style branding with gradient dot and em-dash separator.

### "Clearing the Fog" Concept
- **Fog overlay**: Semi-transparent mask layer that "clears" around the cursor, tying the mouse glow into the brand message ("I clear the fog so your teams can deliver").
- **Enhanced mouse glow**: Larger, softer glow (400px, blur 60px) that works with the fog overlay.

### New JS Interactivity
- **Magnetic buttons**: CTA buttons subtly pull toward the cursor on hover.
- **Gradient border glow**: Cards reveal a blue-to-teal gradient border on hover.
- **Breathing box shadows**: Cards pulse with a subtle glow when in viewport.
- **Floating cert badges**: Cert badges gently float up/down when visible.
- **Tool pills stagger**: Tool & methodology pills cascade in with staggered delays.
- **Company logo parallax**: Social proof logos subtly wave on scroll.
- **Section heading reveals**: Section headers animate in with a slide-up reveal.
- **Text shimmer**: Hero gradient text has a subtle shimmer animation.

### Technical
- File grew from ~1380 lines to ~1695 lines (new CSS animations + enhanced JS).
- All original content preserved exactly.

---

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
