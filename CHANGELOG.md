# Changelog — Mike Miller Resume Site

## [4.1] — 2026-03-04

### UX Polish
- **Softer animations**: Reduced scroll animation distances (12px vs 30px), gentler easing (`power2.out`), slower stagger.
- **Consistent fade-up**: Timeline items now fade up like everything else (removed sideways snap).
- **Softer hovers**: Cards lift 2px with lighter shadow instead of 3px.

### Layout Fixes
- **Nav alignment**: Fixed nav links drifting left when theme toggle was grouped with hamburger.
- **Theme toggle position**: Stays right-aligned next to hamburger on mobile (wrapped in `.nav-right` group).

### New Content
- **Quick Facts strip**: Green-checkmark row above Contact — US Citizen, Remote/Hybrid/Onsite, Travel, 8+ Years.

---

## [4.0] — 2026-03-04

### Bug Fixes
- **Missing `$` on ~$1.7M stat**: Dollar sign was left out of the counter markup.
- **Social sharing images**: Added `og:image` and `twitter:image` meta tags for LinkedIn/Twitter previews.
- **JetBrains Mono font**: Was referenced in CSS but never loaded from Google Fonts.
- **Theme toggle broken**: Now saves preference to localStorage, changes icon (sun/moon), disables mouse glow in light mode.
- **Light mode nav bar stuck dark**: CSS selectors used `body.light-theme` but class was on `<html>`. Fixed to `.light-theme`.
- **Broken GSAP animation**: Removed `gsap.to('.hero::after')` — GSAP can't animate pseudo-elements.
- **Email link quirks**: Rebuilt with data attributes + JS so click and right-click both work.
- **Structured data**: Added `worksFor: SAIC` to Person schema.
- **GA comment**: Removed misleading "replace with your real ID" note.

### New Content
- **Testimonials section**: 5 LinkedIn recommendations with featured card layout (Tracey Valentine featured full-width).

### Design
- **Light mode polish**: Card shadows, button glow, refined color palette, cert badge contrast.
- **Removed fake clickable cursors**: Cards no longer show pointer cursor since they aren't links.
- **Removed 3D tilt effect**: Replaced wobbly card rotation with clean lift-on-hover.
- **404 page rebranded**: Now uses same fonts (Inter/Outfit) and colors as main site.

### Infrastructure
- **Dark mode default**: Always starts dark. Removed OS preference detection.
- **Footer credit**: "Built by Mike Miller Development" with link to mikemillerdevelopment.com.

---

## [3.1] — 2026-02-28

### UX & Spacing
- Tighter section spacing (3.5rem vs 5.5rem).
- Nav shrink on scroll.

### Light Theme Overhaul
- Softer light mode palette.
- Moon icon for theme toggle.

### New JS Interactivity
- Fog overlay, magnetic buttons, gradient border glow, breathing shadows, floating cert badges, tool pill stagger, company logo parallax, text shimmer.

---

## [3.0] — 2026-02-28

### Premium JavaScript Enhancements
- GSAP 3 + ScrollTrigger for all scroll animations.
- Animated stat counters, hero typing animation.
- Dark/light theme toggle, scroll progress bar, active nav highlighting.
- 3D tilt hover effects, mouse glow cursor, smooth scroll offset.

### Documentation
- Created CONTENT.md (single source of truth for copy).
- Created README.md.

---

## [2.1] — 2026-02-28
- Restored original copy accidentally rewritten in v2.0.
- Added blue MM. favicon.

---

## [2.0] — 2026-02-28
- Full design overhaul: blue-teal gradient palette, Outfit + Inter + JetBrains Mono fonts, hybrid cert badges, text-forward hero.

---

## [1.0] — 2026-02-28
- Original site. Dark theme, single blue accent, Source Serif 4 + Plus Jakarta Sans, SVG cert icons, profile photo hero.
