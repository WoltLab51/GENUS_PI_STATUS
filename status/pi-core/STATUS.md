# GENUS · pi-core

**healthy ✓** · seed `263d33cf7b8cf68efb6b45680bc8d1dee1e09698` · generated `2026-07-04T01:37:29.597Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **469458** · beliefs **9** · experiences **9** · proposals 8 · rules 0 · governance 11
- sealing head `2860c74dbc1c3ae9…` (event 469458)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.257) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 5 | 21.651 | -0.50 |
| `system.disk_percent` | 1825 | 1.027 | +0.17 |
| `system.temperature` | 1825 | 3.775 | -0.00 |
| `weather.temp_outside` | 152 | 4.32 | -0.01 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-06-28 | 57686 | 8 | 1.0 | 1.329 |
| 2026-06-29 | 66947 | 8 | 1.0 | 1.436 |
| 2026-06-30 | 76436 | 8 | 0.8 | 1.577 |
| 2026-07-01 | 119968 | 8 | 0.75 | 1.83 |
| 2026-07-02 | 298647 | 8 | 0.75 | 3.385 |
| 2026-07-03 | 443660 | 8 | 0.75 | 4.093 |
| 2026-07-04 | 469458 | 9 | 0.5 | 3.775 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

