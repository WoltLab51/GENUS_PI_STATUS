# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-11-20T02:39:29.708Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1831367** · beliefs **9** · experiences **14** · proposals 48 · rules 0 · governance 59
- sealing head `2fc09e4d3eefe134…` (event 1831367)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 129 | 8.261 | -0.62 |
| `system.disk_percent` | 41637 | 4.026 | -0.09 |
| `system.temperature` | 41636 | 1.153 | -0.00 |
| `weather.temp_outside` | 1766 | 3.231 | +0.25 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-11-14 | 1791180 | 9 | 0.5 | 1.165 |
| 2026-11-15 | 1797854 | 9 | 0.5 | 1.163 |
| 2026-11-16 | 1804519 | 9 | 0.5 | 1.161 |
| 2026-11-17 | 1811193 | 9 | 0.5 | 1.16 |
| 2026-11-18 | 1817918 | 9 | 0.5 | 1.158 |
| 2026-11-19 | 1824629 | 9 | 0.5 | 1.156 |
| 2026-11-20 | 1831367 | 9 | 0.5 | 1.153 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

