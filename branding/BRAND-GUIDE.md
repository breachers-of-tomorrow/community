# Brand Guide — Breachers of Tomorrow

> **Status:** Initial extraction from breacher.net CSS — subject to community input
> **Last updated:** 2026-03-12

This document captures the existing visual identity from [breacher.net](https://breacher.net). The current theme is called **"Cryoarchive"** — a dark sci-fi terminal aesthetic inspired by the Marathon ARG.

> **Note:** The community branding will likely evolve. There may be a community event to collaboratively decide on colors, logo, and identity. This document captures *what exists today* as a starting point.

---

## Color Palette

### Core Colors

| Name | Hex | RGB | Usage |
|------|-----|-----|-------|
| **Background** | `#030a0f` | `3, 10, 15` | Page background — near-black with blue tint |
| **Panel** | `#060f17` | `6, 15, 23` | Card/panel backgrounds — slightly lighter dark |
| **Border** | `#0a3a4a` | `10, 58, 74` | Panel borders, dividers — dark teal |
| **Accent (Cyan)** | `#00d4ff` | `0, 212, 255` | Primary accent — headings, links, glows, interactive elements |
| **Accent 2 (Green)** | `#00ff9d` | `0, 255, 157` | Secondary accent — status indicators, arrows, emphasis |
| **Warning (Orange)** | `#ff6b35` | `255, 107, 53` | Warning states |
| **Danger (Red)** | `#ff2244` | `255, 34, 68` | Kill count, alerts, error states |
| **Text** | `#7ecfdf` | `126, 207, 223` | Main body text — light teal |
| **Dim** | `#2a5a6a` | `42, 90, 106` | Secondary/meta text — muted teal |

### Glow Effects

The cryoarchive theme uses subtle glow effects on text and boxes:

| Effect | CSS | Usage |
|--------|-----|-------|
| Accent glow | `text-shadow: 0 0 10px rgba(0, 212, 255, 0.4)` | Headings, active nav items |
| Accent2 glow | `text-shadow: 0 0 10px rgba(0, 255, 157, 0.4)` | Secondary highlights |
| Danger glow | `text-shadow: 0 0 15px rgba(255, 34, 68, 0.5)` | Kill counter, alerts |
| Box accent glow | `box-shadow: 0 0 10px rgba(0, 212, 255, 0.4)` | Active panels |
| Box accent2 glow | `box-shadow: 0 0 10px rgba(0, 255, 157, 0.4)` | Status panels |

---

## Typography

### Fonts

| Font | Family | Usage | Source |
|------|--------|-------|--------|
| **Orbitron** | Sans-serif display | Headings, section titles, nav labels, status readouts | [Google Fonts](https://fonts.google.com/specimen/Orbitron) |
| **Share Tech Mono** | Monospace | Body text, data, general content | [Google Fonts](https://fonts.google.com/specimen/Share+Tech+Mono) |

### Usage Rules

- **Orbitron** is for display purposes only — headings, labels, navigation, status readouts
  - Always uppercase with wide letter-spacing (`tracking-[3px]` to `tracking-[6px]`)
  - Often paired with glow effects
  - Small sizes (0.6rem–0.7rem for labels, larger for hero text)
- **Share Tech Mono** is the body font — all regular text, descriptions, data
  - Monospace gives the terminal/hacker feel
  - Used at normal sizes without forced uppercase

---

## Visual Patterns

### Panel Style

The signature UI element is the "cryo-panel":
- Dark background (`#060f17`)
- Teal border (`#0a3a4a`)
- Subtle gradient line at the top (left-to-right fade from border color to transparent)
- Used for every card, data display, and content block

### Section Titles

- Orbitron font, 0.7rem, letter-spacing 6px
- Dim teal color (`#2a5a6a`)
- Bottom border separator
- Always uppercase

### Animations

- **Pulse glow** — Slow 2s opacity pulse (1 → 0.3 → 1) for status indicators
- **Blink** — 1s blink (1 → 0.2 → 1) for active/live indicators

---

## Brand Voice

> **To be defined** — This section should capture how the community sounds in official communications.

Starting observations:
- **Tone:** Sci-fi themed but not cringe. Functional over theatrical.
- **Style:** Terminal/hacker aesthetic with in-universe ARG language ("breach protocol", "sectors", "stabilization")
- **Formality:** Casual-professional. We're a gaming community, not a corporation.

---

## Logo & Wordmark

> **Status:** Does not exist yet — needs design

Current landing page uses text-only treatment:
```
BREACHERS OF
    TOMORROW
```
- "BREACHERS OF" in cyan (`#00d4ff`) with glow
- "TOMORROW" in green (`#00ff9d`) with glow
- Orbitron font, bold/black weight

**Needed:**
- [ ] Logo/icon (for Discord avatar, GitHub org avatar, favicon)
- [ ] Wordmark (text-based logotype)
- [ ] Combined mark (logo + wordmark)
- [ ] Variants: full color, monochrome, light background, dark background
- [ ] SVG source files + PNG exports at standard sizes

---

## Asset Inventory

| Asset | Status | Location |
|-------|--------|----------|
| Logo | ❌ Needs design | — |
| Discord server icon | ❌ Needs design | Discord settings |
| Discord server banner | ❌ Needs design | Discord settings |
| GitHub org avatar | ❌ Needs design | GitHub org settings |
| Favicon | ❌ Needs design | `breacher-net/public/` |
| OG image (social preview) | ❌ Needs design | `breacher-net/public/` |
| Social media templates | ❌ Needs design | `branding/templates/` |

---

## Applying the Theme

### Discord

- Server icon and banner should use the cyan/dark palette
- Role colors should follow the palette (cyan for Keepers, green for contributors, teal for members)
- Bot embeds should use `#00d4ff` accent color

### Wiki (future)

- Wiki.js supports custom CSS — apply cryoarchive theme
- Match panel styles, fonts, and colors from breacher.net

### Social Media

- Use dark backgrounds with cyan/green accents
- Orbitron for headlines, Share Tech Mono for body
- Glow effects sparingly — they work on screens but not in print

---

*This brand guide will evolve as the community develops its visual identity. Contributions welcome via the [Ideas discussion](https://github.com/breachers-of-tomorrow/community/discussions/categories/ideas).*
