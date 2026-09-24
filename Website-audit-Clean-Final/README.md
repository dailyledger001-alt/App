# Daily Ledger — Life Planner

A private, local-first planner with a dashboard, finance tracker, tasks, habits, fitness, meals, goals, calendar, and monthly PDF reports.

## Run

No installation or build step is required.

1. Extract the ZIP.
2. Open `index.html` in a modern browser.

If your browser restricts local files, run a local server from this folder:

```bash
python -m http.server 3000
```

Then open `http://127.0.0.1:3000`.

## Data and backups

All data stays in the browser's local storage and is not uploaded. Use the top-right backup menu to export your data before clearing browser storage or moving devices.

## Clean package

This ZIP contains only the runtime files used by the product. It excludes Git history, `node_modules`, internal PRD and feature documents, test tooling, empty route folders, duplicate release builds, embedded ZIPs, and unused assets.

The included vendor scripts provide charts and downloadable monthly PDF reports without a build step.
