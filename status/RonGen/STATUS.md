# GENUS · RonGen

**healthy ✓** · seed `123ab6b5e6716c98bd53e78e297c42bc489136d6` · generated `2026-08-17T01:38:20.496Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1183237** · beliefs **9** · experiences **14** · proposals 37 · rules 0 · governance 48
- sealing head `77b2529c92e0cb35…` (event 1183237)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 47 | 14.056 | -0.39 |
| `system.disk_percent` | 14280 | 1.756 | +0.14 |
| `system.temperature` | 14279 | 1.74 | -0.02 |
| `weather.temp_outside` | 1189 | 3.214 | +0.29 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-08-11 | 1140890 | 9 | 0.5 | 1.792 |
| 2026-08-12 | 1147949 | 9 | 0.5 | 1.777 |
| 2026-08-13 | 1155016 | 9 | 0.5 | 1.763 |
| 2026-08-14 | 1162076 | 9 | 0.5 | 1.748 |
| 2026-08-15 | 1169117 | 9 | 0.5 | 1.745 |
| 2026-08-16 | 1176177 | 9 | 0.5 | 1.744 |
| 2026-08-17 | 1183237 | 9 | 0.5 | 1.74 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

