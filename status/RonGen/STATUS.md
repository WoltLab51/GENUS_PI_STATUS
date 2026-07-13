# GENUS · RonGen

**healthy ✓** · seed `d478152962de2ee178f0469b2a73429eb662fb33` · generated `2026-07-13T01:37:58.633Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **936506** · beliefs **9** · experiences **14** · proposals 16 · rules 0 · governance 27
- sealing head `4c87556df98fbae8…` (event 936506)

## Self-knowledge

**Calibration** — 3/7 stable judgments held · accuracy **0.429** · discriminates (+0.22) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 13 | 18.725 | -0.65 |
| `system.disk_percent` | 4218 | 4.778 | +0.02 |
| `system.temperature` | 4217 | 2.758 | +0.02 |
| `weather.temp_outside` | 352 | 3.259 | +0.16 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-07-09 | 757559 | 9 | 0.5 | 3.15 |
| 2026-07-10 | 764480 | 9 | 0.667 | 2.971 |
| 2026-07-12 | 775410 | 9 | 0.5 | 2.764 |
| 2026-07-13 | 936506 | 9 | 0.429 | 2.758 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

