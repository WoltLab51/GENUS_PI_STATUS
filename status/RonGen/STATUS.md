# GENUS · RonGen

**healthy ✓** · seed `1a73db0db72ebf57f1611b42b97a3e7bef9ec404` · generated `2026-07-27T01:38:08.604Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1035068** · beliefs **9** · experiences **14** · proposals 23 · rules 0 · governance 34
- sealing head `45947bf807eeb8b0…` (event 1035068)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 26 | 17.239 | -0.45 |
| `system.disk_percent` | 8233 | 2.913 | +0.11 |
| `system.temperature` | 8232 | 1.857 | +0.02 |
| `weather.temp_outside` | 687 | 3.16 | +0.21 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-07-20 | 985663 | 9 | 0.286 | 2.216 |
| 2026-07-21 | 992736 | 9 | 0.5 | 2.147 |
| 2026-07-22 | 999832 | 9 | 0.5 | 2.083 |
| 2026-07-23 | 1006879 | 9 | 0.5 | 2.033 |
| 2026-07-25 | 1020958 | 9 | 0.5 | 1.945 |
| 2026-07-26 | 1028020 | 9 | 0.5 | 1.9 |
| 2026-07-27 | 1035068 | 9 | 0.5 | 1.857 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

