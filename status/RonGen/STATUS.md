# GENUS · RonGen

**healthy ✓** · seed `1a73db0db72ebf57f1611b42b97a3e7bef9ec404` · generated `2026-07-30T01:38:09.620Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1056233** · beliefs **9** · experiences **14** · proposals 27 · rules 0 · governance 38
- sealing head `95e084a1bc5ed0c6…` (event 1056233)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 29 | 16.652 | -0.40 |
| `system.disk_percent` | 9097 | 2.667 | +0.12 |
| `system.temperature` | 9096 | 1.752 | +0.02 |
| `weather.temp_outside` | 759 | 3.15 | +0.23 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-07-23 | 1006879 | 9 | 0.5 | 2.033 |
| 2026-07-25 | 1020958 | 9 | 0.5 | 1.945 |
| 2026-07-26 | 1028020 | 9 | 0.5 | 1.9 |
| 2026-07-27 | 1035068 | 9 | 0.5 | 1.857 |
| 2026-07-28 | 1042121 | 9 | 0.5 | 1.816 |
| 2026-07-29 | 1049178 | 9 | 0.5 | 1.779 |
| 2026-07-30 | 1056233 | 9 | 0.5 | 1.752 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

