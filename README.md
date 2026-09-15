# Series Forecast

A match-analysis workbench for exploring seeded tournament scenarios across a small multi-title team catalogue.

## What it demonstrates

- Repeatable match-path simulation using explicit seeds and horizons.
- Team comparison using rating, recent form and uncertainty.
- Head-to-head matrices and bracket sensitivity views.
- Accessible controls, sortable tables and non-visual chart summaries.

Teams are recognisable reference labels, but all ratings, fixtures, prices, posts and outcomes are synthetic. Nothing here is live betting data or wagering advice.

## Run locally

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`. The published version is available through GitHub Pages.

## Engineering note

The deterministic scenario kernel is shared with four sibling studies. This application owns the team-rating adapter, match terminology and tournament-specific views.
