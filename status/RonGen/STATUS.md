# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-10-05T01:38:58.981Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1520867** · beliefs **9** · experiences **14** · proposals 46 · rules 0 · governance 57
- sealing head `628c6642e1b3a375…` (event 1520869)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 96 | 9.788 | -0.52 |
| `system.disk_percent` | 28377 | 3.338 | +0.10 |
| `system.temperature` | 28376 | 1.315 | -0.00 |
| `weather.temp_outside` | 1753 | 3.173 | +0.25 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-09-29 | 1480281 | 9 | 0.5 | 1.354 |
| 2026-09-30 | 1487037 | 9 | 0.5 | 1.347 |
| 2026-10-01 | 1493805 | 9 | 0.5 | 1.34 |
| 2026-10-02 | 1500559 | 9 | 0.5 | 1.333 |
| 2026-10-03 | 1507313 | 9 | 0.5 | 1.327 |
| 2026-10-04 | 1514088 | 9 | 0.5 | 1.321 |
| 2026-10-05 | 1520867 | 9 | 0.5 | 1.315 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

