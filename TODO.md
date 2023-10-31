# Links

[plain_text_notes](NOTES/plain_text_notes.md)

# 2023-10-23 monday

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

#  2023-10-24 tuesday

- *DM*: Confluence Seite für Suchmusterprobleme erstellen
	- [Confluence Suchmuster](https://docmorrisgroup.atlassian.net/wiki/spaces/CIT/pages/3037135146/Optimierung+Suchmuster)
- *DM*: [DDO-696](https://docmorrisgroup.atlassian.net/browse/DDO-696)
	- Walter hat die Funktionsgruppe in meinen Change überführt (Change 4000002580, Transport HRDK941761)
- *all*: Abwesenheit 31.10.2023 eintragen
	- Mail an RKU und DM geschickt.

# 2023-10-25 wednesday

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

# 2023-10-26 thursday

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

# 2023-10-27 friday

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

# 2023-10-30 monday

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

## personal notes

 - Should I sync my notes with github? How secure is it?
	 - I did it. Ich muss das noch dokumentieren.

# 2023-10-31 tuesday


  - 10:00 *Kaffon*: Inspection NSSF (HQ)
	  - Diese Inspektion wird alle 6 Monate durchgeführt
	  - Sie wollte nur die Zertifikate und die Unterlagen von Mitarbeitern sehen
	  - Die Steuererklärung hat sie sich nicht angeschaut
  - 13:00 *RKU*: NG Lief+Netz Transformation ENRW - Sichtung des Altsystems (Rottweil)
	  - Workshops
		  - Kein Fokus auf den Kunden, sondern auf die Dinge, die wir im System haben
	- Es fehlt eine übergreifende Abstimmung der Teilprojekte
		- Verzahnung der Geschäftsprozesse (Beispiel MOSB und Memi) sollte gezeigt werden (Streams)
	- Markus: EEG-Billing

---

 - *RKU*: DMEE und Zahlungsträger dokumentieren
 - *Kaffon*: Boardmeetings: Liste erstellen
	 - Wann muss das erste Jährliche Boardmeeting stattfinden?
