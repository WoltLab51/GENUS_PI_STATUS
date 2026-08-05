# GENUS · RonGen

**healthy ✓** · seed `1a73db0db72ebf57f1611b42b97a3e7bef9ec404` · generated `2026-08-05T01:38:14.074Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1098529** · beliefs **9** · experiences **14** · proposals 32 · rules 0 · governance 43
- sealing head `2c713a1f96261328…` (event 1098531)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 35 | 15.977 | -0.40 |
| `system.disk_percent` | 10825 | 2.275 | +0.13 |
| `system.temperature` | 10824 | 1.803 | -0.01 |
| `weather.temp_outside` | 901 | 3.218 | +0.25 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-07-30 | 1056233 | 9 | 0.5 | 1.752 |
| 2026-07-31 | 1063285 | 9 | 0.5 | 1.739 |
| 2026-08-01 | 1070347 | 9 | 0.5 | 1.746 |
| 2026-08-02 | 1077395 | 9 | 0.5 | 1.759 |
| 2026-08-03 | 1084443 | 9 | 0.5 | 1.763 |
| 2026-08-04 | 1091486 | 9 | 0.5 | 1.777 |
| 2026-08-05 | 1098529 | 9 | 0.5 | 1.803 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

