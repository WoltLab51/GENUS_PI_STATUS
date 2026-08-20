# GENUS · RonGen

**healthy ✓** · seed `089a2b384e1416b3cdc8eec952321b69fa9df086` · generated `2026-08-20T01:38:22.370Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1204429** · beliefs **9** · experiences **14** · proposals 39 · rules 0 · governance 50
- sealing head `0b02303bedb78bac…` (event 1204429)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 50 | 13.581 | -0.39 |
| `system.disk_percent` | 15144 | 1.752 | +0.15 |
| `system.temperature` | 15143 | 1.689 | -0.01 |
| `weather.temp_outside` | 1261 | 3.269 | +0.27 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-08-14 | 1162076 | 9 | 0.5 | 1.748 |
| 2026-08-15 | 1169117 | 9 | 0.5 | 1.745 |
| 2026-08-16 | 1176177 | 9 | 0.5 | 1.744 |
| 2026-08-17 | 1183237 | 9 | 0.5 | 1.74 |
| 2026-08-18 | 1190295 | 9 | 0.5 | 1.724 |
| 2026-08-19 | 1197360 | 9 | 0.5 | 1.707 |
| 2026-08-20 | 1204429 | 9 | 0.5 | 1.689 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

