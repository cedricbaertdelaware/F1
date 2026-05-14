# 🏎️ Racing Hub — Live Formula 1 Dashboard

A real-time Formula 1 dashboard for the 2026 season, built as a single-page HTML application with live data from multiple F1 APIs.

**[→ Open Racing Hub](https://cedricbaertdelaware.github.io/F1/F1.html)**

## Features

- **Live Standings** — Driver and Constructor championship standings updated after each race
- **Race Results** — Full classification with gap times, DNF/DNS status, and points scored
- **2026 Calendar** — Complete race schedule with countdown timer to the next Grand Prix
- **Circuit Cards** — Flip cards with track info, lap records, and circuit descriptions
- **Driver Profiles** — Detailed modal with stats, team info, and headshot photos
- **Head-to-Head Compare** — Side-by-side driver comparison with visual stat cards
- **Favourites** — Star your favourite drivers for quick access on the home page
- **Dark Theme** — Premium dark UI with team-coloured accents and smooth animations

## Data Sources

| Source | Used for | Priority |
|--------|----------|----------|
| [OpenF1 API](https://openf1.org) | Championship standings, race results, session data | Primary |
| [Jolpica F1 API](https://api.jolpi.ca/ergast/) | Race calendar, schedule data | Fallback |

Driver headshots and team colours are embedded directly in the HTML from the official F1 media CDN for instant loading without API dependency.

## Tech Stack

- **Zero dependencies** — Pure HTML, CSS, and vanilla JavaScript in a single file
- **No build step** — Just open `F1.html` in a browser or deploy to any static host
- **Responsive** — Works on desktop, tablet, and mobile
- **GitHub Pages** — Hosted for free with automatic deployments

## Local Development

```
git clone https://github.com/cedricbaertdelaware/F1.git
cd F1
open F1.html
```

No server required — it runs entirely in the browser.

## License

Personal project — not affiliated with Formula 1, FIA, or any F1 team.

---

Built with ☕ and 🏁 by [Cédric Baert](https://github.com/cedricbaertdelaware)
