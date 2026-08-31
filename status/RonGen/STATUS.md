# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-08-31T01:38:35.836Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1281663** · beliefs **9** · experiences **14** · proposals 41 · rules 0 · governance 52
- sealing head `4d2f960b8fda902c…` (event 1281665)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 61 | 12.242 | -0.42 |
| `system.disk_percent` | 18297 | 2.4 | +0.20 |
| `system.temperature` | 18296 | 1.594 | -0.00 |
| `weather.temp_outside` | 1524 | 3.223 | +0.26 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-08-25 | 1239322 | 9 | 0.5 | 1.665 |
| 2026-08-26 | 1246382 | 9 | 0.5 | 1.653 |
| 2026-08-27 | 1253440 | 9 | 0.5 | 1.644 |
| 2026-08-28 | 1260507 | 9 | 0.5 | 1.63 |
| 2026-08-29 | 1267559 | 9 | 0.5 | 1.617 |
| 2026-08-30 | 1274613 | 9 | 0.5 | 1.604 |
| 2026-08-31 | 1281663 | 9 | 0.5 | 1.594 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

