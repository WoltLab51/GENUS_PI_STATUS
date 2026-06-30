# GENUS · pi-core

**healthy ✓** · seed `67321415f0548e9f2d0fd8f4939d033b13e92164` · generated `2026-06-30T01:37:08.935Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **76436** · beliefs **8** · experiences **6** · proposals 5 · rules 0 · governance 10
- sealing head `f156779e00969925…` (event 76436)

## Self-knowledge

**Calibration** — 4/5 stable judgments held · accuracy **0.8** · discriminates (+0.359) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 1 | 14.5 | — |
| `system.disk_percent` | 675 | 0.062 | — |
| `system.temperature` | 675 | 1.577 | -0.14 |
| `weather.temp_outside` | 56 | 3.956 | +0.04 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-06-28 | 57686 | 8 | 1.0 | 1.329 |
| 2026-06-29 | 66947 | 8 | 1.0 | 1.436 |
| 2026-06-30 | 76436 | 8 | 0.8 | 1.577 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

