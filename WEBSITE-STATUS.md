# Website Status

This file tracks where the project stands. The `website-bauen` skill reads it on every run and continues from here.

Status: ✅ done · 🔄 in progress · ⬜ open

| Phase | Name | Status | Date |
|---|---|---|---|
| 0 | Setup | 🔄 | 2026-10-28 |
| 1 | Foundation (brand) | ⬜ | |
| 2 | Research | ⬜ | |
| 3 | Copy | ⬜ | |
| 4 | Design direction | ⬜ | |
| 5 | Build | ⬜ | |
| 6 | Review & polish | ⬜ | |
| 7 | Go-live | ⬜ | |
| 8 | After launch | ⬜ | |

## Starting point

- Project: general hub site for all Airbnb listings across several properties (overview of all listings)
- Existing website or brand: _open — see questions_
- Main goal of the site: _open — see questions_
- Hosting: _open — Netlify connector is available in this environment_
- Tools: impeccable ✅ (available as skill) · Playwright ✅ (Node pre-installed; Python package installing) · DataForSEO ⬜ (connector present, use confirmed in Phase 2) · Hosting MCP ⬜ (Netlify connector present) · Form target ⬜
- Also available: PriceLabs connector (can pull the real listing list)

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

## Open questions

- See Phase 0 questions (existing brand, main goal, hosting, research data).

## Update workflow after go-live

1. Change the page and `texte.md`
2. `python deploy/build.py`
3. Upload:
4. Clear cache:
5. Check live
