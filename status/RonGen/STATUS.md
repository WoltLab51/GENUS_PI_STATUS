# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-11-24T02:39:34.338Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1858277** · beliefs **9** · experiences **14** · proposals 48 · rules 0 · governance 59
- sealing head `d0c3c26aa69264d8…` (event 1858277)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 129 | 8.261 | -0.62 |
| `system.disk_percent` | 42789 | 4.099 | -0.10 |
| `system.temperature` | 42788 | 1.147 | -0.00 |
| `weather.temp_outside` | 1767 | 3.236 | +0.25 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-11-18 | 1817918 | 9 | 0.5 | 1.158 |
| 2026-11-19 | 1824629 | 9 | 0.5 | 1.156 |
| 2026-11-20 | 1831367 | 9 | 0.5 | 1.153 |
| 2026-11-21 | 1838107 | 9 | 0.5 | 1.151 |
| 2026-11-22 | 1844824 | 9 | 0.5 | 1.15 |
| 2026-11-23 | 1851550 | 9 | 0.5 | 1.148 |
| 2026-11-24 | 1858277 | 9 | 0.5 | 1.147 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

