# Changelog — Mike Miller Resume Site

## [2.0] — 2026-02-28

### Design Overhaul
- **Color scheme**: Replaced single blue accent with blue-to-teal gradient system (inspired by MMD). Background shifted from `#0f1117` to deeper navy `#0b0f1a`. New token system with `--blue`, `--teal`, `--green`, `--gold` accents.
- **Typography**: Swapped fonts from Source Serif 4 / Plus Jakarta Sans to **Outfit** (headings) + **Inter** (body) + **JetBrains Mono** (data/labels). Cleaner, more modern, and highly readable.
- **Cert badges**: Hybrid approach — MMD-style gradient text badges (colored rectangles with abbreviations) arranged in MMRS card layout with full cert name + issuer. Color-coded by org: blue (Scrum Alliance), green (SAFe), orange (ICAgile), indigo (LeSS).
- **Hero section**: Dropped profile photo. Now text-forward with gradient headline, status tag, and dual CTAs — inspired by MMD's cleaner hero.
- **Subtle grid background**: Added faint CSS grid lines behind all content for depth.
- **Card hover effects**: Added blue-to-teal gradient top-border reveal on approach cards and builder note.
- **Animations**: Kept smooth scroll-reveal fade-ups, added staggered hero entrance animations.

### Content Updates
- **Metrics**: Updated $1.7M to $1.4M (accurate figure). Changed "PI attendees" to "Teams of people".
- **All original sections preserved**: Approach, Differentiators, Track Record (with full 8-position timeline), Speaking, Builder Note, Credentials, Tools & Methodologies, CTA.

### Structure
- **Nav**: Kept "Mike Miller" text branding (no monogram).
- **CTA**: Kept Email + LinkedIn buttons.
- **Client list**: Unchanged (Google, SAIC, Midmark, 84.51°, GE, AtriCure, Speedway, Winsupply).
- **Certs shown twice**: Once near top (social proof position, like MMD) and once in Credentials section (for resume context).

### Technical
- Added versioning with git tags (v1.0 = pre-redesign, v2.0 = this release).
- Maintained all GA4 analytics tracking (section views, scroll depth, time on page, CTA clicks).
- Maintained all structured data (Schema.org Person + ProfessionalService).
- Single HTML file architecture preserved. No external dependencies beyond Google Fonts.

---

## [1.0] — 2026-02-28 (tagged retroactively)

### Initial Release
- Original resume site with dark theme, single blue accent, Source Serif 4 + Plus Jakarta Sans fonts, SVG cert icons, profile photo hero.
