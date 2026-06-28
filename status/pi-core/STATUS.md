# GENUS · pi-core

**healthy ✓** · seed `319ef57c77df9286559b4ecdc2af3705b2519b8c` · generated `2026-06-28T13:44:35.185Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **57686** · beliefs **8** · experiences **6** · proposals 5 · rules 0 · governance 10
- sealing head `b35b31e154a5e871…` (event 57686)

## Self-knowledge

**Calibration** — 5/5 stable judgments held · accuracy **1.0** · discriminates (+0.359) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `system.disk_percent` | 252 | 0.065 | — |
| `system.temperature` | 252 | 1.329 | +0.02 |
| `weather.temp_outside` | 20 | 1.57 | +0.57 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

