# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-10-09T01:39:01.651Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1547921** · beliefs **9** · experiences **14** · proposals 46 · rules 0 · governance 57
- sealing head `07e532a94a8398ca…` (event 1547921)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 100 | 9.569 | -0.54 |
| `system.disk_percent` | 29529 | 3.387 | +0.08 |
| `system.temperature` | 29528 | 1.291 | -0.01 |
| `weather.temp_outside` | 1753 | 3.173 | +0.25 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-10-03 | 1507313 | 9 | 0.5 | 1.327 |
| 2026-10-04 | 1514088 | 9 | 0.5 | 1.321 |
| 2026-10-05 | 1520867 | 9 | 0.5 | 1.315 |
| 2026-10-06 | 1527631 | 9 | 0.5 | 1.309 |
| 2026-10-07 | 1534395 | 9 | 0.5 | 1.302 |
| 2026-10-08 | 1541157 | 9 | 0.5 | 1.297 |
| 2026-10-09 | 1547921 | 9 | 0.5 | 1.291 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

