# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-10-26T02:39:12.648Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1663074** · beliefs **9** · experiences **14** · proposals 47 · rules 0 · governance 58
- sealing head `2ffc932f1add6f4d…` (event 1663076)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 117 | 8.759 | -0.58 |
| `system.disk_percent` | 34437 | 3.543 | +0.02 |
| `system.temperature` | 34436 | 1.21 | -0.00 |
| `weather.temp_outside` | 1762 | 3.21 | +0.25 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-10-20 | 1622294 | 9 | 0.5 | 1.234 |
| 2026-10-21 | 1629024 | 9 | 0.5 | 1.23 |
| 2026-10-22 | 1635783 | 9 | 0.5 | 1.226 |
| 2026-10-23 | 1642519 | 9 | 0.5 | 1.222 |
| 2026-10-24 | 1649272 | 9 | 0.5 | 1.218 |
| 2026-10-25 | 1656283 | 9 | 0.5 | 1.214 |
| 2026-10-26 | 1663074 | 9 | 0.5 | 1.21 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

