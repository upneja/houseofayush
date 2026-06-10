# Hero Concept: Variation 1 - Center Sigil

## Layout
**Full viewport height, centered composition**

```
┌─────────────────────────────────────────┐
│                                         │
│          [Dark Aerial Photo]            │
│       [Radial Vignette Overlay]        │
│                                         │
│            ○ ═══════ ○                  │
│         [Rotating Sigil]                │
│            ○ ═══════ ○                  │
│                                         │
│           CAMPNEJA                      │
│   A weekend where my worlds             │
│      collide in the woods.              │
│                                         │
│         — MAY 1–3, 2025 —               │
│                                         │
│      [RSVP on Partiful]                 │
│                                         │
└─────────────────────────────────────────┘
```

## Details

### Background
- Image: Aerial property shot
- Filter: brightness(0.3) saturate(0.85)
- Overlay: Radial gradient from transparent center to obsidian edges
- Vignette: Strong, creates focus on center

### Sigil
- Size: 120px diameter
- Border: 3px solid ceremonial gold
- Circle shape
- Rotating animation: 20s linear infinite
- Inner symbol: Geometric tree/mountain in gold line art
- Glow effect: 0 4px 20px rgba(212, 175, 55, 0.3)

### Typography
- Event name: Cormorant Garamond 4.5rem / 600
- Color: Ceremonial gold #D4AF37
- Text shadow: Subtle gold glow
- Tagline: Crimson Text 1.5rem / italic
- Color: Pale gold #EDD9A3
- Dates: JetBrains Mono 1rem
- Color: Ceremonial gold
- Letter spacing: 0.1em

### Dividers
- Width: 200px
- Height: 1px
- Gradient: transparent → gold → transparent
- Position: Above and below date

### CTA Button
- Primary gold gradient button
- Positioned 3rem below dates
- Hover: Lift + glow effect
- Size: 16px × 48px padding

### Animation Sequence
1. Page load: Dark fade in (0.5s)
2. Sigil: Scale from 0.8 to 1.0 (0.8s ease-out)
3. Gold glow: Pulse once (1s)
4. Title: Fade up from opacity 0 (0.6s, 0.3s delay)
5. Tagline: Fade up (0.6s, 0.5s delay)
6. Divider: Draw from center (0.8s, 0.7s delay)
7. Date: Fade in (0.4s, 0.9s delay)
8. Button: Fade up (0.5s, 1.1s delay)
9. Sigil rotation: Continuous slow rotation

### Responsive Behavior
- Mobile: Sigil reduces to 80px
- Title: 3rem on mobile
- Tagline: 1.2rem on mobile
- Button: Full width with max-width 300px
- Vertical spacing reduces by 30%
