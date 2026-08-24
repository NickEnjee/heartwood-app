# Heartwood (app mirror)

Public deploy-only mirror of the Heartwood app's `field.html`, published via
GitHub Pages so it can be opened from any device without downloading a file.

This repo intentionally contains **only the app file** — no personal data,
exports, or notes. The real source of truth (with history, ADRs, and notes)
lives in the private `heartwood` repo. This one gets `index.html` copied
over and pushed whenever the app changes.

All state (tasks, branches, completions) lives in each device's own browser
`localStorage` — nothing here is server-side or shared between visitors.
