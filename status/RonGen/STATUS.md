# GENUS · RonGen

**healthy ✓** · seed `252fff62384e408d0af20e7656b6c68308523456` · generated `2026-07-14T01:38:00.358Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **943492** · beliefs **9** · experiences **14** · proposals 16 · rules 0 · governance 27
- sealing head `8f7f83abdb729cae…` (event 943492)

## Self-knowledge

**Calibration** — 3/7 stable judgments held · accuracy **0.429** · discriminates (+0.22) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 14 | 17.816 | -0.63 |
| `system.disk_percent` | 4502 | 4.672 | +0.04 |
| `system.temperature` | 4501 | 2.658 | +0.01 |
| `weather.temp_outside` | 376 | 3.252 | +0.18 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-07-09 | 757559 | 9 | 0.5 | 3.15 |
| 2026-07-10 | 764480 | 9 | 0.667 | 2.971 |
| 2026-07-12 | 775410 | 9 | 0.5 | 2.764 |
| 2026-07-13 | 936506 | 9 | 0.429 | 2.758 |
| 2026-07-14 | 943492 | 9 | 0.429 | 2.658 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

