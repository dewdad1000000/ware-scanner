# ware-scanner (older warehouse scanner)

The first version of Canvasback's warehouse location scanner. **It has been replaced by Optimus** (repo `dewdad1000000/new-warehouse-scanner`). Make new scanner features there, not here, unless Steve specifically asks for this one.

## How it ships
- Hosted on **GitHub Pages** from `main` (https://dewdad1000000.github.io/ware-scanner/). Pushing to `main` publishes in a minute or two.
- This repository is **public**: never commit passwords, API keys or personal data.
- `git pull` before you start; never force-push.

## Layout
- `index.html` is the whole app (HTML, CSS, JS in one file). Scans go to a Google Apps Script web app that writes to a Google Sheet; the script isn't in this repo.

## Testing
- Open `index.html` with Playwright (pre-installed) at phone width and check for console errors. Don't send test scans to the real web app.
