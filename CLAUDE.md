# Hexagon Lion - Character Animation Demo

An interactive web demo featuring three animated characters from Shapetown.

## Live Site
https://hexagon-lion.vercel.app

## Repository
https://github.com/screendoorstudio/hexagon-lion

## Characters

### Hexagon Lion (Orange - #FF8C00)
- Made of 4 hexagons: 1 top (head), 2 middle (body), 1 bottom (jaw)
- Personality: Brave and strong, tackles problems head-on
- Sound: Deep, warm rumbling (sawtooth + triangle waves)

### Square Man (Purple - #A855F7)
- Made of 4 squares: 1 top (head), 2 middle (body), 1 bottom (jaw)
- Personality: Methodical, makes plans, organizes step by step
- Sound: Robotic, blocky beeps (square wave)

### Triangirl (Green - #22C55E)
- Made of 4 equilateral triangles: 2 pointing up (top row), 1 pointing down (middle), 1 pointing down (jaw)
- Personality: Creative, sees problems from different angles, finds clever solutions
- Sound: Bright, sparkly chimes (sine waves)

## Features

### Hover Interaction
- Character introduces themselves with name
- Speech bubble appears above character
- Jaw animates, character sways gently
- Unique gobbledygook sound plays

### Click Interaction
- Other characters slide off screen (left/right)
- Clicked character zooms in (1.5x scale)
- Speech bubble appears to the side (right for Lion/Square Man, left for Triangirl)
- Character tells more about themselves and Shapetown
- After speech, character zooms out and others return

## Tech Stack
- Single HTML file with embedded CSS and JavaScript
- SVG for character rendering
- CSS animations for movement and jaw
- Web Audio API for gobbledygook sounds
- Deployed on Vercel with GitHub integration

## File Structure
```
Hexagon Lion/
├── index.html          # Main application
├── CLAUDE.md           # Project documentation
├── Hexagon-Lion.png    # Character reference (numbered shapes)
├── Triangirl.png       # Character reference (numbered shapes)
└── screenshots/        # Development screenshots
```

## Animation Details

### Speaking Animation
- Gentle sway: 0.5s ease-in-out
- Jaw movement: 0.4s ease-in-out, moves down 6px

### Transitions
- Character entry: fade in + slide up (0.8s)
- Zoom: scale to 1.5x (0.8s)
- Slide off: translate 300px left/right (0.8s)
