# GENUS · RonGen

**healthy ✓** · seed `20d5773305d503ca861e0a0fe365ae473cdc9657` · generated `2026-07-09T01:37:47.905Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **757559** · beliefs **9** · experiences **11** · proposals 13 · rules 0 · governance 16
- sealing head `883877e82b174260…` (event 757561)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.257) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 10 | 18.575 | -0.47 |
| `system.disk_percent` | 3254 | 3.724 | +0.03 |
| `system.temperature` | 3253 | 3.15 | +0.01 |
| `weather.temp_outside` | 271 | 3.419 | +0.09 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

