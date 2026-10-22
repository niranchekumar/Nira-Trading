# Trading Journal Pro — Odia + English

A responsive colourful trading journal web app. Works on mobile and desktop browsers; can be published free using GitHub Pages.

## Features
- Odia / English toggle
- Add, edit, delete trades
- Daily trade history, monthly/yearly/all-time filters
- Net P&L after manually entered charges
- Win rate, profit factor and monthly chart
- Market and symbol filters
- CSV export for backups
- Local browser storage (not a broker connection)

## GitHub Pages setup
1. Create a repository named `trading-journal-pro`.
2. Upload `index.html`, `style.css`, `app.js`, and `README.md` to the repository root.
3. Go to **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
5. Wait for the Pages URL to appear there.

## Important
Records are stored in browser localStorage. They do not automatically sync across devices; export CSV backups regularly. Do not enter broker passwords or API secrets. This is a journal/calculator, not trading advice or a broker integration. Confirm fees against your broker contract note.
