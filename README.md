# LNCELOT — Africa's Oracle

Three-surface platform for African prediction markets and intelligence.

## File map

- `index.html` — landing page (Africa's Oracle hero, surface cards, signup)
- `markets.html` — prediction floor (63 markets, swarm widget, leaderboard)
- `globe.html` — Oracle 3D globe (54 nations, Green T network, intel panels)
- `oracle-cape.html` — Cape of Good Hope God's Eye View (chokepoint dashboard)
- `oracle-hormuz.html` — Strait of Hormuz God's Eye View
- `oracle-malacca.html` — Strait of Malacca God's Eye View
- `vercel.json` / `netlify.toml` — host configs

## Deploy

Vercel preset = Other. Output dir blank. Auto-detects HTML.
Custom domain `lncelot.africa`: A `@` → `76.76.21.21`, CNAME `www` → `cname.vercel-dns.com`.

## Update flow

Edit any HTML in GitHub browser → commit → Vercel auto-deploys in ~30s.

## Tech

- Leaflet 1.9.4 (maps, oracle dashboards)
- Globe.gl + Three.js r128 (3D globe)
- Inter + JetBrains Mono fonts (Google Fonts)
- Vanilla JS state — no build step, no npm

## Live data wiring (next session)

- AISStream.io WebSocket for real vessel positions
- NASA FIRMS satellite fire detection
- ACLED conflict events API
- OpenSky flights ADS-B (already on globe.html)
- Yahoo Finance for oil/commodity sparklines
