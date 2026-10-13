# FANCLASH (prototype)

Static front-end prototype. No build step, no dependencies.

## Run locally
- `npm install` then `npm run dev`, open http://localhost:3000
- Quickest: double-click `index.html`.
- Or serve the folder: `python3 -m http.server 8000` then open http://localhost:8000

## Structure
- `index.html`  page shell (sidebar, main, right sidebar, mobile nav)
- `css/styles.css`  design tokens, layout, components, responsive rules
- `js/app.js`  mock data, rendering, routing (hash: #/home, #/battles, #/clubs) and interactions

Data is mock and lives in memory only; it resets on reload.
