<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Español](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Canary Islands only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-24 15:12 UTC, BOE consolidated legislation, autonomous communities (open data): 37 addresses read; 0 added, 0 changed, 0 removed; the check failed; 25 not published, 0 of them with no reason. Flags: `publish-lag`.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [BOE consolidated legislation, autonomous communities (open data)](https://www.boe.es/datosabiertos/api/api.php) | `estatuto-de-autonomia/`, `ley-*/`, `decreto-ley-*/`, `decreto-legislativo-*/`, `…` | daily | 2026-11-23 13:50 UTC | the check failed | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-24 15:11](checks/2026-11.md#es-boe-autonomico-20261124t151116z) | boe-autonomico | 37 | 0 | 0 | 0 | 25 (0) | the check failed `publish-lag` | — |
| [2026-11-24 14:21](checks/2026-11.md#es-boe-autonomico-20261124t142140z) | boe-autonomico | 37 | 0 | 0 | 0 | 25 (0) | the check failed `publish-lag` | — |
| [2026-11-24 12:58](checks/2026-11.md#es-boe-autonomico-20261124t125810z) | boe-autonomico | 37 | 0 | 0 | 0 | 25 (0) | the check failed `publish-lag` | — |
| [2026-11-24 11:16](checks/2026-11.md#es-boe-autonomico-20261124t111633z) | boe-autonomico | 37 | 0 | 0 | 0 | 25 (0) | the check failed `publish-lag` | — |
| [2026-11-24 10:12](checks/2026-11.md#es-boe-autonomico-20261124t101257z) | boe-autonomico | 37 | 0 | 0 | 0 | 25 (0) | the check failed `publish-lag` | — |
| [2026-11-24 09:11](checks/2026-11.md#es-boe-autonomico-20261124t091143z) | boe-autonomico | 37 | 0 | 0 | 0 | 25 (0) | the check failed `publish-lag` | — |
| [2026-11-24 08:11](checks/2026-11.md#es-boe-autonomico-20261124t081149z) | boe-autonomico | 37 | 0 | 0 | 0 | 25 (0) | the check failed `publish-lag` | — |
| [2026-11-24 07:16](checks/2026-11.md#es-boe-autonomico-20261124t071620z) | boe-autonomico | 37 | 0 | 0 | 0 | 25 (0) | the check failed `publish-lag` | — |
| [2026-11-23 13:50](checks/2026-11.md#es-boe-autonomico-20261123t135048z) | boe-autonomico | 36 | 0 | 0 | 0 | 25 (0) | no change `publish-lag` | — |
| [2026-11-23 01:08](checks/2026-11.md#es-boe-autonomico-20261123t010807z) | boe-autonomico | 10 | 0 | 0 | 0 | 25 (0) | no change `publish-lag` | — |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
