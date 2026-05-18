---
aliases:
  - Rüstung
---
# `=this.file.name`

```dataview
TABLE  WITHOUT ID 
file.link AS "Title",
Klasse, 
RK, 
Dex_cap AS "GES Cap",
Heimlichkeit, 
Stärke, 
Eigenschaften, 
Gewicht, 
Kosten
FROM #Gegenstand/Rüstung
SORT Klasse, RK, Dex_cap
WHERE file.name != "Vorlage Rüstung"
AND Klasse
```