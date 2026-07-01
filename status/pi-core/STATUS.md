# GENUS · pi-core

**healthy ✓** · seed `cd0b4d2f1b3ad4206b8f32c89b1fd966281e5db1` · generated `2026-07-01T01:37:11.475Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **119968** · beliefs **8** · experiences **6** · proposals 5 · rules 0 · governance 10
- sealing head `512559e261630cd0…` (event 119978)

## Self-knowledge

**Calibration** — 3/4 stable judgments held · accuracy **0.75** · discriminates (+0.285) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 2 | 22.472 | -1.64 |
| `system.disk_percent` | 963 | 0.092 | -0.50 |
| `system.temperature` | 963 | 1.83 | -0.12 |
| `weather.temp_outside` | 80 | 3.998 | -0.01 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-06-28 | 57686 | 8 | 1.0 | 1.329 |
| 2026-06-29 | 66947 | 8 | 1.0 | 1.436 |
| 2026-06-30 | 76436 | 8 | 0.8 | 1.577 |
| 2026-07-01 | 119968 | 8 | 0.75 | 1.83 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

