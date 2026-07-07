# LeanR — Executive Retention Intelligence

A self-contained, single-file executive retention dashboard for LeanR, built from monthly
cohort renewal data (Jun 2024 → Jun 2026).

- **Live entry point:** `index.html` (no build step, no dependencies)
- Cohort retention triangle, live KPIs, renewal/retention funnel, level forecast (SES),
  auto red-flag engine, and prioritized recommendations.
- Facts are computed from the source data; AI insights & forecasts are clearly labelled.

## Deploy on Vercel
This is a static site. On Vercel, import the repo and deploy with **no framework preset**
(Framework Preset: *Other*, no build command, output directory: root). Vercel serves
`index.html` at `/`.
