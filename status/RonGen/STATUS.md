# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-08-26T01:38:32.716Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1246382** · beliefs **9** · experiences **14** · proposals 41 · rules 0 · governance 52
- sealing head `6f127de0983f8159…` (event 1246382)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 56 | 12.689 | -0.41 |
| `system.disk_percent` | 16857 | 2.114 | +0.18 |
| `system.temperature` | 16856 | 1.653 | -0.00 |
| `weather.temp_outside` | 1404 | 3.293 | +0.26 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-08-20 | 1204429 | 9 | 0.5 | 1.689 |
| 2026-08-21 | 1211489 | 9 | 0.5 | 1.673 |
| 2026-08-22 | 1218553 | 9 | 0.5 | 1.671 |
| 2026-08-23 | 1225203 | 9 | 0.5 | 1.681 |
| 2026-08-24 | 1232267 | 9 | 0.5 | 1.671 |
| 2026-08-25 | 1239322 | 9 | 0.5 | 1.665 |
| 2026-08-26 | 1246382 | 9 | 0.5 | 1.653 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

