---
aliases:
  - Stärkewurf
  - Stärkewürfe
  - Stärkewürfen
  - Stärkewurfs
  - ST
  - STR
tags:
  - Regeln/Nimble/Attribut
Beschreibung: Misst die körperliche Kraft, das athletische Training und das Maß in dem du rohe Gewalt ausüben kannst.
---
# `=this.file.name`
`=this.Beschreibung`

## Verbundene Fertigkeiten
```dataview
TABLE WITHOUT ID

file.link AS "Fertigkeit",
Beschreibung

FROM #Regeln/Nimble/Fertigkeit/Stärke 

SORT file.name
```

## Vorteile

### Traglast
Gewicht das Charaktere mit sich herumtragen können.
[[Stärke]] x 15

### Schieben, Ziehen, Heben
[[Stärke]] x 30
Wenn Gewicht geschoben, oder gezogen wird das höher als Traglast ist sinkt [[Bewegungsrate]] auf 1,5 Meter

### Größe und Stärke
Große Kreaturen verdoppeln Traglast.
Winzige Kreaturen halbieren Traglast.

### Belastung
- Wenn Gewicht der Ausrüstung > [[Stärke]] x 5 -> Belastet ( [[Bewegungsrate]] -3m)
- Wenn Gewicht der Ausrüstung > [[Stärke]] x 10 -> Stark_Belastet ( [[Bewegungsrate]] -6m; Nachteil bei [[Attribute#Attributswurf]] und [[Stärkerettungswürfe|ST-Rettungswürfen]], [[Beweglichkeitsrettungswürfe|BW-Rettungswürfen]] und [[Konstitutionsrettungswürfe|KO-Rettungswürfen]])