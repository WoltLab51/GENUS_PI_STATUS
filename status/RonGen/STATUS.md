# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-09-22T01:38:50.544Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1432971** · beliefs **9** · experiences **14** · proposals 44 · rules 0 · governance 55
- sealing head `f0cf6b15fd37e89d…` (event 1432971)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 83 | 10.56 | -0.48 |
| `system.disk_percent` | 24633 | 3.12 | +0.14 |
| `system.temperature` | 24632 | 1.389 | +0.00 |
| `weather.temp_outside` | 1748 | 3.162 | +0.25 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-09-16 | 1392436 | 9 | 0.5 | 1.433 |
| 2026-09-17 | 1399185 | 9 | 0.5 | 1.424 |
| 2026-09-18 | 1405941 | 9 | 0.5 | 1.415 |
| 2026-09-19 | 1412686 | 9 | 0.5 | 1.406 |
| 2026-09-20 | 1419442 | 9 | 0.5 | 1.4 |
| 2026-09-21 | 1426196 | 9 | 0.5 | 1.394 |
| 2026-09-22 | 1432971 | 9 | 0.5 | 1.389 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

