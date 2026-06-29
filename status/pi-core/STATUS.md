# GENUS · pi-core

**healthy ✓** · seed `13ec5ee618a40296ff3f0dbb638cbb63e7e7a37e` · generated `2026-06-29T07:10:13.903Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **61954** · beliefs **8** · experiences **6** · proposals 5 · rules 0 · governance 10
- sealing head `e1b06658faad5343…` (event 61954)

## Self-knowledge

**Calibration** — 5/5 stable judgments held · accuracy **1.0** · discriminates (+0.359) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 1 | 14.5 | — |
| `system.disk_percent` | 462 | 0.064 | — |
| `system.temperature` | 462 | 1.359 | -0.01 |
| `weather.temp_outside` | 39 | 1.775 | +0.58 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-06-28 | 57686 | 8 | 1.0 | 1.329 |
| 2026-06-29 | 61954 | 8 | 1.0 | 1.359 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

