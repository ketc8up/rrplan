# Who Delivers Under Pressure: RR recruitment dashboard

SupeRR Selector Season 2, Round 1 submission: Rajasthan Royals recruitment analytics for the IPL 2027 auction.

**Live dashboard:** https://ketc8up.github.io/rrplan/

**Full report (PDF):** [SupeRR_Selector_S2_Pressure_Report.pdf](SupeRR_Selector_S2_Pressure_Report.pdf)

## What is inside

The dashboard is an interactive version of the methodology report. It covers:

- **Top-10 pressure lists** for batters and bowlers. Each one links to a player profile with ratings, intervals and pressure splits.
- **How pressure is measured.** A win-probability model rates every ball by how much it could swing the match. A player's rating combines performance on pressure balls, lift over ordinary balls and consistency.
- **Robustness:** sensitivity tests, split-half reliability, out-of-fold validation and an independent recount of the headline numbers.
- **RR plan.** This section uses the IPL 2027 retentions announced on 17 November 2026. RR has 6 open slots, at most 3 of them overseas, and a purse of ₹27.05 cr. Only players who can actually be bought are recommended. Players are left out if they were retained by another franchise, come from Pakistan or Bangladesh, are committed to Cricket Australia (Starc, Head), are injured (Bethell), or are ineligible under IPL rules (Brook, Stokes).
- **Fan pulse:** fan and expert reaction set against the data, with sources.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole dashboard in one file, with data, styles, scripts and photos embedded. It needs no build step or server and also opens offline. |
| `SupeRR_Selector_S2_Pressure_Report.pdf` | The full methodology and findings report, linked from the dashboard footer. |

## Deep links

Each section and player has its own URL. Examples:

- `#/rr`: the RR auction plan
- `#/batting/50284`: Vaibhav Sooryavanshi
- `#/bowling/781`: Sunil Narine

## Data and caveats

- Ratings come from the supplied SupeRR Selector data pack plus public Cricsheet ball-by-ball data for other T20 leagues.
- Auction availability is as of 18 November 2026. The official auction register is due on 3 December 2026.
- Price bands in the RR plan are judgement-based estimates, not model output.
