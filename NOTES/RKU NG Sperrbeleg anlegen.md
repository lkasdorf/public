#SAP/IS-U #RKU

# Sperrbeleg anlegen Q61/021 und Q1D/105

- Q61 021
	- CIC0 Malo suchen
	- Rechte Maustaste auf Anlage --> Sperrbeleg anlegen
	- Grund auswählen (irgendeinen) --> Schritt vor
	- Sperrauftrag erzeugen
		- Nur Strom sperren -> Gas abwählen
- Q1D 105
	- Es wird ein PDOC empfangen und dieses legt den Sperrbeleg an
	- Diesen findet man in den Kopfdaten des PDocs
	- Dann muss man die Sperrung bearbeiten bzw. durchführen im System
	- Danach wird ein PDOC angelegt, dass die abrechenbaren Positionen erstellt

# Beispiele vom 01.11.2023

Sperrkostenabrechnung Q1D 105

 - Serviceanbietervereinbarung und VK
 - Preiskatalog für GRDB
 
 PDoc: 00000000000000041230
 Malo: 10126641290
 
 37803/10 105/01.11.2023/#2008458# Nacharbeiten CI (Sperr/MMM
 
 Preiskatalog versenden: Report /US4G/RP_TRIGGER_PRICAT_PROC