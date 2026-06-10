# CampNeja — 10 Complete Website Designs

All 10 designs are now **fully functional** with your actual venue photos integrated.

## Quick Start

Open any design directly in your browser:

```bash
# From the campnejaclaude directory:
open 01-secret-society/layout.html
open 02-fantasy-house/layout.html
open 03-high-fashion/layout.html
# ... etc
```

Or simply double-click any `layout.html` file.

---

## The 10 Designs

### 1. Secret Society
**Vibe:** Obsidian/gold, ceremonial, occult-lite mysticism
- Dark obsidian backgrounds with ceremonial gold accents
- Rotating sigil animations
- Elegant serif typography (Cormorant Garamond)
- Perfect for: Exclusive, mysterious gathering feel

### 2. Fantasy Noble House
**Vibe:** Medieval crests, banners, royal forest kingdom
- Heraldic shields and royal navy/forest green palette
- Banner ribbons and ornamental dividers
- House crest logo system
- Perfect for: Epic, legendary adventure vibes

### 3. High Fashion Editorial
**Vibe:** Dior/Celine B/W minimalism, editorial sophistication
- Pure black and white with maximum contrast
- Ultra-minimal typography (Bodoni, Inter)
- Magazine-style asymmetric layouts
- Perfect for: Sophisticated, refined aesthetic

### 4. Bauhaus Modernist
**Vibe:** Geometric shapes, primary colors, Swiss grid precision
- Bold primary colors (red, blue, yellow)
- Geometric circles, squares, triangles
- Futura typography, perfect grid alignment
- Perfect for: Bold, modern, rational design

### 5. Cinematic Universe
**Vibe:** Dune/Bond dramatic lighting, metallic typography
- Desert tones with midnight blue
- Metallic gradient text effects
- Cinematic widescreen compositions
- Perfect for: Epic, larger-than-life presentation

### 6. Mystical Forest Cult
**Vibe:** Bioluminescence, glowing runes, ethereal fog
- Dark forest blacks with neon green/teal glows
- Pulsing animations and floating orbs
- Mystical symbols throughout
- Perfect for: Otherworldly, enchanted forest feel

### 7. Cabin Outdoor Brand
**Vibe:** REI/Patagonia earth tones, trail badges
- Forest greens and earth tones (terracotta, sandstone)
- Badge/patch style elements
- Trail marker navigation
- Perfect for: Authentic outdoor adventure brand

### 8. Tech Startup
**Vibe:** Glassmorphism, neon accents, floating UI
- Deep purple/blue with neon cyan/magenta
- Frosted glass panels with backdrop blur
- Modern, sleek typography (Space Grotesk)
- Perfect for: Futuristic, innovative tech aesthetic

### 9. Festival Brand
**Vibe:** Sunset gradients, playful stickers, vibrant energy
- Bright sunset gradients (pink→orange→yellow)
- Playful rounded typography (Fredoka)
- Floating sticker elements
- Perfect for: High-energy, celebratory party vibes

### 10. Luxury Travel
**Vibe:** Aman/Soho House quiet elegance, linen textures
- Warm neutrals (sand, beige, taupe)
- Generous whitespace, refined typography
- Soft, natural sophistication
- Perfect for: Understated luxury, serene retreat

---

## File Structure

Each design folder contains:

```
XX-design-name/
├── layout.html          # Complete responsive landing page
├── palette.json         # Full color system
├── typography.md        # Type scale and font specifications
├── design-notes.md      # Detailed design direction & rationale
├── components/          # Reusable UI components (select designs)
└── hero-concepts/       # Multiple hero variations (select designs)
```

---

## All Photos Are Live

✅ All placeholder images have been replaced with your actual venue photos
✅ All paths are correctly set to `../campnejapics/[photo].jpg`
✅ Photos display with custom filters per design (brightness, saturation, etc.)

See `PHOTO-MAPPING.md` for detailed photo usage per design.

---

## Customization

### Update RSVP Link

Search and replace `PARTIFUL_URL_HERE` in any `layout.html` with your actual Partiful link:

```bash
# Example:
sed -i '' 's|PARTIFUL_URL_HERE|https://partiful.com/e/YOUR_EVENT_ID|g' 01-secret-society/layout.html
```

### Adjust Event Details

All event content (dates, pricing, schedule, etc.) is in the HTML files and can be edited directly.

### Modify Colors

Each design has a `palette.json` with the complete color system. The colors are also defined in CSS variables in the `<style>` section of each HTML file.

---

## Technical Notes

- All designs are responsive (mobile, tablet, desktop)
- Built with vanilla HTML/CSS (no frameworks required)
- Fonts loaded from Google Fonts CDN
- Works in all modern browsers
- No build process needed - just open and view!

---

## Next Steps

1. **Review all 10 designs** - Open each layout.html in your browser
2. **Pick your favorite(s)** - You can use one or combine elements
3. **Update RSVP link** - Replace `PARTIFUL_URL_HERE` with real link
4. **Optional tweaks** - Adjust copy, colors, or layout as needed
5. **Deploy** - Host on any web server (Netlify, Vercel, GitHub Pages, etc.)

---

Enjoy exploring your 10 completely unique CampNeja website designs! 🌲✨
