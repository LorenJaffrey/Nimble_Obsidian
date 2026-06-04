---
aliases: 
tags:
  - Merkmal/Klasse/Kämpfer/Kampfmeister
---
# `=this.file.name`

Du lernst [[_Kampfüberlegenheit#Manöver]], für die du eine spezielle Art von Würfeln benötigst: die [[_Kampfüberlegenheit#Überlegenheitswürfel]].
Viele verbessern auf die eine oder andere Weise deinen [[Angriff]]. 
Du kannst pro [[Angriff]] nur ein [[_Kampfüberlegenheit#Manöver]] einsetzen. 
Jedes Mal, wenn du neue [[_Kampfüberlegenheit#Manöver]] lernst, kannst du zusätzlich auch ein altes, das du bereits kennst, durch ein anderes ersetzen.

## Überlegenheitswürfel 
Du besitzt vier Überlegenheitswürfel, die W8 sind. 
Benutzt du einen Überlegenheitswürfel im Rahmen eines [[_Kampfüberlegenheit#Manöver]] wird er verbraucht. 
Du erhältst alle verbrauchten Überlegenheitswürfel nach Beenden einer [[Feldrast|Kurzen Rast]] oder [[Sichere Rast|Langen Rast]] zurück.

## Rettungswürfe
Manche deiner Manöver erfordern von deinem Ziel einen [[Rettungswurf]], um den Auswirkungen des [[_Kampfüberlegenheit#Manöver]]s zu widerstehen. 
Der [[Schwierigkeitsgrad]] des [[Rettungswurf]]s wird folgendermaßen berechnet:

>[!info] [[Schwierigkeitsgrad|SG]] für [[Rettungswurf]] gegen [[_Kampfüberlegenheit#Manöver]]
>8 + dein [[_Übung|Übungsbonus]] + dein [[Stärke#Stärkemodifikator]] oder [[Geschicklichkeit#Geschicklichkeitsmodifikator]] (nach Wahl)

## Manöver
```dataview
TABLE WITHOUT ID

file.link AS "Manöver"

FROM #Merkmal/Klasse/Kämpfer/Kampfmeister/Manöver 

SORT file.name
```