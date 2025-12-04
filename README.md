# Joseph Smith Era — 3-slide Timeline (Static Site)

## Folder structure
- `index.html` (entry point)
- `assets/styles.css`
- `assets/app.js` (renderer + layout + interactions)
- `assets/data.js` (events + slides + church centers)

## Run locally
Because this uses ES modules (`type="module"`), open it via a local server:

### Option A (Python)
```bash
cd joseph-smith-timeline-site
python -m http.server 8000
```
Then open http://localhost:8000

### Option B (VS Code)
Use the **Live Server** extension.

## Deploy
Upload the whole folder to any static host (Netlify, GitHub Pages, Cloudflare Pages, etc.).

## Editing content
Add/adjust events and centers in `assets/data.js`. The layout will:
- try to place all labels without overlap
- only drop the lowest-importance events if it must
