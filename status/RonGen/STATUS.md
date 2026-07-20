# GENUS · RonGen

**healthy ✓** · seed `1a73db0db72ebf57f1611b42b97a3e7bef9ec404` · generated `2026-07-20T01:38:04.059Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **985663** · beliefs **9** · experiences **14** · proposals 16 · rules 0 · governance 27
- sealing head `bbcd8c77ec1c9410…` (event 985663)

## Self-knowledge

**Calibration** — 2/7 stable judgments held · accuracy **0.286** · discriminates (+0.22) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 20 | 17.813 | -0.54 |
| `system.disk_percent` | 6217 | 3.685 | +0.09 |
| `system.temperature` | 6216 | 2.216 | +0.00 |
| `weather.temp_outside` | 520 | 2.988 | +0.23 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-07-14 | 943492 | 9 | 0.429 | 2.658 |
| 2026-07-15 | 950467 | 9 | 0.429 | 2.581 |
| 2026-07-16 | 957463 | 9 | 0.429 | 2.502 |
| 2026-07-17 | 964534 | 9 | 0.429 | 2.426 |
| 2026-07-18 | 971587 | 9 | 0.286 | 2.365 |
| 2026-07-19 | 978636 | 9 | 0.286 | 2.285 |
| 2026-07-20 | 985663 | 9 | 0.286 | 2.216 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

