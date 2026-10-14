# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-10-14T01:39:04.190Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1581739** · beliefs **9** · experiences **14** · proposals 47 · rules 0 · governance 58
- sealing head `e5d9789fd6552357…` (event 1581739)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 105 | 9.315 | -0.55 |
| `system.disk_percent` | 30969 | 3.441 | +0.06 |
| `system.temperature` | 30968 | 1.263 | -0.01 |
| `weather.temp_outside` | 1756 | 3.183 | +0.25 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-10-08 | 1541157 | 9 | 0.5 | 1.297 |
| 2026-10-09 | 1547921 | 9 | 0.5 | 1.291 |
| 2026-10-10 | 1554664 | 9 | 0.5 | 1.286 |
| 2026-10-11 | 1561423 | 9 | 0.5 | 1.279 |
| 2026-10-12 | 1568173 | 9 | 0.5 | 1.274 |
| 2026-10-13 | 1574949 | 9 | 0.5 | 1.268 |
| 2026-10-14 | 1581739 | 9 | 0.5 | 1.263 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

