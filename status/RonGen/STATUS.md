# GENUS · RonGen

**healthy ✓** · seed `bc21ffab70df002779716caf46f7f3d452a81aa9` · generated `2026-07-12T01:37:49.652Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **775410** · beliefs **9** · experiences **14** · proposals 16 · rules 0 · governance 27
- sealing head `11334f42cef7e4fb…` (event 775410)

## Self-knowledge

**Calibration** — 3/6 stable judgments held · accuracy **0.5** · discriminates (+0.209) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 12 | 19.035 | -0.70 |
| `system.disk_percent` | 3969 | 4.818 | -0.00 |
| `system.temperature` | 3968 | 2.764 | +0.02 |
| `weather.temp_outside` | 331 | 3.296 | +0.13 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-07-09 | 757559 | 9 | 0.5 | 3.15 |
| 2026-07-10 | 764480 | 9 | 0.667 | 2.971 |
| 2026-07-12 | 775410 | 9 | 0.5 | 2.764 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

