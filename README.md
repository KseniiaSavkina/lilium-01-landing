# LILIUM 01 — Landing Page

A single-page product landing for LILIUM 01, a premium over-ear headphone
concept. Plain HTML and CSS, no frameworks, no build step. Design values
(colour, type, radius, spacing) are driven entirely by CSS custom properties
defined in `lilium-tokens.css`.

## Running locally

Just open `index.html` in a browser. For the hero background video and
fonts to load without any local file-access quirks, serving the folder is
safer than double-clicking the file:

```bash
python3 -m http.server 8931
```

Then visit `http://localhost:8931`.

## Folder layout

```
index.html            Page markup
styles.css             All layout and component styles
lilium-tokens.css       Design tokens (colour, type, radius, spacing) — linked before styles.css
lilium-build-brief.md   Source brief: section structure, components, acceptance checklist
assets/                 Images and video used by the page
```
