# Syeda Javeria — Portfolio

A single-page portfolio site built with plain HTML/CSS/JS (no build step needed).

## Files
- `index.html` — page content and structure
- `styles.css` — all styling (colors, type, layout)
- `script.js` — mobile nav toggle
- `assets/` — put your real images here (Canva designs, Pinterest pins, Amazon Storefront screenshot)

## Placeholder image slots
Sections marked with a dashed diagonal-striped box and a label (e.g. "Canva design",
"Pinterest pin", "Amazon Storefront — main page screenshot") are placeholders.
To swap in a real image, replace a `<div class="image-slot" ...>` block in `index.html`
with an `<img>` tag, e.g.:

```html
<img src="assets/canva-design-1.jpg" alt="Canva design — Cherry & Rosé campaign">
```

## Publishing on GitHub Pages
1. Create a new GitHub repo (e.g. `syeda-portfolio`).
2. Upload `index.html`, `styles.css`, `script.js`, and the `assets/` folder to the repo root.
3. Go to the repo's **Settings → Pages**.
4. Under "Build and deployment", set Source to **Deploy from a branch**, branch `main`, folder `/root`.
5. Save — GitHub will give you a live URL like `https://yourusername.github.io/syeda-portfolio/` within a minute or two.
