# Cognition SDR Intelligence Hub

A single-page, interactive sales intelligence brief built for a Cognition SDR interview.

Open `index.html` directly in any modern browser — no build step, no server, no dependencies beyond the Tailwind CDN and Google Fonts.

## Sections

1. **Devin ROI Calculator** — models hours / cost / annual ROI from Devin's documented benchmarks (10× migrations, 20× security fixes, 60→90% test coverage).
2. **Target Account Intelligence** — top 10 entertainment, media and financial services accounts with pain points, Devin use cases, and cold-open lines.
3. **Competitive Battle Card** — Devin vs GitHub Copilot vs Cursor.
4. **Objection Handler** — the five most common objections and how to answer them.
5. **30 / 60 / 90 Day Plan** — ramp plan for the first 90 days at Cognition.

## Running locally

```bash
# option A: open directly
xdg-open index.html     # Linux
open index.html         # macOS

# option B: serve
python3 -m http.server 8000
# then visit http://localhost:8000
```
