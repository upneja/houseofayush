# Secret Society Design Concept

## Visual Direction
**Theme:** Obsidian/gold ceremonial aesthetic with occult-lite mysticism
**Mood:** Exclusive, mysterious, ritualistic, sophisticated
**Reference Vibes:** Secret societies, ceremonial orders, occult symbolism, luxury mystery clubs

---

## Color Philosophy
Dark obsidian foundation (#0A0A0F, #161616) creates exclusivity and depth. Ceremonial gold (#D4AF37) provides regal accents. Deep crimson (#8B1E3F) and purple (#3E2A47) add mystical undertones. Parchment (#F4EDE3) for readability.

**Gradient Strategy:** Subtle dark-to-dark gradients maintain mystery, gold gradients for emphasis areas.

---

## Layout & Grid

### Hero Section
- Full-viewport dark overlay on venue aerial photo
- Centered ceremonial sigil/emblem
- Event name in large Cormorant Garamond with gold accent
- Tagline in italicized Crimson Text
- Subtle gold line dividers

### Section Architecture
- **Asymmetric grid:** 60/40 splits for visual interest
- **Dark cards** with gold borders on hover
- **Ceremonial dividers:** Gold ornamental lines between sections
- **Negative space:** Generous breathing room maintains exclusivity

### Component Grid
- 12-column base
- Breakpoints: 1440px / 1024px / 768px / 375px
- Cards use 4-column spans on desktop, full-width on mobile

---

## Iconography & Symbols

### Custom Sigil System
- **Primary sigil:** Geometric forest symbol (triangle + tree silhouette + circle)
- **Section markers:** Small occult-inspired icons (crescent moon, pentagram star, key, candle, compass)
- **Decorative elements:** Flourishes, ornamental corners, wax seal aesthetics

### Icon Style
- Line-based, 2px stroke weight
- Gold color (#D4AF37)
- Minimal, geometric, symmetrical
- Used sparingly for maximum impact

---

## Textures & Backgrounds

### Primary Textures
1. **Subtle paper grain** on parchment sections
2. **Dark linen texture** for obsidian backgrounds
3. **Gold foil effect** on hover states
4. **Vignette overlays** on photo sections

### Photo Treatment
- Heavy dark overlay (60-70% opacity)
- Desaturated slightly (-15% saturation)
- Gold color grading on highlights
- Sharp vignettes to create focus

---

## Components Library

### Buttons
**Primary CTA (RSVP):**
- Background: Ceremonial gold gradient
- Border: 2px solid darker gold
- Typography: Cinzel 600, 14px, uppercase, 0.05em spacing
- Hover: Embossed effect, slight glow
- Padding: 16px 40px

**Secondary:**
- Transparent with gold border
- Gold text
- Hover: Fill with gold, text to obsidian

### Cards
- Dark background (#161616)
- Subtle gold border (1px)
- Hover: Border glows, lifts with shadow
- Inner padding: 32px
- Corner radius: 2px (sharp, formal)

### Navigation
- Fixed top bar, transparent → solid on scroll
- Dark background with gold underline on active
- Cinzel typography, uppercase
- Smooth scroll anchors
- Mobile: Hamburger with ceremonial slide-in

### Section Dividers
- Horizontal gold lines with center sigil
- Fade-in animation on scroll
- 1px height, ornamental caps

### Gallery
- Masonry grid with dark overlays
- Gold borders on hover
- Lightbox with ceremonial frame
- Captions in Crimson Text italic

### CTA Blocks
- Full-width dark section
- Centered content with sigil above
- Large gold CTA button
- Subtle particle effect background

---

## Logo/Wordmark Exploration

### Primary Lockup
```
    [Ceremonial Sigil]
      CAMPNEJA
  —— MAY 1–3, 2025 ——
```

### Variations
1. **Stacked:** Sigil above, name below, date subtitle
2. **Horizontal:** Sigil left, name right, small date
3. **Minimal:** Just "CAMPNEJA" in Cinzel with gold underline
4. **Ceremonial seal:** Circular badge with sigil, name around border

### Sigil Concept
- Geometric triangle (mountain/forest)
- Pine tree silhouette in center
- Outer circle with small stars/dots
- All in gold line art (2-3px stroke)

---

## Animation & Motion

### Micro-interactions
- **Hover states:** Smooth gold glow (0.3s ease)
- **Button press:** Subtle emboss effect
- **Card lift:** translateY(-8px) with shadow expansion
- **Navigation:** Smooth scroll with easing

### Scroll Animations
- **Fade-up:** Section titles and cards (0.6s delay stagger)
- **Line draw:** Dividers animate from center outward (1s)
- **Parallax:** Hero background subtle movement (0.1x scroll speed)
- **Sigil rotate:** On page load, slow 360° rotation (2s)

### Page Load
1. Dark screen fade-in
2. Ceremonial sigil scales from center (0.8s)
3. Gold accent glow pulses once
4. Hero text fades up (0.5s delay)
5. Content sections cascade in (0.2s stagger)

### Transitions
- Page transitions: Smooth fade (0.4s)
- Section changes: Slide + fade (0.5s cubic-bezier)
- Image loads: Blur-up from dark placeholder

---

## Responsive Strategy

### Desktop (1440px+)
- Hero: Full viewport height
- Grid: 12-column with wide gutters
- Imagery: Large with dramatic overlays
- Typography: Full scale

### Tablet (768-1023px)
- Hero: 80vh
- Grid: 8-column, tighter gutters
- Cards: 6-column spans
- Font scale: 85%

### Mobile (375-767px)
- Hero: 70vh with vertical lockup
- Single column layout
- Cards: Full-width
- Navigation: Hamburger menu
- Font scale: 70%
- Maintain ceremonial feel with gold accents

---

## Accessibility Notes
- Ensure gold (#D4AF37) on dark backgrounds meets WCAG AA (4.5:1+)
- Use parchment (#F4EDE3) for body text on dark
- All interactive elements: 44x44px minimum
- Focus states: Gold outline with 2px offset
- Preserve hierarchy without relying solely on color

---

## Export Assets
- Hero concepts: 3 variations (center sigil, left-aligned, minimal)
- Component samples: Button states, cards, navigation
- Sigil: SVG in multiple sizes
- Preview: 1920x1080 desktop mockup with key sections
