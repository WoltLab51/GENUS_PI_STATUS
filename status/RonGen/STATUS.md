# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-09-05T01:38:38.677Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1316895** · beliefs **9** · experiences **14** · proposals 41 · rules 0 · governance 52
- sealing head `76004ce1cdc33fd4…` (event 1316895)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 66 | 11.783 | -0.43 |
| `system.disk_percent` | 19737 | 2.627 | +0.19 |
| `system.temperature` | 19736 | 1.533 | +0.00 |
| `weather.temp_outside` | 1644 | 3.182 | +0.25 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-08-30 | 1274613 | 9 | 0.5 | 1.604 |
| 2026-08-31 | 1281663 | 9 | 0.5 | 1.594 |
| 2026-09-01 | 1288715 | 9 | 0.5 | 1.58 |
| 2026-09-02 | 1295767 | 9 | 0.5 | 1.568 |
| 2026-09-03 | 1302819 | 9 | 0.5 | 1.555 |
| 2026-09-04 | 1309871 | 9 | 0.5 | 1.544 |
| 2026-09-05 | 1316895 | 9 | 0.5 | 1.533 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

