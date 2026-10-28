# Website Status

This file tracks where the project stands. The `website-bauen` skill reads it on every run and continues from here.

Status: ✅ done · 🔄 in progress · ⬜ open

| Phase | Name | Status | Date |
|---|---|---|---|
| 0 | Setup | ✅ | 2026-10-28 |
| 1 | Foundation (brand) | 🔄 | 2026-10-28 |
| 2 | Research | ⬜ | |
| 3 | Copy | ⬜ | |
| 4 | Design direction | ⬜ | |
| 5 | Build | ⬜ | |
| 6 | Review & polish | ⬜ | |
| 7 | Go-live | ⬜ | |
| 8 | After launch | ⬜ | |

## Starting point

- Project: general hub site for all Airbnb listings across several properties (overview of all listings)
- Existing website or brand: 5 Airbnb listings on 2 properties. Each property has / will have its own website and identity:
  - Penthouse El Nido — IG https://www.instagram.com/penthouse.elnido/
  - Casa Maligaya — IG https://www.instagram.com/casa.maligaya
  - Airbnb host profile: https://www.airbnb.com/users/profile/1469882530907914187
  - This hub site needs a NEW umbrella brand (Phase 1b: name first). Repo name "elnido-stays" is a working title only.
- Main goal of the site: (a) showcase all listings and send guests to Airbnb now; (b) direct inquiries/bookings later, once a PMS is in place. Must scale to more properties, incl. third-party properties under management.
- Hosting: Cloudflare (Pages) — Netlify account is maxed out. Domains not bought yet.
- Tools: impeccable ✅ (available as skill) · Playwright ✅ (Node + Python; Python needs executable_path='/opt/pw-browsers/chromium') · DataForSEO ⬜ (connector present, use confirmed 2026-10-28) · Hosting MCP ⬜ (Cloudflare, to connect in Phase 7) · Form target ⬜
- PriceLabs connector: account currently returns 0 listings.
- Network: airbnb.com and instagram.com are blocked in this cloud environment; listing data must come from the user or be allowed in the network settings.

## Brand

| Role | Value |
|---|---|
| Primary color | |
| Accent | |
| Light surface | |
| Text | |
| Headings | |
| Body text | |
| Traits | |

## Decisions

Every decision with a date, so it isn't re-discussed.

- 2026-10-28: Start a new website project in this repo (`elnido-stays`) for an overview of all listings.
- 2026-10-28: Main goal = showcase + link to Airbnb now; direct booking later with a PMS.
- 2026-10-28: Hosting on Cloudflare; user buys domains.
- 2026-10-28: Use DataForSEO for research.

## Open questions

- Phase 1 questions (umbrella name, visitors, proof, listing details) — asked 2026-10-28.

## Update workflow after go-live

1. Change the page and `texte.md`
2. `python deploy/build.py`
3. Upload:
4. Clear cache:
5. Check live
