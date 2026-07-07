---
aliases:
  - Schurkenwaffe
tags:
  - Liste/Waffen
---
# `=this.file.name`

## Nahkampfwaffen
```dataview
TABLE WITHOUT ID
file.link AS "Waffe",
Reichweite,
"`dice:" + Schaden + "\|none\|noform`"  AS "Schaden",
Schadensart,
Rüstungsdurchschlag AS "RD",
Mindeststärke AS "Min-ST", 
Hände, 
Eigenschaften
FROM (#Gegenstand/Waffe/Einfache_Waffe OR (#Gegenstand/Waffe/Kriegswaffe AND ([[Finesse]] OR [[Leicht]]))) AND !#Gegenstand/Magischer_Gegenstand AND #Gegenstand/Waffe/Nahkampfwaffe 
SORT Kategorie
```

## Fernkampfwaffen
```dataview
TABLE WITHOUT ID
file.link AS "Fernkampfwaffe",
"`dice:" + SchadenFern + "\|none\|noform`"  AS "Schaden",
SchadensartFern AS "Schadensart", 
Range1 AS "Minimalreichweite", 
Range2 AS "Grundreichweite", 
Range3 AS "Maximalreichweite", 
Kategorie,
Hände,
Gewicht, 
EigenschaftenFern
FROM (#Gegenstand/Waffe/Einfache_Waffe OR (#Gegenstand/Waffe/Kriegswaffe AND ([[Finesse]] OR [[Leicht]]))) AND !#Gegenstand/Magischer_Gegenstand AND #Gegenstand/Waffe/Fernkampfwaffe 
SORT Kategorie
```