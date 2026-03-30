# Brand Guide — Breachers of Tomorrow

> **Version:** 2.0 — Revised palette
> **Last updated:** 2026-03-30

The visual identity for [breacher.net](https://breacher.net) and all Breachers of Tomorrow assets. The theme is called **"Cryoarchive"** — a dark sci-fi terminal aesthetic inspired by the Marathon ARG.

---

## Color Palette (v2 Revised)

### Core Colors

| Token | Name | Hex | CSS Variable | Usage |
|-------|------|-----|-------------|-------|
| **Primary** | Breacher Blue | `#038ADF` | `--color-cryo-accent` | Primary accent — headings, links, glows, interactive elements |
| **Secondary** | Breacher Cyan | `#00D4EB` | `--color-cryo-accent2` | Secondary accent — system responses, highlights |
| **Tertiary** | Signal Mint | `#00FF9D` | `--color-mint` | Tertiary accent — success states, status indicators (use sparingly) |
| **Warning** | Amber | `#FFAA00` | `--color-cryo-warn` | Warning states |
| **Danger** | Danger Red | `#FF3344` | `--color-cryo-danger` | Kill count, alerts, error states |

### Surface Colors

| Token | Name | Hex | CSS Variable | Usage |
|-------|------|-----|-------------|-------|
| **Background** | Deep Teal | `#031A22` | `--color-cryo-bg` | Page background |
| **Panel** | Dark Teal | `#0A2A35` | `--color-cryo-panel` | Card/panel backgrounds |
| **Card** | Elevated Teal | `#12384A` | `--color-void-card` | Elevated card backgrounds |
| **Border** | Teal Border | `#1A4660` | `--color-cryo-border` | Panel borders, dividers |

### Text Colors

| Token | Name | Hex | CSS Variable | Usage |
|-------|------|-----|-------------|-------|
| **Body** | Cool Teal | `#8AACB8` | `--color-cryo-text` | Main body text |
| **Dim** | Muted Teal | `#5A7A8A` | `--color-cryo-dim` | Secondary/meta text |
| **Heading** | Warm Light | `#E0DDD2` | `--color-text-heading` | Headings, emphasis |

### Glow Effects

The cryoarchive theme uses subtle glow effects on text and boxes:

| Effect | CSS | Usage |
|--------|-----|-------|
| Accent glow | `text-shadow: 0 0 10px rgba(3, 138, 223, 0.4)` | Headings, active nav items |
| Accent2 glow | `text-shadow: 0 0 10px rgba(0, 212, 235, 0.4)` | Secondary highlights |
| Mint glow | `text-shadow: 0 0 10px rgba(0, 255, 157, 0.4)` | Success, status |
| Warn glow | `text-shadow: 0 0 10px rgba(255, 170, 0, 0.4)` | Warning accents |
| Danger glow | `text-shadow: 0 0 15px rgba(255, 51, 68, 0.5)` | Kill counter, alerts |
| Box accent glow | `box-shadow: 0 0 10px rgba(3, 138, 223, 0.4)` | Active panels |
| Box accent2 glow | `box-shadow: 0 0 10px rgba(0, 212, 235, 0.4)` | Status panels |
| Box mint glow | `box-shadow: 0 0 10px rgba(0, 255, 157, 0.4)` | Success panels |

### Tailwind Utility Classes

When using the breacher-net codebase, use these utility classes instead of raw CSS:

| Class | Effect |
|-------|--------|
| `.glow-accent` | Text glow in Breacher Blue |
| `.glow-accent2` | Text glow in Breacher Cyan |
| `.glow-mint` | Text glow in Signal Mint |
| `.glow-warn` | Text glow in Amber |
| `.glow-danger` | Text glow in Danger Red |
| `.box-glow-accent` | Box glow in Breacher Blue |
| `.box-glow-accent2` | Box glow in Breacher Cyan |
| `.box-glow-mint` | Box glow in Signal Mint |

---

## Typography

### Fonts

| Font | Variable | Family | Usage | Source |
|------|----------|--------|-------|--------|
| **Space Grotesk** | `--font-display` | Sans-serif display | Headings, section titles, nav labels, status readouts | [Google Fonts](https://fonts.google.com/specimen/Space+Grotesk) |
| **JetBrains Mono** | `--font-mono` | Monospace | Body text, data, code, general content | [Google Fonts](https://fonts.google.com/specimen/JetBrains+Mono) |

### Usage Rules

- **Space Grotesk** is for display purposes — headings, labels, navigation, status readouts
  - Often paired with glow effects
  - Used for hero text, section headers, and display elements
  - Pairs well with uppercase treatment for terminal-style labels
- **JetBrains Mono** is the body font — all regular text, descriptions, data
  - Monospace gives the terminal/hacker feel
  - Used at normal sizes without forced uppercase
  - Better legibility than Share Tech Mono at small sizes

---

## Visual Patterns

### Panel Style

The signature UI element is the `.cryo-panel`:
- Dark background (`#0A2A35`)
- Teal border (`#1A4660`)
- Subtle gradient line at the top (left-to-right fade from border color to transparent)
- Used for every card, data display, and content block

### Section Titles

- Use the `.section-title` class
- Space Grotesk font
- Dim teal color (`#5A7A8A`)
- Bottom border separator
- Uppercase treatment for terminal-style headings

### Animations

- **Pulse glow** — Slow 2s opacity pulse (1 → 0.3 → 1) for status indicators
- **Blink** — 1s blink (1 → 0.2 → 1) for active/live indicators
- **Respect `prefers-reduced-motion`** — All animations must be disabled when the user has reduced motion enabled

---

## Brand Voice

See [MESSAGING.md](MESSAGING.md) for full brand voice guidelines. Summary:

- **In-universe but not cringe** — Use ARG terminology naturally ("breach protocol", "sectors", "stabilization"), not forced
- **Collaborative** — "We discovered" not "I found"
- **Approachable** — Experts welcome, never gatekeeping
- **Enthusiastic but grounded** — Excited about discoveries, skeptical about unconfirmed theories
- **Inclusive** — Assume the reader is new; don't assume prior knowledge without context

### Tone by Context

| Context | Tone |
|---------|------|
| Discord announcements | Clear, concise, slightly formal |
| Discord general chat | Casual, friendly, inclusive |
| GitHub Issues/PRs | Technical, constructive |
| GitHub Discussions | Thoughtful, longer-form |
| Wiki content | Neutral, factual, well-sourced |
| Social media | Energetic, visual, shareable |

---

## Logo & Wordmark

### Current Assets

| Asset | Status | Location |
|-------|--------|----------|
| Logo SVG (1000×1000) | ✅ | `assets/svg/BreacherLogo.svg` |
| Logo PSD (source) | ✅ | `assets/psd/Breach.psd` |
| Wiki logo SVG | ✅ | `assets/svg/BreacherWikiLogo.svg` |
| Favicon set | ✅ | `breacher-net/public/` (generated from logo) |
| OG image (1200×630) | ✅ | `breacher-net/public/og-image.png` |
| Apple touch icon (180×180) | ✅ | `breacher-net/public/apple-touch-icon.png` |
| PWA icons (192, 512) | ✅ | `breacher-net/public/` |

### Needed (Design Work)

- [ ] Exported logo variants: full-color-on-dark, monochrome-white, monochrome-dark, icon-only — see [community-ops #7](https://github.com/breachers-of-tomorrow/community-ops/issues/7)
- [ ] Wordmark SVG logotype (Space Grotesk) — see [community-ops #5](https://github.com/breachers-of-tomorrow/community-ops/issues/5)
- [ ] Social media templates — see [community-ops #4](https://github.com/breachers-of-tomorrow/community-ops/issues/4)

### Landing Page Treatment

```
BREACH//NET
```
- "BREACH//NET" in Breacher Blue (`#038ADF`) with glow
- Space Grotesk font, bold weight
- Logo mark displayed above hero title with accent glow

---

## Asset Inventory

| Asset | Status | Location |
|-------|--------|----------|
| Logo SVG | ✅ | `assets/svg/BreacherLogo.svg` |
| Logo PSD | ✅ | `assets/psd/Breach.psd` |
| Wiki logo SVG | ✅ | `assets/svg/BreacherWikiLogo.svg` |
| Favicon set | ✅ | Generated via `breacher-net/scripts/generate-assets.mjs` |
| OG image | ✅ | `breacher-net/public/og-image.png` |
| PWA icons | ✅ | `breacher-net/public/` |
| v2 palette preview | ✅ | `assets/breachers-revised-palette.html` |
| v2 palette swatch SVG | ✅ | `assets/breachers_revised_palette.svg` |
| Discord server icon | ✅ | Deployed to Discord |
| Logo variants (exports) | ❌ Needs design | `assets/logos/` |
| Wordmark | ❌ Needs design | `assets/logos/` |
| Social media templates | ❌ Needs design | `branding/templates/` |

---

## Applying the Theme

### Discord

- Server icon and banner use the cryoarchive dark palette
- Role colors follow the palette — see [COLOR-SYSTEM.md](https://github.com/breachers-of-tomorrow/community-ops/blob/main/strategy/discord-reorg/COLOR-SYSTEM.md) (private)
- Bot embeds should use Breacher Blue `#038ADF` accent color

### Wiki

- Wiki.js applies custom CSS matching the cryoarchive theme
- Panel styles, fonts (JetBrains Mono + Space Grotesk), and colors from breacher.net
- Custom sidebar toggle and scroll-to-top from `breacher-net/wiki-theme/`

### Social Media

- Use dark backgrounds (`#031A22`) with blue/cyan accents
- Space Grotesk for headlines, JetBrains Mono for body
- Glow effects sparingly — they work on screens but not in print

### Reference Files

| File | Purpose |
|------|---------|
| `breacher-net/src/app/globals.css` | Canonical CSS variables, base styles, glow utilities |
| `assets/breachers-revised-palette.html` | Interactive v2 palette preview |
| `assets/breachers_revised_palette.svg` | Swatch reference for designers |

---

*This brand guide reflects the v2 revised palette deployed on breacher.net. Contributions welcome via the [Ideas discussion](https://github.com/breachers-of-tomorrow/community/discussions/categories/ideas).*
