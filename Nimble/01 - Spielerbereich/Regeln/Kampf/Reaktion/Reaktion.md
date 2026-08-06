---
tags:
  - 
aliases:
  - Reaktionen
---
# `=this.file.name`
[[Reaktion|Reaktionen]] kosten normalerweise  1 [[Aktionspunkte|Aktionspunkt]] ([[Aktionspunkte|AP]]) und können ausgeführt werden, wenn du **NICHT** am [[Zug]] bist. 
Ein Held kann jede [[Reaktion]] höchstens  einmal  pro [[Runde]] einsetzen und beginnt seinen nächsten [[Zug]] dann mit entsprechend weniger [[Aktionspunkte|Aktionspunkten]].

```dataview
TABLE WITHOUT ID

file.link AS "Reaktion",
Beschreibung,
Kosten

FROM #Zug/Reaktion

SORT file.name
```