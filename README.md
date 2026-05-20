# The GenAI Litmus Test

Companion one-pager to the LinkedIn article *"The GenAI Litmus Test: 3 Uncomfortable Questions Every Executive Must Ask"* — published in **The ThankYouAI Newsletter** by Jeff Czischke, Intelligent Automation By Design.

Live at: https://jeffczischke.github.io/thankyouai/

## What's in here

| File | Purpose |
|---|---|
| `index.html` | The full one-pager (interactive Litmus Test, 6-step fix, CTA) |
| `colors_and_type.css` | Brand tokens — colors, typography, spacing, radii |

Pure static HTML/CSS/JS. No build step, no dependencies.

## Local preview

Open `index.html` in any modern browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Publishing on GitHub Pages

1. Push these files to the `main` branch of `jeffczischke/thankyouai`.
2. Repo → **Settings → Pages**.
3. Source: **Deploy from a branch** → Branch: **main**, Folder: **/ (root)**.
4. Save. The site goes live at `https://jeffczischke.github.io/thankyouai/` within ~1 minute.

## Contact

Jeff Czischke · jeff.czischke@fulcrumlabsinc.com
