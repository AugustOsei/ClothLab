# August Wheel Cloth Lab

A single-file interactive WebGL demo: a dark UI cloth lab with a wind-driven August Wheel banner, custom Verlet-style cloth physics, and a canvas-generated texture.

The demo is fully self-contained in `index.html`: no npm install, no external libraries, no API keys, and no build step.

## Run locally

Open `index.html` directly in a browser, or serve the folder:

```sh
python3 -m http.server 4173
```

Then visit `http://127.0.0.1:4173/`.

## Deploy on Vercel

This is a static site. Point Vercel at the repository root and leave the build command empty.

## Recreate It

See `PROMPT.md` for a reusable prompt that asks an AI coding tool to generate the same kind of one-page interactive cloth lab.
