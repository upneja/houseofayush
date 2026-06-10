# CampNeja Photo Mapping

All designs now use the actual venue photos from `campnejapics/`

## Photo Files Available
- aerial.jpg - Aerial property view
- boats.jpg - Kayaks/paddle boats
- deck.jpg - Outdoor deck area
- diving board.jpg - Pond with diving board
- game room.jpg - Indoor game room
- outside1.jpg - Outdoor/lodge exterior
- pavillion.jpg - Dining pavilion
- playground.jpg - Play structure
- pond.jpg - Pond views
- volleyball.jpg - Volleyball court/field

## Photo Usage by Design

### 01-secret-society
- **Hero:** aerial.jpg
- **Overview:** outside1.jpg
- **Gallery:** deck.jpg, pond.jpg, pavillion.jpg, boats.jpg, game room.jpg, volleyball.jpg

### 02-fantasy-house
- **Hero:** aerial.jpg (background, 20% opacity)
- **Gallery:** outside1.jpg, deck.jpg, pond.jpg, boats.jpg, pavillion.jpg, volleyball.jpg

### 03-high-fashion
- **Hero:** aerial.jpg
- **Overview:** outside1.jpg
- **Gallery:** aerial.jpg, pond.jpg, deck.jpg, pavillion.jpg

### 04-bauhaus
- **Gallery:** aerial.jpg, pond.jpg, pavillion.jpg, deck.jpg

### 05-cinematic
- **Hero:** aerial.jpg
- **Overview:** outside1.jpg

### 06-forest-mystic
- **Hero:** aerial.jpg

### 07-cabin-outdoors
- **Hero:** aerial.jpg (with green overlay)

### 08-tech-startup
(No photos used - focus on glassmorphic UI)

### 09-festival
(No photos used - focus on colorful gradients)

### 10-luxury-travel
- **Hero:** aerial.jpg (with beige overlay)
- **Overview:** outside1.jpg

## Testing the Designs

To view any design, open the layout.html file in a browser:
```bash
# Example:
open 01-secret-society/layout.html
open 03-high-fashion/layout.html
```

All image paths are now correctly set to: `../campnejapics/[filename].jpg`

## Notes

- All photos have been optimized for web display
- Photos maintain their original quality and aspect ratios
- Each design applies its own visual filters (brightness, saturation, etc.) via CSS
- The images are referenced relatively, so the folder structure must remain intact:
  ```
  campnejaclaude/
  ├── campnejapics/
  │   └── [all photos]
  ├── 01-secret-society/
  │   └── layout.html
  ├── 02-fantasy-house/
  │   └── layout.html
  └── [etc...]
  ```
