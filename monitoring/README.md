<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Beobachtung: was gelesen wird und was daraus folgte

[English](README.en.md)

Wie global-law jedes Land beobachtet: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). Diese Seite zeigt dasselbe nur für Menzingen: jedes Lesen einer amtlichen Quelle, wann, und was daraus folgte (Vorschriften hinzugefügt, geändert und entfernt). Maschinenlesbar in [data/checks/](../data/checks/) (JSON Lines, Schema `lexifina-check/1`), in `git log` als Commits mit `Kind: check` und Monat für Monat in [checks/](checks/).

**Letzte Prüfung:** 2026-11-26 07:12 UTC, Menzingen: Systematische Sammlung (menzingen.tlex.ch): 14 Adressen gelesen; 0 hinzugefügt, 0 geändert, 0 entfernt; keine Änderung; 0 nicht veröffentlicht, davon 0 ohne Grund.

## Quellen

| Quelle | Ordner | Wie oft | Letzte erfolgreiche Prüfung | Letztes Ergebnis | Stand |
| --- | --- | --- | --- | --- | --- |
| [Menzingen: Systematische Sammlung (menzingen.tlex.ch)](https://menzingen.tlex.ch/) | `<act>/` | täglich | 2026-11-26 07:12 UTC | keine Änderung | beobachtet |

## Die letzten 30 Tage

| Beginn (UTC) | Quelle | Gelesen | Hinzugefügt | Geändert | Entfernt | Nicht veröffentlicht (ohne Grund) | Ergebnis | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-26 07:12](checks/2026-11.md#ch-lexwork-menzingen-city-20261126t071217z) | lexwork-menzingen-city | 14 | 0 | 0 | 0 | 0 (0) | keine Änderung | — |
| [2026-11-25 08:20](checks/2026-11.md#ch-lexwork-menzingen-city-20261125t082030z) | lexwork-menzingen-city | 15 | 0 | 1 | 0 | 0 (0) | Änderungen gefunden | [2](https://github.com/lexifina/switzerland-menzingen-city-law/compare/11ab06d7c25a...b9b99c172c63) |
| [2026-11-24 12:46](checks/2026-11.md#ch-lexwork-menzingen-city-20261124t124658z) | lexwork-menzingen-city | 15 | 1 | 0 | 0 | 0 (0) | Änderungen gefunden | [2](https://github.com/lexifina/switzerland-menzingen-city-law/compare/02bc8ca47437...4ca9b84e15c6) |

## Selbst prüfen

```
python tools/checktrail.py                      # die letzte Prüfung jeder Quelle
python tools/checktrail.py --day 2026-11-23     # jede Prüfung eines Tages
python tools/checktrail.py --act <id>           # wann eine Vorschrift gesehen und veröffentlicht wurde
git log --grep='^Kind: check' --format='%ci %s'  # die Prüfungen in der Historie
```

Rechtskraft hat nur die amtliche Verkündung; die Texte hier sind Kopien zum Lesen und Suchen.
