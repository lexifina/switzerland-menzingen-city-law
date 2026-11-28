<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Deutsch](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Menzingen only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-28 08:29 UTC, Menzingen: systematic collection (menzingen.tlex.ch): 14 addresses read; 0 added, 0 changed, 0 removed; no change; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Menzingen: systematic collection (menzingen.tlex.ch)](https://menzingen.tlex.ch/) | `<act>/` | daily | 2026-11-28 08:29 UTC | no change | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 08:29](checks/2026-11.md#ch-lexwork-menzingen-city-20261128t082911z) | lexwork-menzingen-city | 14 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-28 07:10](checks/2026-11.md#ch-lexwork-menzingen-city-20261128t071040z) | lexwork-menzingen-city | 0 | 0 | 0 | 0 | 0 (0) | the check failed | — |
| [2026-11-28 06:41](checks/2026-11.md#ch-lexwork-menzingen-city-20261128t064122z) | lexwork-menzingen-city | 0 | 0 | 0 | 0 | 0 (0) | the check failed | — |
| [2026-11-27 07:06](checks/2026-11.md#ch-lexwork-menzingen-city-20261127t070627z) | lexwork-menzingen-city | 15 | 0 | 1 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/switzerland-menzingen-city-law/compare/13f77f462aef...68db8ec5d75c) |
| [2026-11-26 07:12](checks/2026-11.md#ch-lexwork-menzingen-city-20261126t071217z) | lexwork-menzingen-city | 14 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-25 08:20](checks/2026-11.md#ch-lexwork-menzingen-city-20261125t082030z) | lexwork-menzingen-city | 15 | 0 | 1 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/switzerland-menzingen-city-law/compare/11ab06d7c25a...b9b99c172c63) |
| [2026-11-24 12:46](checks/2026-11.md#ch-lexwork-menzingen-city-20261124t124658z) | lexwork-menzingen-city | 15 | 1 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/switzerland-menzingen-city-law/compare/02bc8ca47437...4ca9b84e15c6) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
