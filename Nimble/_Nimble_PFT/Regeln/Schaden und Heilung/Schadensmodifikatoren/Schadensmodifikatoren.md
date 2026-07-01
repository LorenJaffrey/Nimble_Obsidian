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

Es gibt zwei Arten von Schadensmodifikatoren: **flache Modifikatoren** und **Typmodifikatoren**. 
Flache Modifikatoren verändern den Schaden um einen festen Wert, etwa +5 oder -10. 
Typmodifikatoren legen fest, ob eine Kreatur gegen eine Schadensart immun, resistent oder anfällig ist.

## Flache Modifikatoren
Flache Modifikatoren erhöhen oder verringern den verursachten Schaden um einen festen Wert. 
Ein Bonus von +5 erhöht den Schaden um 5, ein Malus von -10 verringert den Schaden um 10. 
Sinkt der Schaden dadurch unter 0, wird er stattdessen auf 0 gesetzt.

## Typmodifikatoren
**[[Schadensimmunität]]** bedeutet, dass eine Kreatur von einer bestimmten Schadensart keinen Schaden erleidet.  
**[[Schadensresistenz]]** bedeutet, dass eine Kreatur gegen eine bestimmte Schadensart nur den halben Schaden erleidet.  
**[[Schadensanfälligkeit]]** bedeutet, dass eine Kreatur gegen eine bestimmte Schadensart doppelten Schaden erleidet.

Mehrere gleiche Typmodifikatoren auf dieselbe Schadensart werden nicht addiert. Eine Kreatur mit mehrfacher Resistenz gegen dieselbe Schadensart bleibt einfach resistent, und eine Kreatur mit mehrfacher Anfälligkeit bleibt einfach anfällig. Treffen Resistenz und Anfälligkeit gleichzeitig auf dieselbe Schadensart zu, heben sie sich gegenseitig auf.[[dndbeyond](https://www.dndbeyond.com/forums/dungeons-dragons-discussion/rules-game-mechanics/126384-resistance-and-vulnerability)][[youtube](https://www.youtube.com/watch?v=KEAvSIwQoOI)]

## Reihenfolge der Anwendung

Wenn Schaden durch Schadensmodifikatoren verändert wird, wird er in folgender Reihenfolge abgehandelt:

1. Zuerst wird geprüft, ob eine **Schadensimmunität** vorliegt. Ist das der Fall, wird der Schaden auf 0 gesetzt.
    
2. Danach werden alle **flachen Modifikatoren** auf den Schaden angewendet.
    
3. Anschließend wird eine vorhandene **Schadensresistenz** angewendet.
    
4. Zuletzt wird eine vorhandene **Schadensanfälligkeit** angewendet.[[reddit](https://www.reddit.com/r/dndnext/comments/2dzugj/question_about_resistance_and_flat_damage/)]
    

Ergibt eine Halbierung einen Bruchwert, wird der Schaden abgerundet.[[dandwiki](https://www.dandwiki.com/wiki/5e_SRD:Damage_Resistance_and_Vulnerability)]

## Beispiel

Eine Kreatur erleidet 25 Feuerschaden und besitzt eine Feuerresistenz. Zusätzlich verringert ein Effekt den erlittenen Feuerschaden um 5. Der Schaden wird zuerst um 5 reduziert und sinkt auf 20, danach halbiert die Resistenz den Wert auf 10.[[dndbeyond](https://www.dndbeyond.com/forums/dungeons-dragons-discussion/rules-game-mechanics/126384-resistance-and-vulnerability)]

> **Umgangssprachlich:** Erst wird geprüft, ob der Schaden überhaupt durchkommt. Danach verändern feste Boni oder Mali den Wert, und erst dann greifen Resistenz oder Anfälligkeit. Immunität schlägt dabei alles.[[facebook](https://www.facebook.com/groups/392678574938393/posts/1759364861603084/)][[youtube](https://www.youtube.com/watch?v=KEAvSIwQoOI)][[dndbeyond](https://www.dndbeyond.com/forums/dungeons-dragons-discussion/rules-game-mechanics/126384-resistance-and-vulnerability)]