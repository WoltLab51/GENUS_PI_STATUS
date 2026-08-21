# GENUS · RonGen

**healthy ✓** · seed `3c66e4dba1d5352a9b89eef941c51822688c7887` · generated `2026-08-21T01:38:23.206Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1211489** · beliefs **9** · experiences **14** · proposals 39 · rules 0 · governance 50
- sealing head `7701d0a614a2f5af…` (event 1211489)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 51 | 13.578 | -0.41 |
| `system.disk_percent` | 15432 | 1.786 | +0.15 |
| `system.temperature` | 15431 | 1.673 | -0.01 |
| `weather.temp_outside` | 1285 | 3.235 | +0.27 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-08-15 | 1169117 | 9 | 0.5 | 1.745 |
| 2026-08-16 | 1176177 | 9 | 0.5 | 1.744 |
| 2026-08-17 | 1183237 | 9 | 0.5 | 1.74 |
| 2026-08-18 | 1190295 | 9 | 0.5 | 1.724 |
| 2026-08-19 | 1197360 | 9 | 0.5 | 1.707 |
| 2026-08-20 | 1204429 | 9 | 0.5 | 1.689 |
| 2026-08-21 | 1211489 | 9 | 0.5 | 1.673 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

