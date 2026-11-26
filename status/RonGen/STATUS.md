# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-11-26T02:39:34.516Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1871675** · beliefs **9** · experiences **14** · proposals 49 · rules 0 · governance 60
- sealing head `94ae771e9a2bdab5…` (event 1871675)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 129 | 8.261 | -0.62 |
| `system.disk_percent` | 43365 | 4.133 | -0.11 |
| `system.temperature` | 43364 | 1.144 | -0.00 |
| `weather.temp_outside` | 1767 | 3.236 | +0.25 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-11-20 | 1831367 | 9 | 0.5 | 1.153 |
| 2026-11-21 | 1838107 | 9 | 0.5 | 1.151 |
| 2026-11-22 | 1844824 | 9 | 0.5 | 1.15 |
| 2026-11-23 | 1851550 | 9 | 0.5 | 1.148 |
| 2026-11-24 | 1858277 | 9 | 0.5 | 1.147 |
| 2026-11-25 | 1864984 | 9 | 0.5 | 1.146 |
| 2026-11-26 | 1871675 | 9 | 0.5 | 1.144 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

