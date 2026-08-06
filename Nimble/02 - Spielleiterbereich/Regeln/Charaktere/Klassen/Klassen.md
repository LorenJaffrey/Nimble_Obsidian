---
tags:
  - Regeln/Nimble/WIP
---
# `=this.file.name`

```dataview
TABLE WITHOUT ID

file.link AS "Title"

FROM #Regeln/Nimble/Charakter/Klasse

SORT file.name
```

## Klassenideen
| Klasse          | Subklassen                                                                        | Identität                         | Rüstung       | Primäre Ressource | Magie      | TP  | RP  |
| --------------- | --------------------------------------------------------------------------------- | --------------------------------- | ------------- | ----------------- | ---------- |:---:|:---:|
| [[Taktiker]]    | Melee DD, Melee Tank, Kommandant (Support)                                        | Kämpfer, Support                  | Mittel/Schwer | Fokus (Flow)      |            | +2  |  -  |
| [[Paladin]]     | Melee DD, Melee Tank, Inquisitor/Interrogator                                     | Kämpfer/Caster Hybrid, Auren      | Mittel/Schwer | Heilige Macht     |            | +2  |  -  |
| [[Druide]]      | Melee DD/Tank, Heiler, Caster DD                                                  | Allrounder                        | Leicht        | Mana (Pool)       | Natur      | +1  |  -  |
| [[Gauner]]      | Assassine , Duellant, Strippenzieher                                              |                                   | Leicht        |                   |            | +1  |  -  |
| [[Arkanist]]    | Pyromant (Caster DD, Crits), Glaciomant (Caster DD, Control), Chronomant (Heiler) |                                   | -             | Mana (Pool)       | Arkan      |  -  |  -  |
| [[Fluchwirker]] | Caster DD (DoTs), Beschwörer, Melee/Caster Hybrid DD                              | Caster                            | -             | Fluchkraft        | Fluchkraft |  -  |  -  |
| [[Priester]]    | Heilig (Heiler), Disziplin (Hybrid), Schatten (Caster DD)                         | Caster, Heiler, Göttlicher Caster | -             | Mana (Pool)       | Göttlich   |  -  |  -  |
| [[Berserker]]   | Melee DD, Kopfjäger (Melee/Ranged Hybrid DD),                                     | Melee DD, Rage                    | -             | Wut (Flow)        |            | +1  |  -  |
| [[Windläufer]]  | Elemente (Control), Drunken Master (Tank), Eisenfaust (Combo-DD)                  |                                   | -             | Ki (Flow)         |            | +1  |  -  |
| [[Jäger]]       | Scharfschütze, Bestienmeister, Späher/Fallensteller                               | Ranged DD                         | Leicht/Mittel |                   |            | +1  |  -  |

## Subklassenübersicht
### [[Taktiker]]
Klassischer Kämpfer-Archetyp

| Subklasse  | Identität               | Rolle            | Rüstung       |
| ---------- | ----------------------- | ---------------- | ------------- |
| ???        | Kämpfer (Waffenfokus)   | Nahkampf DD      | mittel/schwer |
| ???        | Kämpfer (Rüstungsfokus) | Nahkampf Tank    | schwer        |
| Kommandant | Befehle, Ansporn        | Nahkampf Support | mittel/schwer |

### [[Paladin]]
Heiliger Krieger, Auren, Heilige Fähigkeiten (keine Zauber!)

| Subklasse | Identität                  | Rolle                    | Rüstung       |
| --------- | -------------------------- | ------------------------ | ------------- |
| ???       | Heiliger Ritter (offensiv) | Nahkampf DD              | schwer        |
| ???       | Heiliger Ritter (defensiv) | Nahkampf Tank            | schwer        |
| ???       | Inquisitor/Interrogator    | Nahkampf/Support/Debuffs | mittel/schwer |

### [[Druide]]
Naturmagie, Gestaltwandlung, Gestirne, etc.

| Subklasse | Identität       | Rolle            | Rüstung      |
| --------- | --------------- | ---------------- | ------------ |
| ???       | Tiergestalten   | Nahkampf DD/Tank | keine/leicht |
| ???       | Heilung/Natur   | Heiler/Support   | keine/leicht |
| ???       | Caster/Gestirne | Caster DD        | keine/leicht |

### [[Gauner]]
Gauner, Schurke, Attentäter, etc.

| Subklasse  | Identität             | Rolle               | Rüstung |
| ---------- | --------------------- | ------------------- | ------- |
| Attentäter | Verstohlenheit, Gifte | Nahkampf DD         | leicht  |
| Duellant   | Mantel und Degen      | Nahkampf DD/Control | leicht  |
| ???        |                       |                     | leicht  |

### [[Arkanist]]
Arkaner Magiewirker, Gelehrter, etc.

| Subklasse  | Identität                | Rolle                    | Rüstung |
| ---------- | ------------------------ | ------------------------ | ------- |
| Pyromant   | Feuermagie, Crit-basiert | Caster DD                | keine   |
| Glaciomant | Eismagie, Kontrolle      | Caster DD/Control        | keine   |
| Chronomant | Zeitmagie                | Caster DD/Heiler/Support | keine   |

### [[Fluchwirker]]
Kanalisiert negative Energien, nicht unbedingt böse, aber eher verpönt im Vergleich zum Arkanisten.

| Subklasse | Identität              | Rolle                  | Rüstung      |
| --------- | ---------------------- | ---------------------- | ------------ |
| ???       | Flüche, Debuffs        | Caster DD/Debuffs      | keine/leicht |
| ???       | Beschwörung            | Caster DD/Pets         | keine/leicht |
| ???       | Metamorphose/Blutmagie | Caster/Melee DD Hybrid | keine/leicht |

### [[Priester]]
Nutzt Primordiale Magiequellen Licht/Schatten bzw. eine Neutralform.

| Subklasse | Identität                   | Rolle             | Rüstung |
| --------- | --------------------------- | ----------------- | ------- |
| ???       | Lichtmagie/Stärkung/Heilung | Heiler/Support    | keine   |
| ???       | Schattenmagie/Chaos/Entzug  | Caster DD/Debuffs | keine   |
| ???       | Gleichgewicht               |                   | keine   |

### [[Berserker]]
Wut, Mobilität, Hoher Schaden.

| Subklasse | Identität                    | Rolle                 | Rüstung      |
| --------- | ---------------------------- | --------------------- | ------------ |
| ???       | Nahkampf/hoher Einzelschaden | Nahkampf DD           | keine/leicht |
| ???       |                              |                       | keine/leicht |
| ???       | Nahkampf/Wurfwaffen          | Nahkampf/Fernkampf DD | keine/leicht |

### [[Windläufer]]
Mönch-Style, Waffenloser Kampf/Mönchswaffen, Beweglichkeit, Mobilität

| Subklasse | Identität      | Rolle               | Rüstung      |
| --------- | -------------- | ------------------- | ------------ |
| ???       | Elemente       | Nahkampf DD/Control | keine/leicht |
| ???       | Drunken Master | Nahkampf Tank       | keine/leicht |
| ???       | Combos         | Nahkampf DD         | keine/leicht |

### [[Jäger]]
Jäger, Waldläufer, Naturverbunden.

| Subklasse      | Identität           | Rolle            | Rüstung       |
| -------------- | ------------------- | ---------------- | ------------- |
| Scharfschütze  | Fernkampf           | Fernkampf DD     | leicht/mittel |
| Bestienmeister | Pet                 | Fernkampf DD/Pet | leicht/mittel |
| ???            | Trapper/Spurenleser |                  | leicht/mittel |