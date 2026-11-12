# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-11-12T02:39:25.694Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1777697** · beliefs **9** · experiences **14** · proposals 47 · rules 0 · governance 58
- sealing head `afa3e42bdc6621e7…` (event 1777697)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 129 | 8.261 | -0.62 |
| `system.disk_percent` | 39333 | 3.861 | -0.05 |
| `system.temperature` | 39332 | 1.167 | -0.00 |
| `weather.temp_outside` | 1763 | 3.213 | +0.25 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-11-06 | 1737261 | 9 | 0.5 | 1.177 |
| 2026-11-07 | 1744025 | 9 | 0.5 | 1.176 |
| 2026-11-08 | 1750759 | 9 | 0.5 | 1.174 |
| 2026-11-09 | 1757503 | 9 | 0.5 | 1.173 |
| 2026-11-10 | 1764235 | 9 | 0.5 | 1.171 |
| 2026-11-11 | 1770970 | 9 | 0.5 | 1.169 |
| 2026-11-12 | 1777697 | 9 | 0.5 | 1.167 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

