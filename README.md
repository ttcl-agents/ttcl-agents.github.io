# NeurIPS 2026 TTCL — Towards Test-Time Continual Learning Agents

Website for the **NeurIPS 2026 Workshop on Towards Test-Time Continual Learning Agents (TTCL)**, Atlanta, GA — December 13, 2026.

Live site: https://ttcl-agents.github.io

## Structure

- `index.html` — the full single-page site (about, CFP, dates, challenge cancellation notice, speakers, schedule, organizers, sponsor, contact)
- `assets/css/style.css` — standard academic workshop styling (white background, navy/blue accents, Lato, circular headshots)
- `assets/img/` — speaker/organizer headshots, sourced from each person's homepage and downscaled to ≤600px (falls back to initials if an image is missing), plus the Lambda sponsor logo (`lambda-logo.svg`, recolored dark from Lambda's official white SVG)

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

Deployed automatically via GitHub Pages from the `master` branch.
