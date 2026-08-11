# BookiStudios AI — Frontend

The new BookiStudios AI landing page, merged from two source aesthetics:

- **[hydradb-preview](https://github.com/Muhabuki003/hydradb-preview)** → layout system, pixel display type, mono labels, hairline-bordered cell grid, benchmark tables, blinking-cursor & panel-in animations
- **[shadergradient-clone](https://github.com/Muhabuki003/shadergradient-clone)** → full-screen animated WebGL shader-gradient backdrop (orange `#FF430A` / teal `#47FFBF` / blue `#47C2FF` / pale `#FFFBA8`), wide-tracked spaced typography, Lora italic accents

## Stack

Single self-contained `index.html` — no build step. Custom GLSL simplex-noise shader on a `<canvas>` (CSS gradient fallback), IntersectionObserver scroll reveals, typing animation in the hero thread panel, count-up stats, seamless marquee ticker, FAQ accordion.

## Run

Open `index.html` in a browser, or serve statically (GitHub Pages / Vercel / nginx).

## Type

| Role | Font |
|---|---|
| Display (pixel) | Silkscreen |
| Body | Inter |
| Labels / code | JetBrains Mono |
| Italic accents | Lora |
