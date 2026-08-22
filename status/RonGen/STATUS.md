# GENUS · RonGen

**healthy ✓** · seed `429b5688472cdce041188e6c93dbffb9fec79fd9` · generated `2026-08-22T01:38:25.148Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1218553** · beliefs **9** · experiences **14** · proposals 40 · rules 0 · governance 51
- sealing head `582eb43d94a045d8…` (event 1218555)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 52 | 13.346 | -0.41 |
| `system.disk_percent` | 15720 | 1.842 | +0.16 |
| `system.temperature` | 15719 | 1.671 | -0.01 |
| `weather.temp_outside` | 1309 | 3.216 | +0.27 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-08-16 | 1176177 | 9 | 0.5 | 1.744 |
| 2026-08-17 | 1183237 | 9 | 0.5 | 1.74 |
| 2026-08-18 | 1190295 | 9 | 0.5 | 1.724 |
| 2026-08-19 | 1197360 | 9 | 0.5 | 1.707 |
| 2026-08-20 | 1204429 | 9 | 0.5 | 1.689 |
| 2026-08-21 | 1211489 | 9 | 0.5 | 1.673 |
| 2026-08-22 | 1218553 | 9 | 0.5 | 1.671 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

