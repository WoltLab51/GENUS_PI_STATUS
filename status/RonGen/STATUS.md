# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-09-09T01:38:43.172Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1345069** · beliefs **9** · experiences **14** · proposals 41 · rules 0 · governance 52
- sealing head `460f32776c967bfb…` (event 1345071)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 70 | 11.496 | -0.45 |
| `system.disk_percent` | 20889 | 2.776 | +0.18 |
| `system.temperature` | 20888 | 1.494 | +0.01 |
| `weather.temp_outside` | 1740 | 3.162 | +0.25 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-09-03 | 1302819 | 9 | 0.5 | 1.555 |
| 2026-09-04 | 1309871 | 9 | 0.5 | 1.544 |
| 2026-09-05 | 1316895 | 9 | 0.5 | 1.533 |
| 2026-09-06 | 1323939 | 9 | 0.5 | 1.522 |
| 2026-09-07 | 1330983 | 9 | 0.5 | 1.511 |
| 2026-09-08 | 1338027 | 9 | 0.5 | 1.5 |
| 2026-09-09 | 1345069 | 9 | 0.5 | 1.494 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

