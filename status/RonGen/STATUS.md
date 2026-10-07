# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-10-07T01:39:00.684Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1534395** · beliefs **9** · experiences **14** · proposals 46 · rules 0 · governance 57
- sealing head `86239b3d8113f88c…` (event 1534395)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 98 | 9.677 | -0.53 |
| `system.disk_percent` | 28953 | 3.363 | +0.09 |
| `system.temperature` | 28952 | 1.302 | -0.01 |
| `weather.temp_outside` | 1753 | 3.173 | +0.25 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-10-01 | 1493805 | 9 | 0.5 | 1.34 |
| 2026-10-02 | 1500559 | 9 | 0.5 | 1.333 |
| 2026-10-03 | 1507313 | 9 | 0.5 | 1.327 |
| 2026-10-04 | 1514088 | 9 | 0.5 | 1.321 |
| 2026-10-05 | 1520867 | 9 | 0.5 | 1.315 |
| 2026-10-06 | 1527631 | 9 | 0.5 | 1.309 |
| 2026-10-07 | 1534395 | 9 | 0.5 | 1.302 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

