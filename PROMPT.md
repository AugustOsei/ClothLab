# Reusable Prompt

Create a complete, self-contained interactive demo as exactly one HTML file.

Build a polished one-page "Interactive Cloth Lab" website with a dark cinematic UI, inspired by a high-end physics showcase. The page should feature a large wind-blown cloth flag/banner with text mapped onto it. The cloth should feel physical, dimensional, and satisfying to watch.

Content:
- Large text on the cloth: `AUGUST WHEEL`
- Smaller text below it: `By Augustine Osei`
- Additional text below that: `made with GPT 5.5`
- Footer text: `Interactive Cloth Lab. Follow my blog for AI and automation content on augustwheel.com.`

Technical rules:
- Put all HTML, CSS, and JavaScript in one file named `index.html`.
- Do not use React, JSX, npm, bundlers, imports, modules, or external dependencies.
- Use only standard browser APIs.
- Prefer raw WebGL for the cloth rendering.
- Programmatically generate the cloth texture with an offscreen canvas.
- The demo must run by opening `index.html` directly in a browser.
- Do not include any secrets, API keys, analytics tokens, or third-party scripts.

Visual layout:
- Use a dark, glassy lab interface similar to an "Interactive Cloth Lab".
- Add a top bar with the brand title, nav headings, FPS and point counters.
- Nav headings should include `Showcase`, `Physics`, `Texture`, and `Controls`.
- Clicking each nav heading should open an info box near the bottom of the screen explaining that section.
- Add a vertical wind control on the left.
- Add a floating simulation panel with sliders for turbulence, stiffness, and sheen.
- Add a bottom control bar with reset, gust, and pulse controls.
- Keep the UI responsive for desktop and mobile.

Cloth physics:
- Implement custom mass-spring or Verlet-style cloth physics manually in JavaScript.
- Represent the banner as a subdivided rectangular grid of particles.
- Pin the full left edge so it behaves like a smooth pole line.
- Connect particles with structural, bend, and diagonal constraints.
- Apply wind, turbulence, gravity/sag, damping, and pulse pressure.
- The cloth should ripple, fold, swing, and settle naturally.
- Add pointer interaction so users can grab and drag folds in the cloth.
- Show a subtle circular grab indicator at the grabbed point.
- Keep performance reasonable while preserving a rich cloth effect.

Rendering:
- Render both sides of the cloth.
- Use lighting/shading so folds are visible.
- Add moving sheen/highlight bands over the fabric.
- Make the texture bend with the cloth so the text deforms naturally.
- Keep the text legible and dominant.

Quality bar:
- The result should feel impressive enough to share publicly.
- The UI should feel intentional and polished, not like a bare demo.
- The code should be readable and organized.
