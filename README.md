# FRIS – Firmware Risk Intelligence System

Browser-based prototype: firmware hashing, component detection, CVE matching (NVD live + offline fallback), three rule-based agents, risk scoring, and a hash-chained integrity ledger.

## Run locally
Open `index.html` in a browser, or: `python -m http.server 8000`

## Deploy on GitHub Pages
1. Create a repo, add `index.html` and `README.md`
2. Settings → Pages → Source: `main` branch, `/ (root)` → Save
3. Site goes live at `https://<username>.github.io/<repo>/`

## Limits
Finds known issues in components it can identify. Packed/encrypted firmware needs extraction (binwalk) first.
