# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-11-07T02:39:20.979Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1744025** · beliefs **9** · experiences **14** · proposals 47 · rules 0 · governance 58
- sealing head `77cc294a248a1443…` (event 1744025)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 129 | 8.261 | -0.62 |
| `system.disk_percent` | 37893 | 3.742 | -0.03 |
| `system.temperature` | 37892 | 1.176 | +0.00 |
| `weather.temp_outside` | 1763 | 3.213 | +0.25 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-11-01 | 1703515 | 9 | 0.5 | 1.189 |
| 2026-11-02 | 1710261 | 9 | 0.5 | 1.187 |
| 2026-11-03 | 1717011 | 9 | 0.5 | 1.184 |
| 2026-11-04 | 1723765 | 9 | 0.5 | 1.182 |
| 2026-11-05 | 1730519 | 9 | 0.5 | 1.18 |
| 2026-11-06 | 1737261 | 9 | 0.5 | 1.177 |
| 2026-11-07 | 1744025 | 9 | 0.5 | 1.176 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

