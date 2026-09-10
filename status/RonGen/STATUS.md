# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-09-10T01:38:42.783Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1351885** · beliefs **9** · experiences **14** · proposals 41 · rules 0 · governance 52
- sealing head `1566e92acb5b2c63…` (event 1351885)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 71 | 11.371 | -0.45 |
| `system.disk_percent` | 21177 | 2.809 | +0.18 |
| `system.temperature` | 21176 | 1.483 | +0.00 |
| `weather.temp_outside` | 1745 | 3.157 | +0.26 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-09-04 | 1309871 | 9 | 0.5 | 1.544 |
| 2026-09-05 | 1316895 | 9 | 0.5 | 1.533 |
| 2026-09-06 | 1323939 | 9 | 0.5 | 1.522 |
| 2026-09-07 | 1330983 | 9 | 0.5 | 1.511 |
| 2026-09-08 | 1338027 | 9 | 0.5 | 1.5 |
| 2026-09-09 | 1345069 | 9 | 0.5 | 1.494 |
| 2026-09-10 | 1351885 | 9 | 0.5 | 1.483 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

