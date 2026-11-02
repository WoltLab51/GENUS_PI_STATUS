# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-11-02T02:39:17.200Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1710261** · beliefs **9** · experiences **14** · proposals 47 · rules 0 · governance 58
- sealing head `333b2199a548878b…` (event 1710261)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 124 | 8.467 | -0.60 |
| `system.disk_percent` | 36453 | 3.609 | -0.00 |
| `system.temperature` | 36452 | 1.187 | +0.00 |
| `weather.temp_outside` | 1762 | 3.21 | +0.25 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-10-27 | 1669819 | 9 | 0.5 | 1.206 |
| 2026-10-28 | 1676546 | 9 | 0.5 | 1.201 |
| 2026-10-29 | 1683291 | 9 | 0.5 | 1.197 |
| 2026-10-30 | 1690028 | 9 | 0.5 | 1.194 |
| 2026-10-31 | 1696756 | 9 | 0.5 | 1.192 |
| 2026-11-01 | 1703515 | 9 | 0.5 | 1.189 |
| 2026-11-02 | 1710261 | 9 | 0.5 | 1.187 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

