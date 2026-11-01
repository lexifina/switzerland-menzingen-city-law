# Menzingen (city): law history in git

The municipal law of the municipality of Menzingen (Gemeinde Menzingen, canton of Zug, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law). The law of the canton of Zug is in [lexifina/switzerland-zug-law](https://github.com/lexifina/switzerland-zug-law); federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, exactly as the municipality publishes it.

## What this repository holds

41 acts with 41 versions so far: the Gemeindeordnung (the municipality's charter) first, then the municipality's other enactments in force (ordinances, regulations, tariffs and decisions), in the order of the systematic collection, added in parts of about 50. Agreements, concessions, directives and repealed acts are not included.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `1-1-1/` | Gemeindeordnung (SRS 1.1-1) | 1 | as enacted, 12 February 2020 |
| `1-2-1/` | Benutzungsordnung für das Archiv (SRS 1.2-1) | 1 | as enacted, 1 January 2012 |
| `1-2-2/` | Benutzerrichtlinie für die Ortseingangstafeln (SRS 1.2-2) | 1 | as enacted, 10 April 2000 |
| `1-4-1/` | Richtlinie für das Aufstellen von Wahl- und Abstimmungsplakaten (SRS 1.4-1) | 1 | as enacted, 1 January 2022 |
| `1-6-1-delegations-und-kompetenzverordnung/` | Verordnung über die Delegation von Kompetenzen des Gemeinderates an seine Mitglieder und die Verwaltung (SRS 1.6-1) | 1 | as enacted, 1 January 2025 |
| `1-6-2-delegationsbeschluss/` | Beschluss über die Subdelegation von Entscheidungsbefugnissen der einzelnen Gemeinderatsmitglieder an die ihnen unterstellte Abteilung (SRS 1.6-2) | 1 | as enacted, 1 January 2025 |
| `1-7-1-bpr/` | Behörden- und Personalreglement (SRS 1.7-1) | 1 | as enacted, 1 January 2024 |
| `1-7-1-1/` | Personalverordnung (SRS 1.7-1.1) | 1 | one version (the oldest available), 1 January 2025 |
| `2-1-1/` | Verordnung über die Gebühren im Beurkundungswesen (SRS 2.1-1) | 1 | as enacted, 1 January 2014 |
| `4-1-1/` | Reglement über die familienergänzende Betreuung von Kindern (SRS 4.1-1) | 1 | as enacted, 1 January 2016 |
| `4-2-2/` | Reglement Schulzahnarzt-Dienst (SRS 4.2-2) | 1 | as enacted, 1 August 2021 |
| `4-2-2-1/` | Verordnung zum Reglement Schulzahnarzt-Dienst (SRS 4.2-2.1) | 1 | as enacted, 1 August 2021 |
| `4-2-3/` | Richtlinien Schulbus (SRS 4.2-3) | 1 | as enacted, 25 June 2018 |
| `4-3-2/` | Zusammenarbeitsvertrag betreffend Musikschulen Menzingen und Neuheim (SRS 4.3-2) | 1 | as enacted, 1 January 2024 |
| `4-3-2-1/` | Ausführungsbestimmungen zum Zusammenarbeitsvertrag zwischen den Musikschulen Menzingen und Neuheim (SRS 4.3-2.1) | 1 | as enacted, 1 January 2024 |
| `4-3-2-2/` | Tarifordnung zum Zusammenarbeitsvertrag zwischen den Musikschulen Menzingen und Neuheim (SRS 4.3-2.2) | 1 | as enacted, 1 August 2024 |
| `4-3-3/` | Richtlinien zur Änderung der Unterrichtsdauer (SRS 4.3-3) | 1 | as enacted, 16 May 2011 |
| `4-7-1/` | Richtlinie für Ehrungen von Einzelpersonen, Vereinen, Firmen und Institutionen in Menzingen (SRS 4.7-1) | 1 | as enacted, 1 October 2018 |
| `4-8-1/` | Richtlinie zur Förderung der gemeindlichen Vereine (SRS 4.8-1) | 1 | as enacted, 1 January 2020 |
| `5-1-1/` | Verordnung über die Lärmbekämpfung (SRS 5.1-1) | 1 | as enacted, 29 June 1972 |
| `5-5-1/` | Feuerwehr-Reglement (SRS 5.5-1) | 1 | as enacted, 1 January 1997 |
| `6-4-1/` | Verordnung zum Mahnwesen von Gebühren und Auslagen (SRS 6.4-1) | 1 | as enacted, 1 January 2019 |
| `6-5-1/` | Richtlinie für die Vergabe der In- und Auslandhilfe (SRS 6.5-1) | 1 | as enacted, 1 September 2022 |
| `6-6-1/` | Benützungsreglement Mehrzweckraum Eu (SRS 6.6-1) | 1 | as enacted, 20 October 2015 |
| `6-6-2/` | Benützungsreglement Sporthalle Ochsenmatt (SRS 6.6-2) | 1 | as enacted, 17 November 2003 |
| `6-6-3/` | Benützungsreglement Zentrum Schützenmatt (SRS 6.6-3) | 1 | one version (the oldest available), 30 January 2012 |
| `6-6-4/` | Verordnung zur Benützung Mehrzweckraum Finstersee (SRS 6.6-4) | 1 | as enacted, 19 June 2023 |
| `6-6-5/` | Verordnung zur Benützung des Spritzenhüslis (SRS 6.6-5) | 1 | as enacted, 1 January 2023 |
| `7-1-1/` | Bauordnung (SRS 7.1-1) | 1 | as enacted, 5 April 2017 |
| `7-1-2/` | Parkplatzreglement (SRS 7.1-2) | 1 | as enacted, 1 January 1999 |
| `7-4-3-1/` | Abwasserreglement (SRS 7.4.3-1) | 1 | as enacted, 1 January 2003 |
| `7-6-1-strassenreglement/` | Reglement über Strassen und Wege (SRS 7.6-1) | 1 | as enacted, 15 January 2009 |
| `7-7-1/` | Reglement betreffend das Dauerparkieren auf gemeindlichen Strassen und Plätzen (SRS 7.7-1) | 1 | as enacted, 19 June 1978 |
| `8-1-1/` | Verordnung zum Reglement über die familienergänzende Kinderbetreuung (SRS 8.1-1) | 1 | as enacted, 1 August 2026 |
| `8-1-2-kinderbetreuungsreglement/` | Reglement über die familienergänzende Kinderbetreuung (SRS 8.1-2) | 1 | as enacted, 1 January 2026 |
| `8-1-3/` | Verordnung über die Beiträge an ungedeckte Aufenthaltskosten in der Langzeitpflege (SRS 8.1-3) | 1 | as enacted, 1 January 2026 |
| `8-2-1/` | Bestattungs- und Friedhofreglement (SRS 8.2-1) | 1 | as enacted, 1 January 2026 |
| `8-2-2/` | Verordnung zum Bestattungs- und Friedhofreglement (SRS 8.2-2) | 1 | as enacted, 1 January 2026 |
| `8-3-1/` | Reglement über das Halten von Hunden und die Erhebung der Hundesteuer (SRS 8.3-1) | 1 | as enacted, 1 January 2025 |
| `9-4-1/` | Reglement zur Erhebung einer Beherbergungsabgabe (SRS 9.4-1) | 1 | as enacted, 1 January 2015 |
| `9-5-1/` | Festlegung der Freinächte (SRS 9.5-1) | 1 | as enacted, 25 October 2004 |

## Source

The SRS (systematic collection) of the municipality, published by the municipality at <https://menzingen.tlex.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CRS). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the municipality's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (CRS), with an e-mail address that cannot exist (`<act key>@menzingen.tlex.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the municipality publishes as binding. The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
