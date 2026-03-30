# Spring Garden

An immersive, interactive web experience where visitors cultivate their own procedurally-generated spring garden.

**Live Demo:** https://kalrakrish777-ctrl.github.io/spring-garden/

**Repository:** https://github.com/kalrakrish777-ctrl/spring-garden

## Features

### 8 Placeable Items
- **🌸 Flowers** - 8 species (tulips, daisies, sakura, sunflowers, lavender, crocus, hyacinth, bluebells)
- **🌳 Trees** - 4 types (oak, cherry, pine, birch) with unique canopy shapes
- **🍄 Mushrooms** - Colorful spotted mushrooms in 4 varieties
- **🪨 Rocks** - Procedurally generated stone formations
- **🦋 Butterflies** - Place anywhere, they'll be drawn to flowers
- **✨ Fireflies** - Magical glowing insects (more visible at night)
- **☁️ Clouds** - Add custom clouds to the sky
- **🌿 Bushes** - Decorative bushes in various colors

### Living Ecosystem
- **Dynamic sky** - Full day/night cycle (dawn → day → dusk → night) over 2 minutes
- **Sakura petal particles** - 80 falling petals drift across the screen
- **Butterfly AI** - Butterflies are naturally attracted to flowers
- **Firefly glow** - Fireflies glow brighter at night

### Visual Polish
- **Procedural generation** - Every item is unique with randomized properties
- **Growth animations** - Plants emerge and bloom over time
- **Swaying motion** - Trees, flowers, and bushes sway in the breeze
- **Atmospheric depth** - Layered elements create depth
- **Responsive design** - Full-screen canvas that adapts to any screen size
- **Touch support** - Works on mobile devices

### Light Gamification
- **Item counters** - Track flowers, trees, mushrooms, butterflies, and fireflies
- **Inspire meter** - Fills as you interact with the garden
- **Menu selection** - Choose what to place with the bottom toolbar

## Controls

| Input | Action |
|-------|--------|
| Select from menu | Choose item type to place |
| Click/Tap canvas | Place selected item |
| Wait | Watch butterflies gather, fireflies glow |

## Technical Details

- **Stack:** Vanilla JavaScript + HTML5 Canvas (zero dependencies)
- **Architecture:** Object-oriented classes for each item type
- **Performance:** 60fps animation loop with delta-time physics
- **File size:** Single ~30KB HTML file

## Development

To run locally:
```bash
git clone https://github.com/kalrakrish777-ctrl/spring-garden.git
cd spring-garden
open index.html
```

Built with creativity and love for spring. No external libraries used.
