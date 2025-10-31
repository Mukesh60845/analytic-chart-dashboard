# analytic-chart-dashboard

A lightweight, static analytics dashboard built with plain HTML, CSS and JavaScript — no build tools or frameworks required. Designed for easy customization and quick embedding into static sites.

Why this repo
- Simple, dependency-free dashboard for visualizing charts and metrics.
- Good starter template if you want to expand later with a backend or charting library.

Quick start
1. Clone the repo:
   git clone https://github.com/Mukesh60845/analytic-chart-dashboard.git
2. Open the dashboard:
   - Double-click index.html or open it in your browser (http://... if served).
   - For full browser API support, serve with a static server: python -m http.server 3000

What’s inside
- index.html — main dashboard page
- css/ — stylesheet(s)
- js/ — vanilla JavaScript modules (data loading, chart logic, UI)
- assets/ — images and sample data (CSV/JSON)

How to customize
- Replace sample data in assets/ or update js/data-loader.js to fetch your API.
- Modify layout and styles in css/styles.css.
- Add/replace charts by editing js/charts.js — keep logic modular for each widget.

Notes & tips
- No external libraries included; you can drop in Chart.js, ECharts, or any other chart lib if you want richer visuals.
- If loading local JSON/CSV in Chrome, run a local server to avoid CORS/file restrictions.

Contributing
- Small changes welcome — fork, edit, and open a PR.
- Use clear commit messages and include screenshots for UI changes.

License
MIT — see LICENSE

Contact
Created by Mukesh60845 — open an issue or PR on GitHub for questions or feature requests.
