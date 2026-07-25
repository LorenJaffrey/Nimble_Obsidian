---
tags:
  - Regeln/Nimble/Rasten/Rastaktionen
aliases:
  - Rastaktion
---
# `=this.file.name`
[[Rastaktionen]] sind Aufgaben, die ein Charakter während einer langen Rast übernehmen kann. 
Jeder Charakter kann langer Rast **eine** [[Rastaktion]] wählen. 
Eine [[Rastaktionen|Rastaktion]] beschreibt eine sinnvolle Tätigkeit während der Rast und kann zusätzliche Vorteile, kleine Boni oder besondere Effekte gewähren.

```dataview
TABLE WITHOUT ID

file.link AS "Rastoption",
Beschreibung

FROM #Regeln/Nimble/Rasten/Rastaktionen/Rastaktion 

SORT file.name
```