# kokudo-geo

Public map geometry for [hwys.app](https://hwys.app).

- **Production** pins a dated tag in the app (`GEO_PIN`).
- **Preview** reads `current.json` on `main`, then loads that tag.
- Never move a published tag. Same-day rebake: `v2026-09-09.2`.

`https://cdn.jsdelivr.net/gh/MrYarby/kokudo-geo@v2026-09-09/`

Do not put secrets here. OSM-derived spines; ledger catalog stays in the app.
