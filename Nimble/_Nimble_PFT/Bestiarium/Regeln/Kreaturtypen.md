---
aliases:
- Kreaturtyp
---
# `=this.file.name`
Der Typ eines Monsters beschreibt seine grundlegende Natur.
Bestimmte Zauber, magische Gegenstände, Klassenmerkmale und andere Effekte im Spiel interagieren auf bestimmte Weise mit Monstern eines bestimmten Typs. 
Beispielsweise fügt ein Todespfeil (Drachen) nicht nur Drachen, sondern auch anderen Kreaturen des Drachentyps, wie Drachenschildkröten und Wyvern, zusätzlichen Schaden zu.
Das Spiel verwendet die folgenden Monstertypen, die keine eigenständigen Regeln verwenden.

```dataview
TABLE WITHOUT ID

file.link AS "Title",
Identifizieren,
Plündern

FROM #Kreatur/Typ

SORT Identifizieren, file.name
```