# GENUS · RonGen

**healthy ✓** · seed `1a73db0db72ebf57f1611b42b97a3e7bef9ec404` · generated `2026-07-26T01:38:07.624Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1028020** · beliefs **9** · experiences **14** · proposals 23 · rules 0 · governance 34
- sealing head `2b16408a52479a37…` (event 1028020)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 25 | 17.489 | -0.47 |
| `system.disk_percent` | 7945 | 3.002 | +0.11 |
| `system.temperature` | 7944 | 1.9 | +0.03 |
| `weather.temp_outside` | 663 | 3.211 | +0.20 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-07-19 | 978636 | 9 | 0.286 | 2.285 |
| 2026-07-20 | 985663 | 9 | 0.286 | 2.216 |
| 2026-07-21 | 992736 | 9 | 0.5 | 2.147 |
| 2026-07-22 | 999832 | 9 | 0.5 | 2.083 |
| 2026-07-23 | 1006879 | 9 | 0.5 | 2.033 |
| 2026-07-25 | 1020958 | 9 | 0.5 | 1.945 |
| 2026-07-26 | 1028020 | 9 | 0.5 | 1.9 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

