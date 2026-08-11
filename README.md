# BookiStudios AI — Frontend

The new BookiStudios AI landing page, merged from two source aesthetics:

- **[hydradb-preview](https://github.com/Muhabuki003/hydradb-preview)** → layout system, pixel display type, mono labels, hairline-bordered cell grid, benchmark tables, blinking-cursor & panel-in animations
- **[shadergradient-clone](https://github.com/Muhabuki003/shadergradient-clone)** → full-screen animated WebGL shader-gradient backdrop (orange `#FF430A` / teal `#47FFBF` / blue `#47C2FF` / pale `#FFFBA8`), wide-tracked spaced typography, Lora italic accents

## Stack

Single self-contained `index.html` — no build step. Custom GLSL simplex-noise shader on a `<canvas>` (CSS gradient fallback), neon hexagon-forming particles as a seamless full-page background, IntersectionObserver scroll reveals, typing animation in the hero thread panel, count-up stats, seamless marquee ticker, FAQ accordion.

## Demo video

The page ships with a wired 16:9 demo slot (the **“Watch it work.”** section, right after the hero ticker). To light it up, upload a file named exactly **`demo.mp4`** to the repo root, next to `index.html` — no code changes needed:

- **Video present** → the slot detects it, shows the duration, plays on click with native controls.
- **Video absent** → a branded placeholder card shows instead, so the page never looks broken.

Any H.264/AAC `.mp4` works; 1280×720 or 1920×1080 recommended.

## Run

Open `index.html` in a browser, or serve statically (GitHub Pages / Vercel / nginx).

## Type

| Role | Font |
|---|---|
| Display (pixel) | Silkscreen |
| Body | Inter |
| Labels / code | JetBrains Mono |
| Italic accents | Lora |
