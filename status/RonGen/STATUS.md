# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-10-17T01:39:06.491Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1601992** · beliefs **9** · experiences **14** · proposals 47 · rules 0 · governance 58
- sealing head `a0b2c7f95909529e…` (event 1601992)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 108 | 9.154 | -0.56 |
| `system.disk_percent` | 31833 | 3.47 | +0.05 |
| `system.temperature` | 31832 | 1.248 | -0.00 |
| `weather.temp_outside` | 1757 | 3.19 | +0.25 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-10-11 | 1561423 | 9 | 0.5 | 1.279 |
| 2026-10-12 | 1568173 | 9 | 0.5 | 1.274 |
| 2026-10-13 | 1574949 | 9 | 0.5 | 1.268 |
| 2026-10-14 | 1581739 | 9 | 0.5 | 1.263 |
| 2026-10-15 | 1588512 | 9 | 0.5 | 1.258 |
| 2026-10-16 | 1595243 | 9 | 0.5 | 1.253 |
| 2026-10-17 | 1601992 | 9 | 0.5 | 1.248 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

