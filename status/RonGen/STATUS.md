# GENUS · RonGen

**healthy ✓** · seed `3ccf5b5329a8297d4f548d36b27267af74e6326c` · generated `2026-08-15T01:38:18.506Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1169117** · beliefs **9** · experiences **14** · proposals 37 · rules 0 · governance 48
- sealing head `3e282cc83c331a26…` (event 1169117)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 45 | 14.435 | -0.40 |
| `system.disk_percent` | 13704 | 1.821 | +0.14 |
| `system.temperature` | 13703 | 1.745 | -0.02 |
| `weather.temp_outside` | 1141 | 3.235 | +0.29 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-08-09 | 1126763 | 9 | 0.5 | 1.809 |
| 2026-08-10 | 1133823 | 9 | 0.5 | 1.797 |
| 2026-08-11 | 1140890 | 9 | 0.5 | 1.792 |
| 2026-08-12 | 1147949 | 9 | 0.5 | 1.777 |
| 2026-08-13 | 1155016 | 9 | 0.5 | 1.763 |
| 2026-08-14 | 1162076 | 9 | 0.5 | 1.748 |
| 2026-08-15 | 1169117 | 9 | 0.5 | 1.745 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

