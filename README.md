# Quetta Labs

**For a scale not yet reached**

A minimal, responsive landing page for Quetta Labs — research and incubation.

## Preview

No dependencies or build step required. Open `index.html` in a browser, or run `python3 -m http.server 8000` from this directory.

## Edit

- `index.html`: logo, slogan, introduction, and GitHub link
- `styles.css`: layout and brand colors — Purple `#7A4E94`, Cyan `#5FB8BA`
- `assets/`: supplied logo and space background

Instrument Sans is self-hosted under the included SIL Open Font License. No external font requests, scripts, or analytics. Relative asset paths support GitHub Pages project URLs.

## Scroll effect

The space image uses a native CSS scroll timeline and a transform-only animation. A short, decorative scroll area reveals more of the background without adding new content. There are no animation libraries, scroll listeners, continuous JavaScript loops, or extra image layers.

Browsers without CSS scroll-timeline support and visitors with reduced motion enabled see the static, single-screen layout. The favicon uses the supplied Q image unchanged.

## GitHub Pages

In **Settings → Pages → Deploy from a branch**, select the `main` branch and `/ (root)`.
