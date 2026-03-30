# Spring Garden

An immersive, interactive web experience where visitors cultivate their own procedurally-generated spring garden.

**Live Demo:** https://kalrakrish777-ctrl.github.io/spring-garden/

**Repository:** https://github.com/kalrakrish777-ctrl/spring-garden

## Features

### Interactive Garden
- **Click anywhere to plant flowers** - 8 unique procedural flower species (tulips, daisies, sakura, sunflowers, lavender, crocus, hyacinth, bluebells)
- **Growth animations** - Flowers emerge from the ground and bloom over 2 seconds
- **Swaying motion** - All flowers gently sway in the breeze using sine-wave physics

### Living Ecosystem
- **Butterfly attraction system** - Butterflies are naturally drawn to newly planted flowers
- **Sakura petal particles** - 80 falling petals drift across the screen with rotation and wind physics
- **Dynamic sky** - Full day/night cycle (dawn → day → dusk → night) over 2 minutes

### Visual Polish
- **Procedural generation** - Every flower is unique with randomized colors, sizes, and growth patterns
- **Atmospheric depth** - Layered grass, clouds, and gradient sky create depth
- **Responsive design** - Full-screen canvas that adapts to any screen size
- **Touch support** - Works on mobile devices

### Light Gamification
- **Flower counter** - Track how many flowers you've planted
- **Butterfly counter** - Watch butterflies gather in your garden
- **Inspire meter** - Fills as you interact, rewarding cultivation

## Technical Details

- **Stack:** Vanilla JavaScript + HTML5 Canvas (zero dependencies)
- **Architecture:** Object-oriented with Flower, Butterfly, and Particle classes
- **Performance:** 60fps animation loop with delta-time physics
- **File size:** Single ~25KB HTML file

## Controls

| Input | Action |
|-------|--------|
| Click/Tap | Plant a random flower |
| Wait | Watch butterflies naturally gather |

## Development

To run locally:
```bash
git clone https://github.com/kalrakrish777-ctrl/spring-garden.git
cd spring-garden
open index.html
```

Built with creativity and love for spring. No external libraries used.
