# Ternary — Design Mockups

Static, self-contained design mockups for Ternary's marketing **hub pages**
(Capabilities · Solutions · Industries · Scales).

These are **design explorations only** — not the production site, and not connected to any
Ternary application code, CMS, or credentials. Each file is a single standalone HTML page.

## View

- **Locally:** open `index.html` (or any `*.html`) in a browser — no build step, no server.
  The only external dependency is Google Fonts (Poppins / Inter / Geist Mono), which load over the web.
- **Hosted:** deploy this repo as a static site (e.g. Vercel — no framework, output = repo root).
  `index.html` is the landing page; each mockup is reachable at `/<filename>.html`.

## Contents

| Hub | Files |
| --- | --- |
| Capabilities | `capabilities-hub-bold.html`, `capabilities-hub-ternary.html`, `capabilities-hub-elevated.html` |
| Solutions | `solutions-hub-bold.html`, `solutions-hub-ternary.html` |
| Industries | `industries-hub-bold.html` |
| Scales | `scales-hub-iso.html`, `scales-hub-signature.html`, `scales-hub-bold.html`, `scales-hub-refined.html`, `scales-hub-ternary.html` |

## Design system

Warm dark-mode-first — Obsidian `#141208` ground, Eggshell `#F4F3EC` foreground, warm-neutral ramp.
Poppins (display), Inter (body/UI), Geist Mono (labels/numbering). Colour is limited to intentional
gradient panels; motion is transform/opacity only and respects `prefers-reduced-motion`.
