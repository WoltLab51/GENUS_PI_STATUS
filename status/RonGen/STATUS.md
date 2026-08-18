# GENUS · RonGen

**healthy ✓** · seed `123ab6b5e6716c98bd53e78e297c42bc489136d6` · generated `2026-08-18T01:38:22.926Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1190295** · beliefs **9** · experiences **14** · proposals 37 · rules 0 · governance 48
- sealing head `79698a5a82493512…` (event 1190297)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 48 | 13.909 | -0.39 |
| `system.disk_percent` | 14568 | 1.725 | +0.14 |
| `system.temperature` | 14567 | 1.724 | -0.02 |
| `weather.temp_outside` | 1213 | 3.242 | +0.28 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-08-12 | 1147949 | 9 | 0.5 | 1.777 |
| 2026-08-13 | 1155016 | 9 | 0.5 | 1.763 |
| 2026-08-14 | 1162076 | 9 | 0.5 | 1.748 |
| 2026-08-15 | 1169117 | 9 | 0.5 | 1.745 |
| 2026-08-16 | 1176177 | 9 | 0.5 | 1.744 |
| 2026-08-17 | 1183237 | 9 | 0.5 | 1.74 |
| 2026-08-18 | 1190295 | 9 | 0.5 | 1.724 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

