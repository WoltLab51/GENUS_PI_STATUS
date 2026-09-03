# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-09-03T01:38:37.592Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1302819** · beliefs **9** · experiences **14** · proposals 41 · rules 0 · governance 52
- sealing head `b134f18c6511fcce…` (event 1302819)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 64 | 11.923 | -0.42 |
| `system.disk_percent` | 19161 | 2.543 | +0.19 |
| `system.temperature` | 19160 | 1.555 | +0.00 |
| `weather.temp_outside` | 1596 | 3.209 | +0.25 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-08-28 | 1260507 | 9 | 0.5 | 1.63 |
| 2026-08-29 | 1267559 | 9 | 0.5 | 1.617 |
| 2026-08-30 | 1274613 | 9 | 0.5 | 1.604 |
| 2026-08-31 | 1281663 | 9 | 0.5 | 1.594 |
| 2026-09-01 | 1288715 | 9 | 0.5 | 1.58 |
| 2026-09-02 | 1295767 | 9 | 0.5 | 1.568 |
| 2026-09-03 | 1302819 | 9 | 0.5 | 1.555 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

