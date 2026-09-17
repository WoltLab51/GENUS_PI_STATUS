# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-09-17T01:38:47.362Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1399185** · beliefs **9** · experiences **14** · proposals 43 · rules 0 · governance 54
- sealing head `74ebe7943d2f1cdb…` (event 1399185)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 78 | 10.867 | -0.47 |
| `system.disk_percent` | 23193 | 3.008 | +0.16 |
| `system.temperature` | 23192 | 1.424 | +0.00 |
| `weather.temp_outside` | 1747 | 3.157 | +0.26 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-09-11 | 1358660 | 9 | 0.5 | 1.473 |
| 2026-09-12 | 1365417 | 9 | 0.5 | 1.465 |
| 2026-09-13 | 1372185 | 9 | 0.5 | 1.455 |
| 2026-09-14 | 1378939 | 9 | 0.5 | 1.448 |
| 2026-09-15 | 1385697 | 9 | 0.5 | 1.441 |
| 2026-09-16 | 1392436 | 9 | 0.5 | 1.433 |
| 2026-09-17 | 1399185 | 9 | 0.5 | 1.424 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

