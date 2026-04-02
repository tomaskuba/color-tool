# Brand Color Tool

A single-file browser tool for exploring and evaluating brand color palettes with accessibility in mind.

**[Live Demo](https://tomaskuba.github.io/color-tool/)**

## Features

- **4 color pickers** — primary, secondary, dark & light background
- **WCAG contrast evaluation** — AA Large (3:1), AA (4.5:1), AAA (7:1)
- **APCA scores** — modern perceptual contrast with minimum font size recommendations
- **Tints & shades** — 10-step scale (50–900) for each color with contrast ratings
- **Unified Light/Dark palette** — shades interpolate between backgrounds for cohesive feel
- **Shade text preview** — see how each shade looks as actual text on your backgrounds
- **EyeDropper** — pick colors from anywhere on your desktop (Chrome/Edge 95+, HTTPS only)
- **Color wheel** — visualize primary/secondary relationship
- **URL hash sharing** — share palettes via URL (e.g. `#ff550a-009cbf-0f1835-faf7f4`)
- **Persistent state** — colors, font, and settings saved to localStorage

## Usage

Open `index.html` in a browser. No build step, no dependencies (except Google Fonts CDN and [iro.js](https://iro.js.org/) color picker loaded from CDN).

For EyeDropper support, serve over HTTPS or localhost:

```
python3 -m http.server 8000
```

## License

MIT
