# GENUS · RonGen

**healthy ✓** · seed `089a2b384e1416b3cdc8eec952321b69fa9df086` · generated `2026-08-19T01:38:21.861Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1197360** · beliefs **9** · experiences **14** · proposals 38 · rules 0 · governance 49
- sealing head `960db70ee1c09d76…` (event 1197362)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 49 | 13.829 | -0.40 |
| `system.disk_percent` | 14856 | 1.721 | +0.14 |
| `system.temperature` | 14855 | 1.707 | -0.02 |
| `weather.temp_outside` | 1237 | 3.274 | +0.28 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-08-13 | 1155016 | 9 | 0.5 | 1.763 |
| 2026-08-14 | 1162076 | 9 | 0.5 | 1.748 |
| 2026-08-15 | 1169117 | 9 | 0.5 | 1.745 |
| 2026-08-16 | 1176177 | 9 | 0.5 | 1.744 |
| 2026-08-17 | 1183237 | 9 | 0.5 | 1.74 |
| 2026-08-18 | 1190295 | 9 | 0.5 | 1.724 |
| 2026-08-19 | 1197360 | 9 | 0.5 | 1.707 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

