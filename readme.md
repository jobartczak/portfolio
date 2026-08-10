# Field Notes Image Showcase

A responsive, editorial-style image gallery built as a lightweight static site for Netlify. The page presents six landscape photographs in a three-column, two-row desktop grid with rounded corners and title overlays that appear on hover or keyboard focus.

## Technologies

- Semantic HTML5
- Modern CSS Grid and responsive media queries
- Local optimized JPEG assets
- CSS-only hover, focus, and reduced-motion interactions

## Run Locally

No build step or package installation is required. Open `index.html` directly in a browser, or serve the project directory with any static file server.

For Netlify’s local environment, run:

```bash
netlify dev --port 8889
```

Then open `http://localhost:8889`.

## Structure

```text
.
├── assets/images/   # Local gallery photographs
├── index.html       # Page content and gallery markup
└── styles.css       # Layout, visual design, and interactions
```
