# Datenbanken

## Einfuehrung

### Dateisystem
* Inkonsistenz der Daten 
    * Muessen manuell an mehreren Orten gepflegt werden
* Redundanzen
    * mehrfache Speicherung von Daten, aufwaendige Pflege, hohe Fehlerrate der Daten
* Datenschutzprobleme
    * Zugriff muss auf ganze Datei gegeben werden, Pflegen der Berechtigungen unuebersichtlich und aufwendig
* Keine Datenunabhaengigkeit
    * Datenverwaltung nicht ohne weiteres effizient moeglich, strukturelle Aenderungen sehr aufwendig

### Datenbanksystem (DBS)
* Effiziente Kontrolle ueber die Daten 
* Datenintegritaet 
* Mehrbenutzerbetrieb moeglich 
* Hohe Datenunabhaengigkeit


### Datenbanken (DB)
> Datenbanken enthalten die logisch verknuepften Daten und sind damit das grundlegene Element des Datenbanksystems
#### Hierarchische Datenbanken 
* Aufgebaut mit einfachem, multidimensionalem Nesting
#### Netzwerkdatenbanken 
* Logische Verknuepfungen zwischen zusammenhaengenden Datensaetzen, bspw mit Abteilungen, Mitarbeitern, Projekten
#### Relationale Datenbanken 
* Verknuepfung eines Hauptdatensatzes zu detaillierteren Datensaetzen
#### Objektorientierte Datenbanken 
* gruppierte Datensaetze, linear miteinander verknuepft 
#### NoSQL Datenbanken 
* No SQL / Not only SQL 
* Key-Value Storing, Column Storing, Graph Databases, Document Stores 

### Datenbankmanagementsystem (DBMS)
> Ein DBMS ist eine Schnittstelle (Anwendungsprogramm) zwischen Datenbank und Nutzer, die das Verwalten der Daten sowie der Nutzerrechte etc. ermoeglicht.