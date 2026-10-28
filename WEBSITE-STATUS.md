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
- 2026-10-28: Scope El Nido only. Listings: Casa Maligaya (private villa + boutique loft); second property "Cliff Tower" (renaming, 3 listings incl. Penthouse).
- 2026-10-28: No "Airbnb" in the name (trademark). Owner leans "El Nido Stays"; shortlist in recherche/namen.md.
- 2026-10-28: Positioning: elevated / luxe end of El Nido, owner-designed and owner-built, personal family hosting, one shared design language.
- 2026-10-28: Plans: shared Instagram, blog for SEO/GEO, property sites link here ("dates unavailable → see our other stays"), search/booking engine later.
- 2026-10-28: Favourite name: El Nido Collection (with "El"); also buy elnidostays.com as a redirect if free. Owner checks domains personally.
- 2026-10-28: NAME CHOSEN: El Nido Collection. elnidocollection.com is available; owner to buy via Cloudflare Registrar.
- 2026-10-28: No design references yet; owner imagines an Airbnb-like overview. Collect references in Phase 2.

## Open questions

- Owner: buy elnidocollection.com (+ elnidostays.com if free), secure @elnidocollection on Instagram, IPOPHL trademark search (watch El Nido Resorts).
- Logo round 1: owner picks 1–2 concepts from logo/entwuerfe/runde-1.html.
- Still open from Phase 1: listing names + Airbnb links, proof (Superhost, rating, reviews), what stays off the page.

## Update workflow after go-live

1. Change the page and `texte.md`
2. `python deploy/build.py`
3. Upload:
4. Clear cache:
5. Check live
