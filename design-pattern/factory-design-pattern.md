# Design Pattern

## Factory Method (Fabrik, Kreatives Designmuster)


Objekte können erstellt werden, ohne die genaue Klasse anzugeben, die zum Erstellen des jeweiligen Objekts erforderlich ist.        
Dadurch können wir den Code entkoppeln und seine Wiederverwendbarkeit verbessern.

Factory Method ist nur für bestimmte Situationen geeignet und nicht für jedes Entwicklungsszenario.

Das Entwurfsmuster der Factory-Methode wird häufig in Bibliotheken verwendet, indem Clients auswählen können, welche Unterklasse oder welcher Objekttyp über eine abstrakte Klasse erstellt werden soll.



## Vorteile

Der Code wird lose gekoppelt, da die Mehrheit der Komponenten unseres Codes andere Komponenten derselben Codebasis nicht kennt.

Der Code ist leicht zu verstehen und zu testen und hinzufügt bestimmten Komponenten mehr Funktionen, ohne das gesamte Programm zu beeinträchtigen oder zu beschädigen.

Hilft auch dabei, das Muster aufrechtzuerhalten *Prinzip der Einzelverantwortung*.


## Nachteile

geringeren Lesbarkeit, jedoch in Kombination mit einer Abstract Factory (Fabrik der Fabriken) kann gewartet werden


