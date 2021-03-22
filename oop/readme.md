# Objektorientierte Programmieren

Ein objektorientiertes Programm ist ein System von Objekten, die untereinander Botschaften austauschen.



Zur visuellen Beschreibung von objektorientierten Programmen werden häufig die grafischen Symbole von **UML** (Unified Modeling Language) verwendet.

---

## Klassen

Klasse ist ein **Bauplan für Objekte** und beschreiben der prinzipielle Aufbau und das Verhalten einer Menge von Objekten. 

## Objekte

Objekt ist eine **Instanzen (Inkarnation) einer Klassen** (gehört immer zu einer bestimmten Klasse).

Objekte repräsentieren Dinge der realen Welt und haben gewisse gemeinsame Merkmale.

Ein Objekt befindet sich zu jedem Zeitpunkt seiner Existenz in einem bestimmten Zustand. Der Zustand ergibt sich aus den momentanen Werten der Attribute.

### Attribute

Attribute beschreiben die **Merkmale eines Objektes** (Eigenschaften). 

### Methoden

Methoden sind keine selbständige Objekte, sondern integraler Bestandteil einer Klasse und definieren das **Verhalten der Objekte**. 

<br>

---

## Abstraktion

Die wesentliche Aspekte einer Sache ermitteln und das Unwichtige (unwesentliche Daten) weglassen.

## Verkapselung (encapsulation)

Operationen und logisch zusammengehörige Daten (Attribute) werden zu einer Einheit (einer Klasse) verschmolzen.

## Geheimprinzip (information hiding)

Der Zustand eines Objektes (Werte der Attribute) und die Implementierung der Methoden sind nach außen nicht sichtbar.   
Alle Attribute sind streng privat.

Änderungen des Zustandes eines Objektes können von außen nur über Methodenaufrufe (Botschaften) ermöglicht werden. 

## Vererbung

Vererbung beschreibt die **Beziehung zwischen einer allgemeinen Klasse** (Basisklasse, Oberklasse) **und einer spezialisierten Klasse** (Subklasse, Unterklasse). 

Die Subklasse besitzt sämtliche Attribute und Methoden der Basisklasse und können zusätzliche Attribute und Methoden haben. Die Methoden können durch Überschreiben(overriding) neu definiert werden.

## Spezialisierungen

Von einer Basisklasse können spezielle Subklassen gebildet werden.

---

## Polymorphismus

Polymorphismus ermöglicht den **gleichen Namen** für (mehr oder weniger) gleichartige Operationen zu verwenden, um dann es **auf Objekte unterschiedlicher Klassen anzuwenden**.        
Man spricht von einer **Überladung** (**overloading**) einer Operation.

### Beispiel (Python)

Ein Beispiel dafür ist der **Plusoperator**, der durch die Methode `__add__()` repräsentiert wird und auf Zahlen oder Strings angewendet werden kann. Je nach Datentyp wirkt `+ ` als Addition oder Konkatenation.

Ein weiteres Beisiel ist die `__init__()` Methode, die eine Überladung der Zuweisungsoperators `= `verwendet wird, um eine Instanz einer Klasse zu bilden.

---
<br>

### :computer: Beispiel

```py


```


```py

```


