# Sweet EV Rides — Client P&L Model

Interactive P&L calculator for Sweet EV Rides client conversations. Single HTML file, no dependencies, runs in any browser.

**Live tool:** enable GitHub Pages (Settings → Pages → Deploy from branch → main) and share the URL with the team.

## Client types

- **Investor** — owns/finances the vehicle, Sweet EV operates it. Revenue = daily rent + charging fees from the renter. Net profit split 50/50 per Revenue Share Agreement; all figures show the client's share.
- **Driver** — rents the vehicle, keeps 100% of Uber earnings, pays daily rent + charging fees.
- **VIP / DFY Student** — owns the fleet vehicle. One-time program fee (DFY $7,000 / DWY $3,000) plus optional ongoing management fee.

## Key assumptions (from Sweet EV pro forma — illustrative only)

| Item | Default |
|---|---|
| Daily rent | $150/day |
| Rental days/month | 26 (KB: 25–30) |
| Car note | $1,000/mo |
| Insurance reserve | $350/mo |
| Maintenance reserve | $250/mo |
| Sweet EV ops & concierge | $400/mo |
| Vehicle cost | $30,000 |

A warning banner appears when projected rental income exceeds ~$4,500/mo pro forma assumptions.

## Features

- Auto-recalculating summary cards (revenue, expenses, net, margin, ROI, break-even, payback, 36-month cumulative)
- Monthly + annual breakdown table
- Export to PDF (print dialog)
- Copy shareable link — encodes the full scenario in the URL so a teammate opens the exact same numbers

## Requesting features

Open a GitHub Issue with what you need and why. Changes are made centrally and deployed to the live URL — do not edit local copies, they fragment versions.

## Compliance

All outputs are illustrative projections, never guarantees. Do not remove the disclaimer. Never present figures as guaranteed returns — see the Sweet EV safe-language guidelines.

---
v1.0 — June 12, 2026
