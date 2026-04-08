# Uncut App

John's movie recommendation app — immersive 3D carousel prototypes with Three.js, GSAP, and poster-driven UI. Mobile-first (430px), single-file HTML.

## Structure

```
uncut-app/
├── index.html                     # Launcher — links to all designs
│
├── design-1/                      # Ferris Wheel Cinematic
│   └── index.html                 # Three.js 3D carousel, gold/dark palette, Playfair Display + Inter
│
├── design-1-final/                # Ferris Wheel — refined
│   └── index.html                 # Apple Keynote clean, white surface, Inter, poster-first layout
│
├── design-2/                      # Frosted Glass Variant
│   └── index.html                 # Glassmorphism cards, gradient accents, Space Grotesk + DM Sans
│
├── design-2-carousel/             # Hamster Wheel Carousel
│   ├── index.html                 # Three.js hamster wheel 3D, Bebas Neue + Plus Jakarta Sans, dark vignette
│   ├── intro.mp3                  # Audio intro
│   └── terror-english.m4a        # Audio asset
│
├── design-ios/                    # iOS Motion
│   └── index.html                 # Apple-native feel, Inter, pill tabs, frosted blur, subtle Three.js bg
│
├── data/                          # Shared movie JSON data
└── CLAUDE.md                      # Agent instructions
```

## Design index

| Design | Name | Aesthetic | Typography | Tech |
|--------|------|-----------|------------|------|
| 1 | Ferris Wheel Cinematic | Dark cinematic, gold accent | Playfair Display + Inter | Three.js, GSAP |
| 1-final | Ferris Wheel Refined | Apple Keynote clean, white | Inter | Three.js, GSAP |
| 2 | Frosted Glass | Glassmorphism, gradient accents | Space Grotesk + DM Sans | Three.js, GSAP |
| 2-carousel | Hamster Wheel | Dark vignette, 3D drum carousel | Bebas Neue + Plus Jakarta Sans | Three.js |
| ios | iOS Motion | Apple-native, frosted blur | Inter | Three.js, GSAP |

## Tech

- Three.js r128 — 3D poster carousels and ambient backgrounds
- GSAP 3.12 — scroll and transition animation
- TMDB poster API for imagery
- Google Fonts
- Pure HTML/CSS/JS — no build step
- Mobile-first (430px max-width)
