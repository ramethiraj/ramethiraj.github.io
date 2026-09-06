# RMKR Toolkit

Static, client-side developer utilities hosted at [rmkr-dev.github.io](https://rmkr-dev.github.io).

Every tool runs in the browser. Transforms, hashes, diffs, and previews stay on your machine. There is no backend and no telemetry that leaves the tab with your payloads.

## Run it locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Tools

### Transform

- **Payload Knife** — pretty/minify JSON, JSON to CSV, cURL to fetch
- **YAML ↔ JSON** — convert and format
- **CSV Convert** — CSV, JSON, and YAML
- **XML ↔ JSON** / **TOML ↔ JSON**
- **Encode / Decode** — Base64, URL, HTML entities
- **.env ↔ JSON**, **Query ↔ JSON**, **Headers Parser**

### Security

- **JWT Debugger**
- **Hash Lab** — SHA-256, SHA-1, MD5
- **UUID Generator**
- **PEM / SSH Viewer**

### Time

- **Time Overlay** — timezone working-hour grid
- **Unix Timestamp**
- **Cron Explainer**

### Data

- **Markdown Viewer**
- **Payload Diff**
- **Mock Generator**
- **JSON Schema Studio**
- **Regex Tester**
- **SQL Formatter**
- **Markdown Table**

### Design

- **Architect Draw**
- **Color Converter**
- **QR Code**
- **Sample Data**
- **Slugify**

### Dev helpers

- **Roadmap Planner** (saved in localStorage)
- **Collab Pad** (peer-to-peer scratch pad)
- **Number Base**
- **Local Stats** (counts stored only in this browser)

## Notes

- Shared chrome lives in `assets/site.css` and `assets/site.js`.
- Small libraries used by a few tools are vendored under `assets/vendor/`.
- Existing tool URLs (`/md`, `/jwt`, `/transform`, and the rest) are unchanged.
