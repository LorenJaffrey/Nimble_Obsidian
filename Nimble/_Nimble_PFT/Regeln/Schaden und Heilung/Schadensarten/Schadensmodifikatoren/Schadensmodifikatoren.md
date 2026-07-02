---
tags:
  - Regeln/Nimble/Schaden
aliases:
  - Schadensmodifikator
---
# `=this.file.name`
Manche Kreaturen, Gegenstände, Effekte oder Zustände verändern, wie stark sie von bestimmten [[Schadensarten]] betroffen sind. 
Diese Veränderungen werden als [[Schadensmodifikatoren]] bezeichnet. 
[[Schadensmodifikatoren]] beziehen sich immer auf eine bestimmte [[Schadensarten|Schadensart]] oder auf eine klar benannte Schadensquelle.

Es gibt zwei Arten von [[Schadensmodifikatoren]]: **flache Modifikatoren** und **Typmodifikatoren**. 
Flache Modifikatoren verändern den Schaden um einen festen Wert, etwa +5 oder -10. 
Typmodifikatoren legen fest, ob eine Kreatur gegen eine [[Schadensart]] immun, resistent oder anfällig ist.

## Flache Modifikatoren
Flache Modifikatoren erhöhen oder verringern den verursachten Schaden um einen festen Wert. 
Ein Bonus von +5 erhöht den Schaden um 5, ein Malus von -10 verringert den Schaden um 10. 
Sinkt der Schaden dadurch unter 0, wird er stattdessen auf 0 gesetzt.

## Typmodifikatoren
**[[Schadensimmunität]]** bedeutet, dass eine Kreatur von einer bestimmten [[Schadensarten|Schadensart]] keinen Schaden erleidet.  
**[[Schadensresistenz]]** bedeutet, dass eine Kreatur gegen eine bestimmte [[Schadensarten|Schadensart]] nur den halben Schaden erleidet.  
**[[Schadensanfälligkeit]]** bedeutet, dass eine Kreatur gegen eine bestimmte [[Schadensarten|Schadensart]] doppelten Schaden erleidet.

Mehrere gleiche Typmodifikatoren auf dieselbe [[Schadensart]] werden nicht addiert. 
Eine Kreatur mit mehrfacher [[Schadensresistenz]] gegen dieselbe [[Schadensart]] bleibt einfach resistent, und eine Kreatur mit mehrfacher [[Schadensanfälligkeit]] bleibt einfach anfällig.
Treffen [[Schadensresistenz]] und [[Schadensanfälligkeit]] gleichzeitig auf dieselbe [[Schadensart]] zu, heben sie sich gegenseitig auf.

## Reihenfolge der Anwendung
Wenn Schaden durch [[Schadensmodifikatoren]] verändert wird, wird er in folgender Reihenfolge abgehandelt:

1. Zuerst wird geprüft, ob eine **[[Schadensimmunität]]** vorliegt. Ist das der Fall, wird der Schaden auf 0 gesetzt.
2. Danach werden alle **flachen Modifikatoren** auf den Schaden angewendet.
3. Anschließend wird eine vorhandene **[[Schadensresistenz]]** angewendet.
4. Zuletzt wird eine vorhandene **[[Schadensanfälligkeit]]** angewendet.

Ergibt eine Halbierung einen ungeraden Wert, wird der Schaden abgerundet.

>[!Example] Beispiel
>Eine Kreatur ist gegen alle [[Schadensarten]] [[Schadensresistenz|resistent]], [[Schadensanfälligkeit|anfällig]] für [[Feuerschaden]], und sie befindet sich innerhalb einer magischen Aura, die jeden Schaden um 5 verringert. 
>Wenn diese Kreatur 28 [[Feuerschaden]] erleidet, wird der Schaden zuerst um 5 verringert (auf 23), dann aufgrund der [[Schadensresistenz]] halbiert (und auf 11 abgerundet) und zum Schluss aufgrund der [[Schadensanfälligkeit]] verdoppelt (auf 22).