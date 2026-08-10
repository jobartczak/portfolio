# Project Guide

## Architecture

This project is a static Netlify site with no framework, package dependencies, or build step. `index.html` contains the semantic page structure, while `styles.css` owns all visual presentation and responsive behavior. Gallery photographs are stored locally in `assets/images/` so the deployed page does not depend on third-party image requests.

## Key Directories

- `assets/images/`: Six landscape JPEGs used by the showcase.
- `.netlify/`: Netlify-generated task metadata and result summaries.
- Project root: Static entry point, stylesheet, and documentation.

## Coding Conventions

- Keep the site dependency-free unless a feature clearly requires otherwise.
- Use semantic HTML elements and descriptive image alternative text.
- Use BEM-style class names for page components.
- Define reusable colors, spacing, and corner treatments as CSS custom properties.
- Preserve keyboard focus behavior alongside hover interactions.
- Respect `prefers-reduced-motion` for any new animation.
- Keep images local and use purposeful filenames.

## Design Decisions

The desktop gallery intentionally uses exactly three columns and two rows. It reduces to two columns on tablets and one column on phones to preserve image size and readability. The page title appears over every image on hover, keyboard focus, and by default on touch devices where hover is unavailable.
