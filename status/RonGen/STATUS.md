# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-09-12T01:38:43.882Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1365417** · beliefs **9** · experiences **14** · proposals 42 · rules 0 · governance 53
- sealing head `0a3463968064449b…` (event 1365417)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 73 | 11.24 | -0.45 |
| `system.disk_percent` | 21753 | 2.871 | +0.17 |
| `system.temperature` | 21752 | 1.465 | +0.01 |
| `weather.temp_outside` | 1746 | 3.158 | +0.26 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-09-06 | 1323939 | 9 | 0.5 | 1.522 |
| 2026-09-07 | 1330983 | 9 | 0.5 | 1.511 |
| 2026-09-08 | 1338027 | 9 | 0.5 | 1.5 |
| 2026-09-09 | 1345069 | 9 | 0.5 | 1.494 |
| 2026-09-10 | 1351885 | 9 | 0.5 | 1.483 |
| 2026-09-11 | 1358660 | 9 | 0.5 | 1.473 |
| 2026-09-12 | 1365417 | 9 | 0.5 | 1.465 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

