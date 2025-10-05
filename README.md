# EcoTales — Cosmic Conversations

Lightweight static site that presents conversational narratives about environmental topics (Deforestation, Ice Melting, Global Warming) together with short dataset/info cards. Built with plain HTML, Tailwind CSS (CDN), and a small inline script for page navigation.

## Key features
- Responsive two-column layout (info card left / conversation right) on md+ screens
- External stylesheet: `styles.css` for custom rules and helpers
- Uses Material Symbols icons and Google fonts for consistent visual language
- No build step required — Tailwind is loaded from CDN

## Files
- `index.html` — main single-page document with multiple sections (home, ice-melting, global-warming, deforestation)
- `styles.css` — project stylesheet containing custom CSS utilities and page visibility rules
- `deforestation.png` — sample image used in the Deforestation info card (place image in project root)

## Getting started (development)
1. Clone or copy the project folder to your machine.
2. Ensure the assets (images) referenced in `index.html` are present in the project root.
3. Open `index.html` in your browser (double-click or use `File → Open`).

Notes
- The page navigation is handled by the `showPage(pageId)` function in `index.html`. It toggles `.page.active` and highlights nav links.
- Tailwind is included via CDN in `index.html`. For production or significant styling changes, consider switching to a local Tailwind build pipeline.

## License
MIT — see source files for attribution.

If you want, I can add a minimal `scripts.js`, optimize images, or create a simple dev task for VS Code. Which would you like next?
