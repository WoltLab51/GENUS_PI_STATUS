# GENUS · pi-core

**healthy ✓** · seed `c20b6c065b53634b05f24886e24e14c002d9498d` · generated `2026-06-28T08:31:09.025Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **56447** · beliefs **8** · experiences **6** · proposals 5 · rules 0 · governance 10
- sealing head `66d1a7baea5f3e47…` (event 56447)

## Self-knowledge

**Calibration** — 5/5 stable judgments held · accuracy **1.0** · discriminates (+0.359) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | early → recent |
| --- | ---: | ---: | --- |
| `system.disk_percent` | 190 | 0.067 | 0.067 → 0.065 |
| `system.temperature` | 190 | 1.292 | 1.432 → 1.353 |
| `weather.temp_outside` | 15 | 1.18 | 1.18 → 1.18 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

