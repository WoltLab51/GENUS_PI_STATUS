# GENUS · RonGen

**healthy ✓** · seed `a5bb421ee2feee18609d18514d5e56c436a1b097` · generated `2026-07-16T01:38:01.117Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **957463** · beliefs **9** · experiences **14** · proposals 16 · rules 0 · governance 27
- sealing head `3f9452688f640021…` (event 957463)

## Self-knowledge

**Calibration** — 3/7 stable judgments held · accuracy **0.429** · discriminates (+0.22) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 16 | 17.495 | -0.55 |
| `system.disk_percent` | 5066 | 4.339 | +0.06 |
| `system.temperature` | 5065 | 2.502 | +0.00 |
| `weather.temp_outside` | 424 | 3.071 | +0.23 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-07-09 | 757559 | 9 | 0.5 | 3.15 |
| 2026-07-10 | 764480 | 9 | 0.667 | 2.971 |
| 2026-07-12 | 775410 | 9 | 0.5 | 2.764 |
| 2026-07-13 | 936506 | 9 | 0.429 | 2.758 |
| 2026-07-14 | 943492 | 9 | 0.429 | 2.658 |
| 2026-07-15 | 950467 | 9 | 0.429 | 2.581 |
| 2026-07-16 | 957463 | 9 | 0.429 | 2.502 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

