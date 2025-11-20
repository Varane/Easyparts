# Easyparts landing page

## What changed in this update
- Language switcher fixes and WhatsApp submission flow improvements from the latest commit.
- Softer gray backgrounds on the hero, cards/steps, and info panels.

## How to apply the changes
1. Download or clone this repository to your machine.
2. Replace your existing `index.html` with the one in this repo (or copy-paste the contents).
3. Make sure `background.jpg` stays next to `index.html` so the hero background loads.
4. If you deploy to a static host (Netlify, Vercel, GitHub Pages, etc.), commit and push these files as-is.
5. To verify locally, serve the folder with any static server:
   - Python: `python -m http.server 8000`
   - Node (if you prefer): `npx serve .`
6. Open `http://localhost:8000` in your browser and test:
   - Switch languages using the ES/EN/DE/LT/FR/IT/PT buttons.
   - Submit the form and confirm WhatsApp opens with the prefilled message.

### Downloading the full files
- **Download as ZIP (no git needed):**
  1. On GitHub, click the green **Code** button > **Download ZIP**.
  2. Unzip it locally; you will see the full `index.html` (~1100 lines), `background.jpg`, `manifest.json`, and this `README.md`.
- **Clone with git:**
  1. `git clone https://github.com/<your-repo>/Easyparts.git`
  2. Change into the folder and open `index.html` with your editor.
- **Single-file download:**
  1. Open `index.html` in the GitHub UI.
  2. Click **Raw**, then save the page (`Ctrl+S`/`Cmd+S`) to download the entire file.

> If you see fewer lines (for example ~300), the file was likely truncated during copy/paste. Re-download using one of the methods above to ensure you have the full file.

## Notes on WhatsApp behavior
- The form now redirects in the **same tab** to the WhatsApp URL so it works on both desktop and mobile without pop-up blockers.
- Ensure you are logged into WhatsApp Web on desktop; on mobile it will open the WhatsApp app automatically.

## Troubleshooting
- If language switching does not seem to update text, clear your browser cache/localStorage and reload.
- If WhatsApp does not open, verify that you have internet access and that `wa.me` is not blocked on your network.
