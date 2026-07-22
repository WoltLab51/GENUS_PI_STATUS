# GENUS · RonGen

**healthy ✓** · seed `1a73db0db72ebf57f1611b42b97a3e7bef9ec404` · generated `2026-07-22T01:38:04.893Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **999832** · beliefs **9** · experiences **14** · proposals 20 · rules 0 · governance 31
- sealing head `d1c78f4a93ac07b0…` (event 999832)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 22 | 17.777 | -0.51 |
| `system.disk_percent` | 6793 | 3.426 | +0.10 |
| `system.temperature` | 6792 | 2.083 | +0.01 |
| `weather.temp_outside` | 568 | 3.111 | +0.21 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-07-16 | 957463 | 9 | 0.429 | 2.502 |
| 2026-07-17 | 964534 | 9 | 0.429 | 2.426 |
| 2026-07-18 | 971587 | 9 | 0.286 | 2.365 |
| 2026-07-19 | 978636 | 9 | 0.286 | 2.285 |
| 2026-07-20 | 985663 | 9 | 0.286 | 2.216 |
| 2026-07-21 | 992736 | 9 | 0.5 | 2.147 |
| 2026-07-22 | 999832 | 9 | 0.5 | 2.083 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

