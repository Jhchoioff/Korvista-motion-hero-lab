# KorVista Motion Hero Lab

A growing internal library of cinematic and signature luxury hero experiments for KorVista Design.

## Current studies

- **Cinematic / Interior 01 — Warm to Daylight**  
  Dolly-in, lateral movement, dolly-out, crossfade, and cohesive color grading.
- **Cinematic / Interior Parallax 01 — Depth You Can Feel**  
  Three-scene dolly and lateral sequence, ending with layered 2.5D pointer-responsive depth.
- **Cinematic / Boutique Hotel 01 — Arrive Somewhere**  
  Center-opening curtain reveal, pool push-in, light sweep, and layered sunset parallax.

## Structure

```text
dist/
├── index.html
├── cinematic/
│   ├── interior-01/
│   │   └── index.html
│   ├── interior-parallax/
│   │   └── index.html
│   └── hotel-01/
│       └── index.html
└── assets/
    ├── interior-01/
    │   ├── evening.png
    │   ├── daylight.png
    │   └── lounge.png
    ├── interior-parallax/
    │   ├── background.png
    │   └── foreground.png
    └── hotel-01/
        ├── suite.png
        ├── pool.png
        ├── pavilion.png
        ├── pavilion-background.png
        └── pavilion-foreground.png
```

## Add a new study

1. Create a dedicated folder under `dist/cinematic/` or `dist/signature/`.
2. Store its images in a matching folder under `dist/assets/`.
3. Add a card linking to the new page from `dist/index.html`.
4. Test both desktop and mobile layouts before publishing.

## Local preview

Open `dist/index.html` in a browser. Select a study card to view the full hero.

## Publishing note

This repository is a creative lab. Only selected, client-ready studies should be linked from the main KorVista Design website.
