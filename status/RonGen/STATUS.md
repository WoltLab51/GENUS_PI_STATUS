# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-10-01T01:38:56.236Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1493805** · beliefs **9** · experiences **14** · proposals 44 · rules 0 · governance 55
- sealing head `93b25d9d88f59630…` (event 1493805)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 92 | 9.984 | -0.51 |
| `system.disk_percent` | 27225 | 3.281 | +0.11 |
| `system.temperature` | 27224 | 1.34 | -0.00 |
| `weather.temp_outside` | 1751 | 3.165 | +0.25 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-09-25 | 1453261 | 9 | 0.5 | 1.375 |
| 2026-09-26 | 1460017 | 9 | 0.5 | 1.372 |
| 2026-09-27 | 1466771 | 9 | 0.5 | 1.366 |
| 2026-09-28 | 1473525 | 9 | 0.5 | 1.36 |
| 2026-09-29 | 1480281 | 9 | 0.5 | 1.354 |
| 2026-09-30 | 1487037 | 9 | 0.5 | 1.347 |
| 2026-10-01 | 1493805 | 9 | 0.5 | 1.34 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

