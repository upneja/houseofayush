# Fantasy Noble House Design Concept

## Visual Direction
**Theme:** Medieval-modern forest kingdom with heraldic crests and royal banners
**Mood:** Regal, noble, adventurous, legendary
**Reference Vibes:** Game of Thrones meets modern luxury, royal forest estates, medieval heraldry

---

## Color Philosophy
Royal navy (#1A2B4A) and deep forest green (#2C4A3E) create noble foundation. Heraldic gold (#C9A961) for royal accents. Banner red (#A63446) for dramatic emphasis. Parchment (#EDE8DC) for readability. Metallic silvers and coppers for detail work.

---

## Layout & Grid

### Hero Section
- Full-height with banner overlay
- House crest centered or top-aligned
- Event name in imperial capitals (Cinzel Decorative)
- Decorative gold underline
- Heraldic shields or banner elements flanking

### Section Architecture
- **Banner-style headers:** Full-width colored bands with centered text
- **Shield cards:** Information blocks shaped like heraldic shields
- **Scroll dividers:** Parchment-style section breaks
- **Royal frame:** Content areas with decorative corner flourishes

---

## Iconography & Symbols

### House Crest System
- **Primary crest:** Shield shape with pine tree, mountain, crossed axes
- **Elements:** Crown above, banner below with date ribbon
- **Style:** Traditional heraldry with line art
- **Colors:** Gold, navy, forest green, banner red

### Icon Library
- Swords, shields, crowns, banners
- Pine trees, mountains, campfires
- Medieval line art style (2-3px stroke)
- Used for section markers and list bullets

---

## Textures & Backgrounds

### Primary Textures
1. **Parchment grain** for light sections
2. **Linen canvas** for dark sections
3. **Leather texture** (subtle) on cards
4. **Wood grain** for accent elements

### Photo Treatment
- Slight warming filter (+10 warmth)
- Vignette with forest green tint
- Bordered with gold or silver frames
- Overlay with subtle medieval patterns

---

## Components Library

### Buttons
**Primary (Royal):**
- Background: Heraldic gold gradient
- Border: 3px double border, bronze
- Typography: Montserrat 600, uppercase
- Icon: Small shield or sword
- Hover: Embossed, shadow lift

**Secondary (Banner):**
- Background: Banner red
- Border: Gold accent
- White text
- Hover: Lighten, scale slightly

### Cards (Shield Style)
- Shield-shaped containers (CSS clip-path)
- Gold border with corner decorations
- Navy or parchment background
- Hover: Lift with dramatic shadow
- Banner ribbon at top for title

### Navigation
- Fixed top bar with royal navy background
- Gold underline on active states
- House crest logo on left
- Uppercase Montserrat labels
- Dropdown: Parchment background with gold borders

### Banners
- Full-width decorative bands
- Wavy bottom edge (SVG)
- Centered text with flanking ornaments
- Background: Banner red or royal navy
- Gold text with shadow

---

## Logo/Wordmark

### Primary House Crest
```
      ╔═══════╗
      ║ CROWN ║
    ╔═══════════╗
    ║  SHIELD   ║
    ║ [TREE +   ║
    ║ MOUNTAIN] ║
    ╚═══════════╝
     ═══════════
     CAMPNEJA
     MAY 1-3
```

### Variations
1. **Full crest:** With crown, shield, banner, motto
2. **Shield only:** Simplified for small spaces
3. **Wordmark:** "HOUSE CAMPNEJA" in Cinzel
4. **Circular seal:** Round badge version

---

## Animation & Motion

### Micro-interactions
- **Banner unfurl:** On page load, banners roll down
- **Shield shine:** Gold borders shimmer on hover (0.5s)
- **Crest reveal:** Pieces of crest animate in
- **Scroll parallax:** Banners move at different speeds

### Page Load Sequence
1. Royal navy fade in (0.3s)
2. House crest: Center shield fades in (0.6s)
3. Crown descends from above (0.4s, 0.6s delay)
4. Banner ribbon unfurls below (0.5s, 1s delay)
5. Event name: Letter-by-letter (1.2s, 1.5s delay)
6. Gold line: Draw from center (0.8s, 2s delay)
7. Content sections: Cascade up (0.3s stagger)

### Transitions
- Page changes: Cross-fade with gold flash
- Section reveals: Rise from bottom with banner unfurl
- Gallery: Images slide in with metallic glint

---

## Responsive Strategy

### Desktop (1440px+)
- Hero: Full viewport with large crest
- Grid: 12-column with decorative gutters
- Cards: Shield shapes fully rendered
- Banners: Full decorative elements

### Tablet (768-1023px)
- Crest: Reduced size, simplified
- Cards: Rounded rectangles instead of shields
- Banners: Simplified wave patterns
- Font scale: 90%

### Mobile (375-767px)
- Crest: Minimal version, top-aligned
- Single column
- Cards: Simple borders, no complex shapes
- Banners: Flat with minimal decoration
- Font scale: 75%

---

## Accessibility
- Ensure gold (#C9A961) meets contrast on navy (check WCAG AA)
- Use parchment for body text on dark backgrounds
- Decorative elements: aria-hidden="true"
- Focus states: Gold outline with high contrast
- Interactive minimums: 44×44px

---

## Special Features

### House Motto
Display in gothic script: *"In Silva, Unitas"* (In the Forest, Unity)

### Heraldic Badges
Visitor profile badges: Knight, Lord, Lady, Squire (based on RSVP status)

### Medieval Calendar
Date displayed in medieval style: "The First Through Third Days of May, Year of Our Gathering 2025"
