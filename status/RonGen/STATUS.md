# GENUS · RonGen

**healthy ✓** · seed `db6c5dd21b9aeef15bdb7df371728697ed10b0ff` · generated `2026-07-10T01:37:48.929Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **764480** · beliefs **9** · experiences **13** · proposals 14 · rules 0 · governance 16
- sealing head `3d7e5ca5ac8dddc3…` (event 764480)

## Self-knowledge

**Calibration** — 4/6 stable judgments held · accuracy **0.667** · discriminates (+0.209) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 11 | 19.614 | -0.70 |
| `system.disk_percent` | 3542 | 4.175 | -0.00 |
| `system.temperature` | 3541 | 2.971 | +0.02 |
| `weather.temp_outside` | 295 | 3.392 | +0.07 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-07-09 | 757559 | 9 | 0.5 | 3.15 |
| 2026-07-10 | 764480 | 9 | 0.667 | 2.971 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

