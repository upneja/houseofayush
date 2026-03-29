# House of Ayush

A collection of luxury website designs and fashion brand identity systems — each built as a standalone HTML/CSS piece, exploring radically different design aesthetics from secret society occultism to Bauhaus modernism to quiet luxury retreat.

---

## What Is This

This repository is a design exploration portfolio. The same brief — a luxury gathering / event — is executed across 10+ completely different visual languages. Each collection includes a working responsive landing page, a documented color system, typography specifications, and component design notes.

There are two parallel series:

- **campnejaclaude** — Designs built with Claude Sonnet, focusing on expressive layout and atmosphere
- **campnejacodex** — Designs built with Claude Opus / Codex, with richer component libraries and hero concept variations
- **highfashion** — Standalone fashion house brand identity system (Dior / Celine reference aesthetic)
- **secretsociety** / **noble** / **bauhaus** — Earlier standalone explorations

---

## Design Collections

### 01 — Secret Society
Obsidian and ceremonial gold. Cormorant Garamond at wide tracking. Rotating sigil on load, gold line dividers, dark cards with hover glow. Occult-lite mysticism for an exclusive, ritualistic feel.

### 02 — Fantasy Noble House
Medieval heraldry brought into a modern editorial grid. Royal navy and forest green, heraldic gold, parchment backgrounds. House crest with shield, pine tree, and crown. Banner unfurl animations. Reference: *Game of Thrones* meets luxury estate.

### 03 — High Fashion Editorial
Pure black and white maximum contrast. Bodoni display type. Magazine asymmetric grid, generous negative space. Reference: Dior, Celine, Saint Laurent.

### 04 — Bauhaus Modernist
Primary color blocking (Bauhaus red `#E63946`, blue `#1D3557`, yellow `#F1C453`). Futura for all type. 12-column Swiss grid. Geometric circles, triangles, rectangles as decorative punctuation. Linear animations, no easing curves.

### 05 — Cinematic Universe
Desert sand meets midnight blue. Metallic gradient headlines. Widescreen 16:9 section proportions, full-bleed photography with heavy vignettes. Reference: *Dune* / James Bond title sequences.

### 06 — Mystical Forest Cult
Dark forest blacks lit by bioluminescent neon green and teal. Pulsing glow animations, particle fireflies, Nordic rune symbols as section markers. Reference: Avatar bioluminescence, fantasy forest worlds.

### 07 — Cabin Outdoor Brand
Forest greens and earth tones (terracotta, sandstone). REI / Patagonia catalog aesthetic. Topographic line patterns, badge/patch elements, trail marker navigation. Vintage outdoor poster feel.

### 08 — Tech Startup
Glassmorphism with deep purple-blue base and neon cyan/magenta accents. Frosted glass panels using `backdrop-filter: blur`. Space Grotesk type. Floating UI, gradient borders, neon hover glow.

### 09 — Festival Brand
Sunset gradient system (pink → orange → yellow). Fredoka rounded typography. Sticker-scattered layout, confetti particle effects, playful asymmetric composition. Reference: Coachella-era festival branding.

### 10 — Luxury Travel
Aman / Soho House register. Warm neutrals — sand, beige, taupe, sage. Maximum whitespace, soft shadows, linen texture. Understated refinement where nothing shouts. Reference: Quiet luxury hotel digital identity.

---

## House of Ayush — Fashion Identity

The `highfashion/` directory contains a standalone brand identity system for a luxury fashion house:

- **Wordmark** — Stacked "HOUSE OF / AYUSH" in Playfair Display, ultra-wide tracking, SVG
- **Color system** — Monochromatic foundation (`#0a0a0a` → `#fafafa`) with warm taupe/cognac `#8b7355` accent
- **Material textures** — Pure CSS: embossed leather, silk jacquard weave, precision stitching
- **Editorial layouts** — Asymmetric grid, quote-driven sections, studio photography aesthetic using only CSS shadows

---

## Tech

- Vanilla HTML and CSS — no frameworks, no build step
- Google Fonts CDN for typography
- CSS custom properties for complete design token systems per collection
- Responsive at 375 / 768 / 1024 / 1440px breakpoints
- All animations in pure CSS (transitions, keyframes, `backdrop-filter`)

---

## File Structure

```
houseofayush/
├── campnejaclaude/          # 10 designs — Claude Sonnet series
│   ├── 01-secret-society/
│   │   ├── layout.html      # Complete responsive landing page
│   │   ├── palette.json     # Full color token system
│   │   ├── typography.md    # Type scale and font specs
│   │   ├── design-notes.md  # Design direction and rationale
│   │   ├── components/      # Reusable component HTML
│   │   └── hero-concepts/   # Hero variation briefs
│   ├── 02-fantasy-house/ … 10-luxury-travel/
│   └── campneja-deploy/     # Production-ready deploy build
├── campnejacodex/           # 10 designs — Codex series (richer docs)
│   └── 01-secret-society/ … 10-luxury-travel/
├── highfashion/             # Fashion brand identity system
│   ├── index.html
│   ├── styles.css
│   └── logo.svg
├── secretsociety/           # Standalone secret society exploration
├── noble/                   # Standalone noble heraldry exploration
└── bauhaus/                 # Standalone Bauhaus exploration
```

---

## Viewing

No install required. Open any `layout.html` or `index.html` directly in a browser:

```
open campnejaclaude/01-secret-society/layout.html
open highfashion/index.html
open secretsociety/index.html
```

All assets are self-contained or loaded from CDN.
