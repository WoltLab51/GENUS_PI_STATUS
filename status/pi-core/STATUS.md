# GENUS · pi-core

**healthy ✓** · seed `2e34394da697d3484b952ef6f4dc69ff3e432453` · generated `2026-07-03T01:37:28.658Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **443660** · beliefs **8** · experiences **9** · proposals 5 · rules 0 · governance 10
- sealing head `f6dd3706708690a1…` (event 443702)

## Self-knowledge

**Calibration** — 3/4 stable judgments held · accuracy **0.75** · discriminates (+0.257) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 4 | 23.813 | -0.67 |
| `system.disk_percent` | 1537 | 0.677 | +0.14 |
| `system.temperature` | 1537 | 4.093 | -0.04 |
| `weather.temp_outside` | 128 | 4.137 | +0.01 |

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

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

