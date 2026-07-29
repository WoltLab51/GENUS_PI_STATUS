# GENUS · RonGen

**healthy ✓** · seed `1a73db0db72ebf57f1611b42b97a3e7bef9ec404` · generated `2026-07-29T01:38:09.446Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1049178** · beliefs **9** · experiences **14** · proposals 26 · rules 0 · governance 37
- sealing head `c4a4dd56b3c86669…` (event 1049178)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 28 | 17.033 | -0.43 |
| `system.disk_percent` | 8809 | 2.744 | +0.12 |
| `system.temperature` | 8808 | 1.779 | +0.02 |
| `weather.temp_outside` | 735 | 3.074 | +0.22 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-07-22 | 999832 | 9 | 0.5 | 2.083 |
| 2026-07-23 | 1006879 | 9 | 0.5 | 2.033 |
| 2026-07-25 | 1020958 | 9 | 0.5 | 1.945 |
| 2026-07-26 | 1028020 | 9 | 0.5 | 1.9 |
| 2026-07-27 | 1035068 | 9 | 0.5 | 1.857 |
| 2026-07-28 | 1042121 | 9 | 0.5 | 1.816 |
| 2026-07-29 | 1049178 | 9 | 0.5 | 1.779 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

