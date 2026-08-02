# GENUS · RonGen

**healthy ✓** · seed `1a73db0db72ebf57f1611b42b97a3e7bef9ec404` · generated `2026-08-02T01:38:12.547Z`

> Auto-generated public status — aggregate health only, no values, paths, or event detail.

## Health

- events **1077395** · beliefs **9** · experiences **14** · proposals 30 · rules 0 · governance 41
- sealing head `487a92be248933ad…` (event 1077395)

## Self-knowledge

**Calibration** — 2/4 stable judgments held · accuracy **0.5** · discriminates (+0.207) — *does GENUS know that it knows?*

**Learning** — 24/7 forecast paths (predict → self-test → score):

| metric | scored | mean error | skill |
| --- | ---: | ---: | ---: |
| `repo.commits_per_day` | 32 | 16.444 | -0.41 |
| `system.disk_percent` | 9961 | 2.457 | +0.12 |
| `system.temperature` | 9960 | 1.759 | +0.00 |
| `weather.temp_outside` | 831 | 3.161 | +0.24 |

_skill = how much better than naive (guessing the mean): >0 learned real structure · ~0 the signal is too flat to learn · <0 worse than naive._

## Trend (last days)

| day | events | beliefs | calib. | temp. err |
| --- | ---: | ---: | ---: | ---: |
| 2026-07-27 | 1035068 | 9 | 0.5 | 1.857 |
| 2026-07-28 | 1042121 | 9 | 0.5 | 1.816 |
| 2026-07-29 | 1049178 | 9 | 0.5 | 1.779 |
| 2026-07-30 | 1056233 | 9 | 0.5 | 1.752 |
| 2026-07-31 | 1063285 | 9 | 0.5 | 1.739 |
| 2026-08-01 | 1070347 | 9 | 0.5 | 1.746 |
| 2026-08-02 | 1077395 | 9 | 0.5 | 1.759 |

## Verify it has not been tampered with

The ledger is hash-sealed and externally anchored here. Verify any file in
`anchors/` against the live head — if it matches, the Pi has not rewritten its past:

```
genus ledger anchor verify anchors/genus-anchor-<core>-<event>-<hash>.json
```

