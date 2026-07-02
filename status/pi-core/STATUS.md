# GENUS · pi-core

**healthy ✓** · seed `0c51aa4c00132830030d0049c9750df652f3f1d7` · generated `2026-07-02T01:37:21.508Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **298647** · beliefs **8** · experiences **9** · proposals 5 · rules 0 · governance 10
- sealing head `18fe830318b16857…` (event 298677)

## Self-knowledge

**Calibration** — 3/4 stable judgments held · accuracy **0.75** · discriminates (+0.257) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 3 | 16.781 | -0.94 |
| `system.disk_percent` | 1251 | 0.219 | +0.08 |
| `system.temperature` | 1251 | 3.385 | +0.01 |
| `weather.temp_outside` | 104 | 4.087 | -0.03 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-06-28 | 57686 | 8 | 1.0 | 1.329 |
| 2026-06-29 | 66947 | 8 | 1.0 | 1.436 |
| 2026-06-30 | 76436 | 8 | 0.8 | 1.577 |
| 2026-07-01 | 119968 | 8 | 0.75 | 1.83 |
| 2026-07-02 | 298647 | 8 | 0.75 | 3.385 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

