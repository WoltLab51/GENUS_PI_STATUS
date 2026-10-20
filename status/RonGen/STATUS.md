# GENUS · RonGen

**healthy ✓** · seed `245c21774854f0530a94414f4d8b0f35b62b1c0b` · generated `2026-10-20T01:39:08.871Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1622294** · beliefs **9** · experiences **14** · proposals 47 · rules 0 · governance 58
- sealing head `929a9c33992b7cb3…` (event 1622294)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 111 | 9.022 | -0.57 |
| `system.disk_percent` | 32697 | 3.496 | +0.04 |
| `system.temperature` | 32696 | 1.234 | -0.00 |
| `weather.temp_outside` | 1762 | 3.21 | +0.25 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-10-14 | 1581739 | 9 | 0.5 | 1.263 |
| 2026-10-15 | 1588512 | 9 | 0.5 | 1.258 |
| 2026-10-16 | 1595243 | 9 | 0.5 | 1.253 |
| 2026-10-17 | 1601992 | 9 | 0.5 | 1.248 |
| 2026-10-18 | 1608756 | 9 | 0.5 | 1.243 |
| 2026-10-19 | 1615519 | 9 | 0.5 | 1.238 |
| 2026-10-20 | 1622294 | 9 | 0.5 | 1.234 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

