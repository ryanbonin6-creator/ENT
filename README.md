# Turf Burn

A responsive, dependency-free website exploring a player-first transition from NFL synthetic turf to natural grass.

Run locally:

```sh
cd /workspace/ENT
python3 -m http.server 8000 --bind 127.0.0.1
```

Open the served `index.html` in a browser. No build or API credentials are required. Questions and suggestions stay in browser localStorage and can be exported; this is not a shared discussion service.

The uploaded PDF is included in `assets/innovation-report.pdf` and preserved as accessible text in `report.html`. Research citations are attributed to that report and have not been independently verified online. Stadium costs are explicitly illustrative category-based scenarios, not sourced contractor quotes. The inventory uses historical 2024 venues and needs current operator verification. See Sources & methodology for assumptions, exclusions, and limitations.

Validation: `node --check app.js`, HTTP smoke checks, and headless Chromium interaction checks.
