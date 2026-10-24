# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-10-24T01:39:11.430Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1649272** · beliefs **9** · experiences **14** · proposals 47 · rules 0 · governance 58
- sealing head `3e35cc58017b9a34…` (event 1649272)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 115 | 8.833 | -0.58 |
| `system.disk_percent` | 33849 | 3.527 | +0.03 |
| `system.temperature` | 33848 | 1.218 | -0.00 |
| `weather.temp_outside` | 1762 | 3.21 | +0.25 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-10-18 | 1608756 | 9 | 0.5 | 1.243 |
| 2026-10-19 | 1615519 | 9 | 0.5 | 1.238 |
| 2026-10-20 | 1622294 | 9 | 0.5 | 1.234 |
| 2026-10-21 | 1629024 | 9 | 0.5 | 1.23 |
| 2026-10-22 | 1635783 | 9 | 0.5 | 1.226 |
| 2026-10-23 | 1642519 | 9 | 0.5 | 1.222 |
| 2026-10-24 | 1649272 | 9 | 0.5 | 1.218 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

