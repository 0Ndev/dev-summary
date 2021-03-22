# Design Patterns – Entwurfsmuster

##  :arrows_clockwise: wiederverwendbare Vorlagen

Mit Design Patterns stehen **vorgefertigte Muster** zur Verfügung, mit denen ein explizites Problem gelöst wird, indem man auf ein **bewährtes Konzept** zurückgreift.

Bestimmte Abläufe wiederholen sich immer wieder, die durch den Einsatz von wiederverwendbaren Entwurfsmustern (praxisbewährte Lösungs-Schablonen) einen sich wiederholenden Software-Programmieraufwand verhindern.

Entwurfsmuster sind eine Beschreibung (wie eine Art Rezept), wie ein Problem zu lösen ist.


Entwurfsmuster sind **universell einsetzbar**, weil sie erst einmal nicht an eine Programmiersprache gebunden sind.

<br>

## :white_check_mark: Vorteile

- ermöglicht auf bewährte Lösungsansätze zurückzugreifen
- Zeit- und Kostenersparnis (nicht ständig das Rad neu erfinden)
- vereinfachte Dokumentation einer Software
- einfachere Wartung und Weiterentwicklung eines Programms

## :x: Nachteile

- setzt auf umfangreiches Wissen voraus
- Kreativität und Neugier kann eingeschränkt werden, um neue (bessere) Lösungsansätze zu finden

<br>

## :blue_book: Arten mit Kategorien

Die Arten der Entwurfsmuster repräsentieren die grundsätzlichen Einsatzgebiete der darin jeweils versammelten Software Patterns.

<br>

###  :ledger: **Strukturmuster** (Structural Patterns)

Das sind **vorgefertigte Schablonen für Beziehungen zwischen Klassen** und Kapselung komplexen Strukturen.

Dabei wird eine **Abstraktion** angestrebt, die auch mit anderen Lösungsansätzen kommunizieren kann (**Schnittstellen-Programmierung / API**).


- :memo: **Composite Pattern** (**Kompositum**, zusammengesetztes Strukturmuster)

richtet sich speziell auf den Umgang mit dynamischen Strukturen aus ist, z. B. zur Dateiorganisation oder Datenkompression.

- :memo: **Decorator Pattern** (Dekorierer)

integriert in bestehende Klassen weitere Funktionalitäten oder Zuständigkeiten.

- :memo: **Facade Pattern** (Fassade)

stellt eine Schnittstelle zu anderen (Unter- bzw. Sub-)Systemen dar.

<br>

###  :ledger: **Verhaltensmuster** (Behavioral Patterns)

Damit wird das **Verhalten der Software** modelliert. 

Diese Patterns **vereinfachen komplexe Prozesse/Strukturen zur Steuerung und Kontrolle**, die während der Laufzeit schwer zu analysieren sind.      
Dazu kann zwischen Algorithmen und den Verantwortlichkeiten der Objekte gewählt werden.

- :memo: **Observer Pattern** (Beobachter)

reicht Änderungen an einem Objekt an Strukturen weiter, die vom Ursprungsobjekt abhängen.

- :memo: **Strategy Pattern** (Strategie)

definiert eine Familie von austauschbaren Algorithmen

- :memo: **Visitor Pattern** (Besucher)

kapselt ausführbare Operationen so ab, dass neue Operationen ohne Veränderung der betroffenen Klassen vorgenommen werden.


<br>

### :ledger: **Entwurfsbasierte Erzeugungsmuster** (Creational Patterns)

Damit werden Objekte erzeugt, unabhängig davon, auf welche Weise einzelne Objekte in einer Software erstellt und dargestellt werden.

- :memo: **Builder Pattern** (Erbauer)

trennt die Entwicklung von (komplexen) Objekten von deren Repräsentationen.

- :memo: **Factory Pattern** (Fabrikmethode)

erzeugt ein Objekt durch den Aufruf einer Methode und statt durch den eines Konstruktors.

- :memo: **Singleton Pattern** (Einzelstück)

sorgt dafür, dass on einer Klasse nur genau ein Objekt existiert. Darüber hinaus ist ein Singleton global verfügbar.

<br>


