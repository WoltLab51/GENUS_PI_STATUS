# GENUS · RonGen

**healthy ✓** · seed `1a73db0db72ebf57f1611b42b97a3e7bef9ec404` · generated `2026-08-13T01:38:17.470Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1155016** · beliefs **9** · experiences **14** · proposals 37 · rules 0 · governance 48
- sealing head `047cabb17033ef77…` (event 1155016)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 43 | 14.676 | -0.39 |
| `system.disk_percent` | 13129 | 1.895 | +0.14 |
| `system.temperature` | 13128 | 1.763 | -0.02 |
| `weather.temp_outside` | 1093 | 3.211 | +0.27 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-08-07 | 1112650 | 9 | 0.5 | 1.845 |
| 2026-08-08 | 1119702 | 9 | 0.5 | 1.827 |
| 2026-08-09 | 1126763 | 9 | 0.5 | 1.809 |
| 2026-08-10 | 1133823 | 9 | 0.5 | 1.797 |
| 2026-08-11 | 1140890 | 9 | 0.5 | 1.792 |
| 2026-08-12 | 1147949 | 9 | 0.5 | 1.777 |
| 2026-08-13 | 1155016 | 9 | 0.5 | 1.763 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

