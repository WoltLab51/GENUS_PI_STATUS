# GENUS · RonGen

**healthy ✓** · seed `1a73db0db72ebf57f1611b42b97a3e7bef9ec404` · generated `2026-08-09T01:38:15.590Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1126763** · beliefs **9** · experiences **14** · proposals 35 · rules 0 · governance 46
- sealing head `d0d9fa5aeb6e4bc5…` (event 1126763)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 39 | 15.355 | -0.39 |
| `system.disk_percent` | 11977 | 2.066 | +0.14 |
| `system.temperature` | 11976 | 1.809 | -0.01 |
| `weather.temp_outside` | 997 | 3.222 | +0.25 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-08-03 | 1084443 | 9 | 0.5 | 1.763 |
| 2026-08-04 | 1091486 | 9 | 0.5 | 1.777 |
| 2026-08-05 | 1098529 | 9 | 0.5 | 1.803 |
| 2026-08-06 | 1105596 | 9 | 0.5 | 1.842 |
| 2026-08-07 | 1112650 | 9 | 0.5 | 1.845 |
| 2026-08-08 | 1119702 | 9 | 0.5 | 1.827 |
| 2026-08-09 | 1126763 | 9 | 0.5 | 1.809 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

