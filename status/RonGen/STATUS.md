# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-10-11T01:39:02.977Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1561423** · beliefs **9** · experiences **14** · proposals 46 · rules 0 · governance 57
- sealing head `483240c1c5613119…` (event 1561423)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 102 | 9.462 | -0.54 |
| `system.disk_percent` | 30105 | 3.41 | +0.07 |
| `system.temperature` | 30104 | 1.279 | -0.01 |
| `weather.temp_outside` | 1753 | 3.173 | +0.25 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-10-05 | 1520867 | 9 | 0.5 | 1.315 |
| 2026-10-06 | 1527631 | 9 | 0.5 | 1.309 |
| 2026-10-07 | 1534395 | 9 | 0.5 | 1.302 |
| 2026-10-08 | 1541157 | 9 | 0.5 | 1.297 |
| 2026-10-09 | 1547921 | 9 | 0.5 | 1.291 |
| 2026-10-10 | 1554664 | 9 | 0.5 | 1.286 |
| 2026-10-11 | 1561423 | 9 | 0.5 | 1.279 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

