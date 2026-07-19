# GENUS · RonGen

**healthy ✓** · seed `a5bb421ee2feee18609d18514d5e56c436a1b097` · generated `2026-07-19T01:38:02.785Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **978636** · beliefs **9** · experiences **14** · proposals 16 · rules 0 · governance 27
- sealing head `db1c28e2b4df6a08…` (event 978636)

## Self-knowledge

**Calibration** — 2/7 stable judgments held · accuracy **0.286** · discriminates (+0.22) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 19 | 18.075 | -0.57 |
| `system.disk_percent` | 5930 | 3.832 | +0.08 |
| `system.temperature` | 5929 | 2.285 | -0.00 |
| `weather.temp_outside` | 496 | 2.915 | +0.25 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-07-13 | 936506 | 9 | 0.429 | 2.758 |
| 2026-07-14 | 943492 | 9 | 0.429 | 2.658 |
| 2026-07-15 | 950467 | 9 | 0.429 | 2.581 |
| 2026-07-16 | 957463 | 9 | 0.429 | 2.502 |
| 2026-07-17 | 964534 | 9 | 0.429 | 2.426 |
| 2026-07-18 | 971587 | 9 | 0.286 | 2.365 |
| 2026-07-19 | 978636 | 9 | 0.286 | 2.285 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

