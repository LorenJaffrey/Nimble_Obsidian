---
aliases: 
  - Schild
tags:
---
# `=this.file.name`

```dataview
TABLE  WITHOUT ID 
file.link AS "Title",
Klasse, 
RK,
Stärke, 
Dex_cap AS "GES Cap", 
Heimlichkeit,
Eigenschaften, 
Gewicht, 
Kosten
FROM #Gegenstand/Schild 
SORT RK
```