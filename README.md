# LinkedIn Analytics Dashboard

Real-time engagement tracking for an autonomous LinkedIn publishing system.

## What It Shows

- **Post Performance** — Likes, comments, shares measured at 25h / 49h / 73h intervals
- **Pipeline Health** — Briefs queued, posts published today, publishing errors
- **A/B Experiments** — Side-by-side comparison of content experiments with statistical confidence
- **Content Calendar** — Visual timeline of published and scheduled posts

## Architecture

Data flows from the LinkedIn autonomous system:

1. **Trigger.dev** collects metrics via Apify LinkedIn scraper
2. **Supabase** stores post data, metrics snapshots, and experiment results
3. **Dashboard** fetches via Supabase REST API (real-time updates)

## Tech Stack

- HTML / CSS / JavaScript
- Supabase REST API (read-only anon key)
- GitHub Pages

## Live

**[View Dashboard →](https://saafir-coder.github.io/linkedin-dashboard/)**

## License

MIT
