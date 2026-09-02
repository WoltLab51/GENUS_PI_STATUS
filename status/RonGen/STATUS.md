# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-09-02T01:38:36.674Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1295767** · beliefs **9** · experiences **14** · proposals 41 · rules 0 · governance 52
- sealing head `e9d5d760aa898b7a…` (event 1295769)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 63 | 12.066 | -0.43 |
| `system.disk_percent` | 18873 | 2.498 | +0.19 |
| `system.temperature` | 18872 | 1.568 | +0.00 |
| `weather.temp_outside` | 1572 | 3.209 | +0.26 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-08-27 | 1253440 | 9 | 0.5 | 1.644 |
| 2026-08-28 | 1260507 | 9 | 0.5 | 1.63 |
| 2026-08-29 | 1267559 | 9 | 0.5 | 1.617 |
| 2026-08-30 | 1274613 | 9 | 0.5 | 1.604 |
| 2026-08-31 | 1281663 | 9 | 0.5 | 1.594 |
| 2026-09-01 | 1288715 | 9 | 0.5 | 1.58 |
| 2026-09-02 | 1295767 | 9 | 0.5 | 1.568 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

