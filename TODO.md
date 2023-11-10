# Links

[Plain Text Notes Information](NOTES/Plain%20Text%20Notes%20Information.md)

# 2023

## 10-2023

### 2023-10-23 monday

- *DM*: **Meeting**: Refinement DM
	- Termin, um festzulegen, wie ein gutes Refinement aussieht
	- Mehr Details in den Refinements
	- Dominik bereitet das nochmal auf
	- [Team Task Refinement](https://docmorrisgroup.atlassian.net/wiki/spaces/CIT/pages/3035168892/Team+Task+Refinement)
	- [Refinement Sprint 8](https://docmorrisgroup.atlassian.net/wiki/spaces/CIT/pages/3019342093/8.+Sprint+-+Refinement+List)
- Timesheet bookings
	  - RKU Cats
	  - Timetrack
	  - ZEP
- *DM*: Dewi: Transport veranlassen (Abschreibungsart)
	- wurde um 11:46 erfolgreich und ohne Fehler ins HR1 importiert
- *DM*: **Meeting**: Matching Tool Nomentia
	- Präsentation wird im Nachhinein zur Verfügung gestellt
	- DM will das vor allem für AP (Direct Debit)
	- Einzüge werden bei N hochgeladen, wir kriegen die "Matches" wieder, wir müssen aber die offenen Posten bei N hochladen
	- Eigentlich ist es doppelte Arbeit, da es auch hier nur von der Qualität der N-Suchmuster abhängt.
	- Neuer Task: Suchmuster nur mit Partner IBAN [# Elektronischer Kontoauszug: Suchmusterermittlung nur mit Partner-IBAN](https://docmorrisgroup.atlassian.net/browse/DDO-1097) 
- *DM*: [DDO-696](https://docmorrisgroup.atlassian.net/browse/DDO-696) --> Walter muss eine Aufgabe freigeben (Charm 4000001859, Transport HRDK937429)
	- Transport von Kopien von Walter durchgeführt

### 2023-10-24 tuesday

- *DM*: Confluence Seite für Suchmusterprobleme erstellen
	- [Confluence Suchmuster](https://docmorrisgroup.atlassian.net/wiki/spaces/CIT/pages/3037135146/Optimierung+Suchmuster)
- *DM*: [DDO-696](https://docmorrisgroup.atlassian.net/browse/DDO-696)
	- Walter hat die Funktionsgruppe in meinen Change überführt (Change 4000002580, Transport HRDK941761)
- *all*: Abwesenheit 31.10.2023 eintragen
	- Mail an RKU und DM geschickt.

### 2023-10-25 wednesday

- *adesso*: Immer noch kein Adtime Projekt
	- Tennyson fragt nochmal nach (11am: Ist jetzt behoben)
- *DM*: Zeiten nacherfassen
- *DM*: Fehler Jelle Bankverbindung Consentmanager
    - Vorschlag Michell: Mahnungen beim Druckdienstleister stornieren, Mahnungen im System stornieren und kommende Woche neu mahnen.   
- 1 pm *DM*: **Meeting**: Amazon - Abgleich der Amazon Daten mit FI-CA
	- Walter transportier am Donnerstag auf die HRQ und wir testen morgen alleine und am Freitag mit dem Fachbereich
- *RKU*: Q1D: MeMi-Abrechnung testen
	- Es gibt immer doch das Problem, dass das PDoc keine Daten hat (MeMi-Beleg 000000000268/PDoc 00000000000000037746 auf Q1D 105)
	- Warten auf Rückmeldung von Deniz Aydin
- *DM*: Refinement [DDO-1097 Suchmuster IBAN](https://docmorrisgroup.atlassian.net/browse/DDO-1097)
	- Kommende Woche mit Walter analysieren und in den Sprint mit reinnehmen

### 2023-10-26 thursday

**Important**: Focus on RKU

- 11 am *RKU*: *Meeting* Iterationsplanung
	- Aus welcher Datei kommen die Tasks für das Backlog?
	- Erledigte Tasks in den nächsten Bucket schieben
	- Offen: Kontoauszugsverarbeitung
- 12 am *RKU*: *Meeting* Projektplanung Ina
	- Christian Plage: Info, wenn Sachen fertig sind, melden. Z.B. SEPA-Mandate
	- Transformationen
		- Klaus PL: Rottweil (ENRW)
		- Ina PL: Werra
		- Leon: DSGVO-konformer Einsatz fraglich
		- Leon und Karl sollen unterstützen (Karl --> Rottweil, Leon --> Werra)
		- Rottweil: Workshop am 13.11.2023
		- Auftrag: 2006242 RKUIT AV Zuarbeiten und Tätigk. NextGen (Text: ENRW: Abstimmung Workshops)
		- PL: Levent?
	- Q1D:
		- Aufträge für Test und/oder Nacharbeiten
- *RKU*: SEPA Funktionsbaustein Mandats-ID übernehmen
    - Wen ansprechen? Deniz Aydin
    - Deniz hat den Fuba übertragen, muss noch in den Events eingetragen werden (/RKU/FKK_SAMPLE_0570)

### 2023-10-27 friday

- 10 am *DM*: **Meeting** Dewi - Customizing Altdatenübernahme
	- Ich muss den Haken "Restwert" noch bei Z11 und Z12 auf HRQ und HRD ändern
	- Erledigt. HRD, HRQ und HR1 nun wieder auf demselben Stand.
- *RKU*: SEPA Baustein in Event 570 eintragen.
	- Fuba ist eingetragen (Request: 0000037669, D1S 101)
- 12 am *DM*: **Meeting**: Amazon und Adyen Abstimmung mit Walter
	- Anpassung Brasilien funktioniert nicht. Neuer Bug: [DDO-1135 - Bug zu DDO-696](https://docmorrisgroup.atlassian.net/browse/DDO-1135)
	- Beispiele (Aufträge): 7004710524, 7004808987
	- FuBa: /CHCNL/FKK_DOCUMENT_CREATE_AMA
- *RKU*: Test MeMi/MGV
	- Deniz muss sich die PDocs anschauen
		- Fehler: Mabis
		- PDoc hat keine Daten
	- Beispiele (MeMi-Belege auf Q1D 105)
		- 000000000277 
		- 000000000276
		- 000000000275
	- MGV-Abrechnung
		- Ich habe mit Sebastian J. getestet (VK 50000000200) und wir sind soweit gekommen, dass wir eine Abrechnung duchführen konnten.
		- Am Montag müssen wir dann die Fehler in der Fakturierung beheben
	- SAV anlegen
		- SAV MEMI müssen noch für DEW_SUP_20 & SBO_SUP_20 angelegt werden
- 2 pm *RKU*: **Meeting**: Kurze Abstimmung NG VNB
	- Ina war nicht da. Ich teste mit Sebastian und wir informieren Karl danach.
- *Kaffon*: NSSF Unterlagen vorbereiten
	- Ich habe alles vorbereitet, es muss noch ausgedruckt werden. Der Rest befindet sich in dem neuen Aktenordner, den ich dann am Dienstag mitnehmen muss.

### 2023-10-30 monday

 - 11:45 *DM* Sprint planning
	 - Meine Tasks
		 - [DDO-1097](https://docmorrisgroup.atlassian.net/browse/DDO-1097) - 5 SP
		 - [DDO-688](https://docmorrisgroup.atlassian.net/browse/DDO-688) - 5 SP
		 - Changes sind beantragt
			 - 4000002654, DDO-688 -Einführung Ordnungsbegriff FICA
			 - 4000002655, DDO-1097 - Elektronischer Kontoauszug
	 - Sprint: 30.10 - 17.11
	 - Refining für diesen Sprint
		 - [DDO-1146](https://docmorrisgroup.atlassian.net/browse/DDO-1146)
		 - [DDO-1145](https://docmorrisgroup.atlassian.net/browse/DDO-1145)
 - *DM* [Zendesk Ticket 10245538](https://zrg04.zendesk.com/agent/tickets/10245538) bearbeiten
	 - Buchen mit FB05 - Selektieren offene Posten - Debitor suchen liefert kein Ergebnis und der Dialogprozess friert ein
 - *DM*: [DDO-1135 - Bug zu DDO-696](https://docmorrisgroup.atlassian.net/browse/DDO-1135) testen
	 - Kukey: 28550 (Deutsche bank)
	 - Hint: Es ist nur eine Buchungsregel definiert (Y014). Es muss noch eine zweite Buchung definiert werden, ansonsten bleibt es auf "nicht buchen"
 - *RKU*: Fehler Mehrwertsteuer (SJ)
	 - Es lag daran, dass in den Geschäftspartnern keine Steuernummer eingetragen war. Bei den 2 GP habe ich diese jetzt nachgetragen.
	 - Fehler in der REDISND1 war "Mehrwehrtsteuerkennzeichen in Prozess nicht gültig"
 - *RKU*: Q1D 105 SAV anlegen (DEW_SUP_20 & SBO_SUP_20)
	 - Habe ich angelegt. Ich musst noch die MeMi Vertragskonten erstellen.
- *DM*: Mieke Krijn, Text bei Bankbuchung
	- Da gab es schon mal einen Task, der von Walter umgesetzt wurde. Muss ich raussuchen
	- Ich habe Walter angeschrieben, ob er noch was weiß. Es war der Task [DSE-496](https://docmorrisgroup.atlassian.net/browse/DSE-496)
 - 17:00 *RKU* MGV Faktura (Sebastian Junkernheinrich)
	 - Faktura funktioniert jetzt, Kontenfindung wurde korrigiert
	 - Es gibt noch den Fehler mit Mabis, der auftritt, wenn das PDOc für den Einzelversand erstellt wird. Mohammed wird das debuggen (morgen)
 - *Kaffon*: Unterlagen NSSF einsortieren
	 - Unterlagen in Ordner eingeheftet

#### personal notes

 - Should I sync my notes with github? How secure is it?
	 - I did it. Ich muss das noch dokumentieren.

### 2023-10-31 tuesday


  - 10:00 *Kaffon*: Inspection NSSF (HQ)
	  - Diese Inspektion wird alle 6 Monate durchgeführt
	  - Sie wollte nur die Zertifikate und die Unterlagen von Mitarbeitern sehen
	  - Die Steuererklärung hat sie sich nicht angeschaut
  - 13:00 *RKU*: NG Lief+Netz Transformation ENRW - Sichtung des Altsystems (Rottweil)
	  - CATS für diese Termine: 2006242 / SR-2333505
	  - Unser Workshop am 13.11.2023 (Montag)
	  - Workshops
		  - Kein Fokus auf den Kunden, sondern auf die Dinge, die wir im System haben
	- Es fehlt eine übergreifende Abstimmung der Teilprojekte
		- Verzahnung der Geschäftsprozesse (Beispiel MOSB und Memi) sollte gezeigt werden (Streams)
	- Markus: EEG-Billing
	- System
		- 2 Mandanten auf einem System (LIEF und VNB)
	- Themen für uns
		- Convergent Invoicing
	- TODO: Dirk Friedrich fragen nach
	- Termin morgen mit Karl wegen Sperrprozess
 - Meeting Markus Berger/Mohamed
	 - Noch mal versucht, über Debugger den Mabis Fehler nachzustellen
	 - Es lag an den Berechtigungen des Systmusers. Das wurde dann behoben und die Belege laufen jetzt auch beim ersten mal durch.
- Meeting Dirk Friedrich Sperrprozess
	- Beispiele MALO für Sperrungen auf Q1D 105
		- 10126641290
		- 10126667147
	- Leventh Önder extern
	- Phillip Siegfranz intern (aber nett)
	- Sperrbeleg anlegen [RKU NG Sperrbeleg anlegen](NOTES/RKU%20NG%20Sperrbeleg%20anlegen.md) 
 - *Docmorris*: Fehler Retoure HSL
	 - [Klarna HSL: Buchung Zahlungsausgang aus Retoure Falsch (TVG 0019 fehlt - DDO-1152)](https://docmorrisgroup.atlassian.net/browse/DDO-1152)
	 - Das habe ich Peter zugewiesen. Er muss den Teilvorgang bei Retoure über die Tabelle "/CHCNL/FKK_TVORG" ermitteln. Zurzeit wird da irgendwa komkateniert und das passt nicht mehr mit den neuen Klarna Zahlwegen (0 und N) zusammen.
- *Docmorris*: Fehler Belegbuchung mit Partnergesellschaft
	- Ich habe das Kennzeichen "Gesellschaftsübergreifend" in der T003 für die Belegart D1 gesetzt (direkt auf der Datenbank)
		- Dadurch kann man bei der Buchung mit F-02 unter "weitere Daten" die Partnergesellschaft eingeben
	- Das muss noch in der HRD geändert werden und transportiert werden (morgen)
	- Die Validierung wurde durch [DDO-829 geändert](https://docmorrisgroup.atlassian.net/browse/DDO-829)

## 11-2023

### 2023-11-01 wednesday

Notes: All Saints Day

- 11:00 *RKU*: **Meeting**: Abstimmung ENWR - Vorbereitung Workshop
	- Abrechnung Sperrkosten mit Karl korrigieren
	- Wir haben es geschaftt, abrechenbare Positionen anzulegen (siehe [RKU NG Sperrbeleg anlegen](NOTES/RKU%20NG%20Sperrbeleg%20anlegen.md))
	- Es gibt noch Probleme mit der Faktura (Sparte und Serviceanbieter sind nicht gefüllt)
 - *RKU*: DMEE und Zahlungsträger dokumentieren
	 - Habe ich ins Konzeptdokument aufgenommen
- *Docmorris*: Korrektur Belegart D1
	- Ich habe das Kennzeichen bei den Belegarten D1 und D2 auf den Systemen HRD, HRQ und HR1 manuell in der Tabelle gesetzt, um Transporte zu vermeiden, da heute auch Feiertag in Deutschland ist (teilweise)
	- Contact Docmorris: Linh Nguyen
 - *RKU*: Mein S-User läuft im Dezember ab und ich habe das der Basis gemeldet

### 2023-11-02 thursday

- 10:05 *RKU* **Daily**: NextGen LIEF
	- habe ich abgesagt
- 11:45 *Docmorris* **Daily**: O2C-Team
	- Themen: Klarna Go-Live heute abend (technisch), Aktivierung am Freitag
	- Hier gab es ein Problem, dass Klarna zwischenzeitlich kurz aus Versehen live war und wir jetzt falsche Buchungen im System haben
- 12:30 *Docmorris* **Meeting**: Adyen und Amazon Abgleiche mit FI-CA
	- Tennyson, Walter
	- Klarna
		- Dadurch, dass Klarna kurz produktiv war, wurden Belege gebucht, aber mit dem falschen Teilvorgang und damit auf ein falsches Transferkonto (Die Tabelle /CHCNL/FKK_TVORG war auf der HR1 noch nicht für Klarna produktiv)
			- Walter hat den Fehler gefunden und wird ihn mit [Correction of /CHCNL/FKK_GET_TVORG](https://docmorrisgroup.atlassian.net/browse/DDO-1166) beheben
		- Belege müssen storniert und neu gebucht werden
			- Entweder LSMW oder die message neu verarbeiten (Rückmeldung Jörg abwarten)
			- Jörg: Messages neu starten: Report /CHCNL/CP_MSG_RECOVERY (siehe [Docmorris Transactions](NOTES/Docmorris%20Transactions.md))
	- Transaktionen von Tennyson -> [Docmorris Transactions](NOTES/Docmorris%20Transactions.md)
- *RKU*: Faktura Sperrkostenabrechnung. Wir müssen mit Deniz oder Birgit sprechen (siehe Termin 2023-11-01)
	- Karl hat einen Hinweis gefunden [3379243 - Billable items are created without division for GPKE Additional Service Billing](https://me.sap.com/notes/3379243/E)
	- Ling Ling hat ihn eingespielt, muss jetzt nochmal getestet werden
- 16:00 *RKU* **Meeting**: Analyse CHK_TRIG_DATA_FOR_DELVNOT / Lieferscheinversand Q1D 105
	- Mohamed muss das nochmal debuggen
	- Ich denke, es liegt an irgendwelchen Belegzeilenarten
- *Kaffon*: TRA Uploads und Buchungen
	- Rechnung Kamerun Waldemar prüfen
	- Gehalt Ibrahim Buchung
	- PAYE
	- Directors Fee
	- VAT
	- SDL
	- Bankgebühren

### 2023-11-03 friday

- *RKU*: Gespräch mit Ina
	- Workshops
		- Messstellenwesen: 06.11. - 07.11.2023
		- EDM: 08.11.2023
		- Druckmanagement: 09.11.2023
		- Geschäftsprozesse: 15.11.2023
		- Vertriebsprozesse: 17.11.2023
	- Thema Leon: "Geschäftsführerbeschluss" notwendig
		- 3 Tage + Option auf Erhöhung
		- DSGVO

### 2023-11-06 monday


 - *DM* **Meeting**: Docmorris zentrales Customizing (Jörg König)
	 - [Adapt Order characteristics - Bestellart/Bestellzusatz](https://docmorrisgroup.atlassian.net/browse/DDO-783)
	 - Zentrales Customizing der Bestellarten
	 - Tabelle : /chcnl/ord_chars
	 - Klasse: /CHCNL/CL_ORD_CHARACTERISTICS
	 - DDO-997 - Viewcluster für kompliziertes Customizing
- 12:30 *DM* **Meeting**: Report: Adyen und Amazon Abgleich mit FI-CA
	- Walter und Tennyson. Die Reports von Walter müssen schnellstmöglich fertig werden.
	- Walter war nicht da (Internetprobleme), Termin auf Dienstag verschoben

### 2023-11-07 tuesday

 - 12:30 *DM* **Meeting**: Report: Adyen und Amazon Abgleich mit FI-CA 
	 - Amazon Bericht Zahlungseingänge: /CHCNL/FKK_IN_AI
	 - Tennyson: Externe Berater als Anlagevermögen
 - 13:00 *RKU* **Meeting**: Workshop Vorbereitung FI-CA/MAKO ENRW
	 - Aufwände (Fehlerbehebung VNB) sollen auf Transformation gebucht werden
	 - Wir brauchen Testfälle für Netznutzung
	 - Karl: Abrechnen in die Zukunft (Termin)

### 2023-11-08 wednesday

 - 17:00 *RKU* **Meeting**: Lösung für den elektronischen Kontoauszug von Arvato Systems
	 - Von Avato: Mathias Krug
	 - Lösung relevant, wenn es viele Überweiser gibt
	 - Lösungsbeschreibung
		 - Basis: Kontoauszug ist im System eingespielt
		 - Es werden automatisiert Stapel über den Standard angelegt (Rückläufer, Zahlstapel etc.)
		 - Zahlungsstapelsplit? (VNB und gMSB)
		 - Umfangreiches Regelwerk
		 - Noch nicht im S4-Umfeld getestet
		 - Kontoauszüge können per RFC gelesen werden
		 - Auswertungen möglich. Kontrollinstrument für Management. Ausgabe von offenen oder nicht zugeordneten Fällen.
 - *RKU*: Abstimmung mit Karl
	 - Seine Kollegin war dabei: Pauline Niewiadomski (?)
- *Docmorris*: Tasks im Sprint beginnen
	- [DDO-1097](https://docmorrisgroup.atlassian.net/browse/DDO-1097) - 5 sp
		- Donnerstag: Abstimmung mit Walter. Ich brauche hier Unterstützung
	- [DDO-688](https://docmorrisgroup.atlassian.net/browse/DDO-688) - 5 sp
		- Ordnungsbegriff einführen
		- Hier mussten über das Customizing noch CI-Includes und Tabellenindizes angelegt werden
		- [Ordnungsbegrif FI-CA](NOTES/Ordnungsbegrif%20FI-CA.md)
		- Mein Test war erfolgreich. Originalauftrag und Retoure haben jetzt die gleiche Auftragsnummer im Ordnungsbegriff
		- FPMA muss noch getestet werden

### 2023-11-09 thursday

 - 10:00 *RKU* Daily NG Lief
	 - Wir brauchen noch eine klare Vorgehensweise für die Buckets
	 - Ina stimmt mit PL ab, wie es mit der Arvato Kontoauszugslösung weitergeht
		 - Sie hat angedeutet, dass die Kunden wahrscheinlich wieder mit Seralla/Hanseorga gehen werden, weil es im Core wahrscheinlich zum Einsatz kommen wird.
 - 11:00 *RKU*: NextGen LIEF: Zuarbeiten aus Stream Abrechnung und FI-CA
	 - Es geht um die Zuarbeiten, die unser Stream leisten muss für den Vertriebsstream
	 - Datei liegt unter Allgemein --> 06_Übergreifende Arbeitsdokumente -> Zuarbeiten_Stream_übergreifend
	 - Vorbelegung für den Vorerfassungsbeleg
		 - KDB: Abstimmung der Tarife erforderlich -> Es müssen eigentlich noch alle geschult werden, wie die Tariflogik zukünftig aussehen wird
	- Termin wird nächstes mal fortgeführt
	- Ergebnis des Termins: Wir wollen erstmal mit Vorlage Vertragskonto arbeiten (René) --> Kerstin: Vorlage VEB
		- Wenn das Produktkonzept steht (René), können wir die Vorgaben an Carla geben
 - 12:00 *RKU*: ENWR - GRDB-Fakturafehler - Klassen abrechenbarer Positionen - Erweiterung (Karl Johann)
	 - Es lag an den Schnittstellenkomponenten. Allerdings funktioniert es immer noch nicht. Wir schauen morgen nochmal mit Deniz
 - 13:30 *DM* - DDO-1097 Analyse mit Walter
	 - Ich habe ein Beispiel für morgen organisiert und wir schauen uns das morgen nochmal gemeinsam an.
- *Kaffon*: Termin mit Richard vereinbaren
	- Irgendwann im November (2h in seinem Büro)
	- Ich habe Richard eine E-Mail geschrieben mit der Bitte um einen Termin diesen Monat.

### 2023-11-10 friday

Priorität hat die Workshop Vorbereitung für Montag. Ich muss nochmal mit Karl das morgen abstimmen.

 - *RKU*: Netznutzungsrechnungen auf Q1D Mandant 105 testen für den Workshop
	 - Fiori Transaktionen prüfen (Abrechnung etc.)
	 - Folien anpassen? Wo sind diese Folien?
	 - Folien sind in Ordnung, irgendwer hat die auch aufgehübscht.
	 - Ich habe einen Fall von Sebastian getestet und hier lief alles einwandfrei
 - *DM*: IBAN Kontoauszug mit Walter prüfen (DDO-1097)
	 - Das konnten wir heute erfolgreich umsetzen und auch schon testen
 - *DM*: Ticket Tennyson Kontoauszug
	 - Komischer Fall, wahrscheinlich ist die Buchungsregel für den GVC 116 nicht passend.
 - *Kaffon*: Alle Stunden gebucht

### 2023-11-13 monday

 - Workshop Rottweil ganztägig (WICHTIG)
 - *DM*: [DDO-169 - Automatische Buchungen Gehalt - SAP](https://docmorrisgroup.atlassian.net/browse/DDO-169)
 - *DM* - Mieke Krijn: Text bei Bankbuchung
 - *DM* - Ticket Kontoauszug von Michell (Sebastian)

