# Hero Concept: Variation 2 - Left-Aligned Asymmetric

## Layout
**Full viewport height, asymmetric left-weighted composition**

```
┌─────────────────────────────────────────┐
│  [Dark Pavilion Photo - Right 60%]     │
│                                         │
│  ◆ CAMPNEJA                            │
│                                         │
│  A weekend where my                     │
│  worlds collide in                      │
│  the woods.                             │
│                                         │
│  MAY 1–3, 2025                          │
│  Pennsylvania Forest Retreat            │
│                                         │
│  [RSVP Button]                          │
│  [Learn More Button]                    │
│                                         │
│  [Small Sigil]                          │
│                                         │
└─────────────────────────────────────────┘
```

## Details

### Layout Grid
- Left column: 40% width, dark gradient overlay
- Right column: 60% width, full-bleed image
- Content: Constrained to left column with left padding

### Background
- Image: Timber pavilion or firepit photo
- Position: Right 60% of viewport
- Filter: brightness(0.4) saturate(0.8)
- Overlay: Linear gradient from solid obsidian (left) to transparent (40%)
- Creates strong left-to-right visual flow

### Content Block
- Max width: 500px
- Left padding: 8%
- Vertical centering
- Text-align: left

### Typography Hierarchy
- Diamond bullet: ◆ in ceremonial gold, 1rem
- Event name: Cormorant Garamond 5rem / 600
- Line height: 1.1 (tight, stacked)
- Color: Ceremonial gold
- Tagline: Crimson Text 1.75rem / italic
- Color: Parchment #F4EDE3
- Max width: 400px for natural line breaks
- Dates: JetBrains Mono 1rem / 500
- Color: Ceremonial gold
- Subtitle: Crimson Text 0.95rem
- Color: Pale gold

### Button Group
- Stacked vertical layout
- Gap: 1rem between buttons
- Primary: "RSVP on Partiful" (gold)
- Secondary: "View Details" (outline)
- Both left-aligned

### Decorative Sigil
- Size: 60px diameter
- Position: Bottom of content block
- Border: 2px solid gold with 50% opacity
- No rotation (static)
- Serves as visual anchor

### Animation Sequence
1. Image: Fade in from right (0.8s)
2. Diamond: Fade + small rotate (0.4s, 0.3s delay)
3. Title: Slide from left word-by-word (0.6s, 0.5s delay, 0.1s stagger)
4. Tagline: Fade up (0.6s, 0.8s delay)
5. Dates: Fade in (0.4s, 1s delay)
6. Buttons: Fade up staggered (0.5s, 1.2s delay, 0.2s stagger)
7. Sigil: Fade + scale (0.6s, 1.5s delay)

### Hover States
- Entire left block: Subtle gold border appears on left edge
- Buttons: Standard hover effects
- Sigil: Slow rotation on hero hover

### Responsive Behavior
- Tablet: Reduce left column to 50%, right to 50%
- Mobile: Stack vertically
  - Top 50vh: Image with dark overlay
  - Bottom 50vh: Content centered
  - Text-align: center
  - Buttons: Full width
