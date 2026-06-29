# GENUS · pi-core

**healthy ✓** · seed `a0f8f3154a00fcb9a42b156a39abfdb3edf74fff` · generated `2026-06-29T15:39:50.782Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **66947** · beliefs **8** · experiences **6** · proposals 5 · rules 0 · governance 10
- sealing head `1a580bcc131895cc…` (event 66947)

## Self-knowledge

**Calibration** — 5/5 stable judgments held · accuracy **1.0** · discriminates (+0.359) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 1 | 14.5 | — |
| `system.disk_percent` | 563 | 0.062 | -70240894901770.21 |
| `system.temperature` | 563 | 1.436 | -0.10 |
| `weather.temp_outside` | 47 | 3.276 | +0.21 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-06-28 | 57686 | 8 | 1.0 | 1.329 |
| 2026-06-29 | 66947 | 8 | 1.0 | 1.436 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

