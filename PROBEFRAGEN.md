# Software Engineering 2 – Probefragen (Multiple Choice)

> Format: ankreuzbare Antworten. Es können **eine oder mehrere** Antworten richtig sein (typisch für MC-Klausuren). Jede Frage hat eine **Lösung** + **Kurzerklärung**. Decke die Lösungen ab, wenn du die Fragen üben willst!

---

## A) Einführung & Softwareentwicklungsprozesse

### Frage 1
Welche Aussagen über Software treffen zu?
- A) Software hat physikalische Substanz.
- B) Software ist unsichtbar und hat kein Aussehen.
- C) Software lebt oft länger als geplant.
- D) Software kann großen Schaden verursachen.

**Lösung**: B, C, D. *Software ist nicht-physikalisch, lebt aber länger und kann großen Schaden anrichten (Therac-25, Ariane 5).*

---

### Frage 2
Welche 4 Merkmale guter Software wurden in der VO genannt?
- A) Wartbarkeit, Sicherheit/Zuverlässigkeit, Effizienz, Benutzerfreundlichkeit
- B) Performance, Lesbarkeit, Komplexität, Kosten
- C) Wartbarkeit, Skalierbarkeit, Komplexität, Lesbarkeit
- D) Funktionalität, Effizienz, Wartung, Skalierbarkeit

**Lösung**: A. *Sommerville: maintainable, dependable, efficient, usable.*

---

### Frage 3
Welche Aussage zum Wasserfall-Modell stimmt?
- A) Benutzer sind in jeder Phase aktiv eingebunden.
- B) Kurskorrekturen sind frühzeitig leicht möglich.
- C) Die Reihenfolge der Aktivitäten ist fest, Rückkopplung ist eingeschränkt.
- D) Risiken werden permanent neu bewertet.

**Lösung**: C. *Wasserfall: Top-Down, festgelegte Reihenfolge, eingeschränkte Rückkopplung, Benutzer nur zu Beginn.*

---

### Frage 4
Das V-Modell …
- A) integriert Qualitätssicherung systematisch.
- B) ist für sehr kleine Projekte besonders geeignet.
- C) verbindet jede Entwicklungsphase mit einer Test-/Validierungsphase.
- D) lehnt Dokumentation grundsätzlich ab.

**Lösung**: A, C. *V-Modell: integrierte QS, Verifikation/Validation. Klein: zu viel Bürokratie. Doku zentral.*

---

### Frage 5
Welche der folgenden Prozessmodelle gehören zu den **iterativen** Modellen?
- A) Wasserfallmodell
- B) Spiralmodell
- C) V-Modell
- D) Rational Unified Process (RUP)

**Lösung**: B, D. *Wasserfall und V-Modell sind sequenziell.*

---

### Frage 6
Welche 4 Werte umfasst das Agile Manifest?
- A) Individuen & Interaktionen über Prozesse & Tools
- B) Funktionierende Software über umfassende Dokumentation
- C) Zusammenarbeit mit dem Kunden über Vertragsverhandlung
- D) Festen Plan über Reaktion auf Änderung

**Lösung**: A, B, C. *D ist umgekehrt: „Responding to change over following a plan."*

---

### Frage 7
Welches **Prozessmodell** ist das beste?
- A) Wasserfall – immer.
- B) Scrum – immer.
- C) Es gibt kein ideales Modell; abhängig von Organisation/Produkt/Entwickler.
- D) Spiralmodell – immer.

**Lösung**: C. *Auf Folie sehr explizit so genannt.*

---

## B) Scrum

### Frage 8
Welche Aussagen zu Scrum-Rollen stimmen?
- A) Der Product Owner ist verantwortlich für den ROI.
- B) Der Scrum Master weist dem Team Tasks zu.
- C) Das Team ist selbstorganisierend.
- D) Der Scrum Master schützt das Team vor äußeren Störungen.

**Lösung**: A, C, D. *Tasks weist sich das Team selbst zu, Scrum Master entfernt Hindernisse.*

---

### Frage 9
Wie viele Mitglieder sollte ein Scrum-Team typischerweise haben?
- A) 1–3
- B) 5–10
- C) 15–20
- D) > 25

**Lösung**: B. *5–10 Vollzeit-Mitglieder.*

---

### Frage 10
Was bedeutet **INVEST** für User Stories?
- A) Independent, Negotiable, Valuable, Estimateable, Small, Testable
- B) Important, Negotiable, Verified, Effective, Strict, Tested
- C) Independent, Necessary, Valuable, Easy, Small, Testable
- D) Integrated, Negotiable, Valuable, Estimateable, Scalable, Testable

**Lösung**: A.

---

### Frage 11
Wer priorisiert das **Product Backlog**?
- A) Das Entwicklungsteam
- B) Der Scrum Master
- C) Der Product Owner
- D) Das Management

**Lösung**: C. *Product Owner repräsentiert den Kunden und priorisiert.*

---

### Frage 12
Welche Aussagen zum **Daily Scrum** stimmen?
- A) Dauert 15 Minuten und findet täglich statt.
- B) Wird im Stand-up abgehalten.
- C) Dient der Problemlösung.
- D) Nur das Team („Schweine") spricht; andere („Hühner") nehmen nur teil.

**Lösung**: A, B, D. *Problemlösung erfolgt danach, nicht im Daily.*

---

### Frage 13
Ein User Story mit **20 Story Points** sollte …
- A) sofort umgesetzt werden.
- B) als **Epic** behandelt und vor Implementierung **geteilt** werden.
- C) ohne Schätzung sofort in den Sprint kommen.
- D) verworfen werden.

**Lösung**: B. *Stories > 13 Story Points = Epic, müssen geteilt werden.*

---

### Frage 14
Was ist Velocity?
- A) Die Anzahl an Bugs pro Sprint.
- B) Die Anzahl an Story Points, die ein Team pro Sprint umsetzt.
- C) Die Geschwindigkeit der Code-Compilation.
- D) Eine Risiko-Metrik.

**Lösung**: B.

---

### Frage 15
Welche Aussage zum **Sprint Review** stimmt?
- A) Nur das Scrum-Team nimmt teil.
- B) Es ist eine formelle Code-Inspektion.
- C) Es ist informell ("2-Stunden-Vorbereitung"-Regel) und Kunden/Management nehmen teil.
- D) Es dient als Performance-Review der Teammitglieder.

**Lösung**: C.

---

### Frage 16
In der **Sprint Retrospektive** …
- A) … ist das gesamte Management dabei.
- B) … wird das Team bewertet.
- C) … nimmt nur das Scrum-Team teil und reflektiert (start/continue/stop).
- D) … wird die Velocity neu kalkuliert.

**Lösung**: C. *Retrospektive ist Team-intern, keinesfalls Leistungs-Review.*

---

### Frage 17
Welche Aussage zu Scrum stimmt?
- A) Anforderungen sind im Pflichtenheft festgehalten.
- B) Manager entscheiden für das Team.
- C) Anforderungen sind im Product Backlog festgehalten.
- D) Sprints haben typischerweise eine Dauer von ca. einem Monat (+/− 1–2 Wochen).

**Lösung**: C, D.

---

### Frage 18
Was passiert in Scrum mit Produktions-Notfällen?
- A) Sie werden ignoriert bis zum Sprintende.
- B) Bei sofortiger Notwendigkeit → **Sprintende** und Reparatur.
- C) Sie werden immer im laufenden Sprint behoben.
- D) Sie kommen sofort in den nächsten Sprint.

**Lösung**: B. *Wenn Produktion steht: Sprintende.*

---

### Frage 19
Welches Schätzverfahren wird im agilen Schätzen verwendet?
- A) COCOMO
- B) Function Points
- C) Planning Poker mit Story Points
- D) Application Points

**Lösung**: C.

---

## C) Anforderungen

### Frage 20
Was sind die 5 Aufgaben des **Requirements Engineering**?
- A) Implementieren, Testen, Dokumentieren, Verwalten, Wartung
- B) Ermitteln, Dokumentieren, Prüfen, Abstimmen, Verwalten
- C) Erheben, Designen, Entwickeln, Validieren, Auslieferung
- D) Sammeln, Bewerten, Dokumentieren, Implementieren, Testen

**Lösung**: B. *Wird in jeder VO-Einheit wiederholt!*

---

### Frage 21
Ordne zu: „Das Suchergebnis soll nach spätestens 5 Sekunden angezeigt werden."
- A) Funktionale Anforderung
- B) Nicht-funktionale Anforderung
- C) Benutzeranforderung
- D) Use Case

**Lösung**: B. *Beschreibt **wie gut** (Performance).*

---

### Frage 22
„Als Admin möchte ich User löschen können." ist …
- A) eine funktionale Anforderung.
- B) eine nicht-funktionale Anforderung.
- C) ein Akzeptanzkriterium.
- D) ein NFA-Performance-Requirement.

**Lösung**: A. *Klar funktional, beschreibt **was**.*

---

### Frage 23
Welche der folgenden Aussagen zu Lastenheft / Pflichtenheft stimmen?
- A) Das Lastenheft wird vom **Auftraggeber** erstellt.
- B) Das Pflichtenheft beschreibt das **WAS und WARUM**.
- C) Das Pflichtenheft beschreibt die konkrete Realisierung.
- D) Lastenheft in natürlicher Sprache, Pflichtenheft in technischer Sprache.

**Lösung**: A, C, D. *Pflichtenheft = WIE; Lastenheft = WAS/WARUM.*

---

### Frage 24
Welche Qualitätskriterien gehören zu IEEE/ISO 29148-2011?
- A) Vollständig, atomar, eindeutig, prüfbar
- B) Schnell, sauber, einfach, billig
- C) Lösungsneutral, notwendig, verfolgbar, konsistent
- D) Realisierbar, eindeutig

**Lösung**: A, C, D.

---

### Frage 25
„Die Informationsanzeige im Zug muss benutzerfreundlich sein." Welcher Fehler liegt vor?
- A) Widerspruch
- B) Mehrdeutigkeit
- C) Unmessbarkeit
- D) Überspezifikation

**Lösung**: C. *„Benutzerfreundlich" ist nicht messbar.*

---

### Frage 26
„Die Zugtüren müssen zwischen Stationen immer geschlossen bleiben. Sie müssen offen sein wenn es einen Nothalt gab." Welcher Fehler?
- A) Widerspruch
- B) Mehrdeutigkeit
- C) Unmessbar
- D) Noise

**Lösung**: A. *Widerspruch zwischen den zwei Sätzen.*

---

### Frage 27
Welche Wissensebene wird mit **Beobachtungstechniken** ermittelt?
- A) Bewusstes Wissen
- B) Unbewusstes Wissen
- C) Unterbewusstes Wissen (Basisfaktoren)
- D) Allgemeines Wissen

**Lösung**: C. *Beobachtung erfasst Basis-Faktoren (unterbewusst); Befragung = bewusst; Kreativität = unbewusst.*

---

### Frage 28
Welche Technik gehört zu **Kreativitätstechniken**?
- A) Interview
- B) Feldbeobachtung
- C) 6-Hut-Denken (Wechsel der Perspektive)
- D) Fragebogen

**Lösung**: C.

---

### Frage 29
Bei der **Methode 6-3-5** …
- A) … beteiligen sich 6 Teilnehmer.
- B) … schreibt jeder 3 Ideen auf.
- C) … wird das Blatt 5 mal weitergegeben.
- D) … gibt es **keinen** Moderator.

**Lösung**: A, B, C. *Methode 6-3-5 ist namensgebend für 6 Teilnehmer × 3 Ideen × 5 Weitergaben.*

---

### Frage 30
Welche Aussage zu **Apprenticing** stimmt?
- A) Es ist eine Befragungstechnik.
- B) "In die Lehre gehen" – Erleben des Ist-Systems.
- C) Eignet sich besonders gut in kritischen Umfeldern (z. B. Flugsicherung).
- D) Ist nicht zeitintensiv.

**Lösung**: B. *Apprenticing ist Beobachtung, sehr zeitintensiv, nicht für kritische Umfelder.*

---

### Frage 31
Welche der folgenden Inhalte sind **typisch für ein Lastenheft**?
- A) Ist-Zustand
- B) Soll-Zustand
- C) Detaillierte Systemarchitektur
- D) FA und NFA

**Lösung**: A, B, D. *Detaillierte Architektur gehört ins Pflichtenheft.*

---

### Frage 32
Welche **3 Arten von Reviews** unterscheiden sich?
- A) Stellungnahme, Walkthrough, Inspektion
- B) Audit, Test, Inspektion
- C) Code-Review, Test, Audit
- D) Stellungnahme, Test, Validation

**Lösung**: A.

---

### Frage 33
Wie viele Phasen hat eine **Inspektion**?
- A) 3
- B) 4
- C) 6
- D) 8

**Lösung**: C. *Planung, Vorbesprechung, individuelle Vorbereitung, Reviewsitzung, Nachbereitung/Bewertung, Ende.*

---

### Frage 34
Was beschreibt eine **User Story** in Scrum?
- A) Eine technische Spezifikation in Pseudocode.
- B) „Als <Rolle> will ich <tun>, so dass ich <Grund>."
- C) Den Aufbau der Architektur.
- D) Eine Datenbankspezifikation.

**Lösung**: B.

---

### Frage 35
Welche Aussagen zur **Definition of Done (DoD)** stimmen?
- A) Sie ist projekt-/teamspezifisch.
- B) Sie beschreibt, wann etwas „fertig" ist.
- C) Sie soll messbar sein.
- D) Bei Missachtung ist der Product Owner zuständig.

**Lösung**: A, B, C. *Bei DoD-Verletzungen ist der **Scrum Master** zuständig.*

---

## D) Software Design

### Frage 36
Welche der folgenden Schichten gehören zur typischen Schichtenarchitektur?
- A) Presentation Layer
- B) Business Layer
- C) Technical Layer
- D) Test Layer

**Lösung**: A, B, C. *(Plus optional Application Layer.) Test Layer gehört nicht dazu.*

---

### Frage 37
Welche **Nachteile** hat die Schichtenarchitektur?
- A) Bessere Kapselung
- B) Performance: Anfragen werden durch alle Schichten weitergereicht
- C) Änderungen in allen Schichten nötig
- D) Schlechte Skalierbarkeit

**Lösung**: B, C, D. *A ist ein Vorteil, kein Nachteil.*

---

### Frage 38
Welche Komponente im **MVC**-Pattern …
- A) … enthält die Daten und Status? → **Model**
- B) … zeigt die Daten an und leitet User-Eingaben weiter? → **View**
- C) … interpretiert User-Eingaben und triggert Updates? → **Controller**
- D) … ist verantwortlich für Datenbankzugriff? → **Controller**

**Lösung**: A, B, C. *D ist falsch (das ist eher Aufgabe des Model bzw. eines Repository).*

---

### Frage 39
Worin unterscheiden sich **MVC** und **MVP**?
- A) MVP nutzt einen Controller, MVC einen Presenter.
- B) In MVP ist die View passiv und kommuniziert über den Presenter mit dem Model.
- C) MVP wird in der Business Layer eingesetzt, MVC im UI.
- D) MVP bietet **bessere Testbarkeit** als MVC.

**Lösung**: B, D.

---

### Frage 40
Welche Eigenschaften charakterisieren eine **Software-Komponente**?
- A) Klare und stabile Schnittstelle
- B) Auf Wiederverwendbarkeit ausgelegt
- C) Streng plattformabhängig
- D) Locker verbunden

**Lösung**: A, B, D. *Komponenten sind oft auf Plattform/Framework beschränkt, aber Service ist plattformunabhängig.*

---

### Frage 41
**Dependency Injection** ist ein Pattern, das …
- A) … die Auflösung von Abhängigkeiten an das Framework delegiert (Inversion of Control).
- B) … nur über XML-Konfiguration funktioniert.
- C) … die Testbarkeit erhöht (auch Mocking).
- D) … die direkte Bindung zwischen Komponenten verstärkt.

**Lösung**: A, C. *DI funktioniert auch über Annotations/Autowiring, reduziert direkte Bindung.*

---

### Frage 42
Welche der folgenden gehören zur **Aspektorientierten Programmierung (AOP)**?
- A) Aspekt – Klasse mit Querschnittsfunktionalität
- B) Advice – Implementierung des Aspekts (Before, After, Around)
- C) Join Point – Punkt, an dem Aspekte eingeführt werden können
- D) Pointcut – Gruppe von Join Points

**Lösung**: A, B, C, D. *Alle gehören zu AOP-Begriffen.*

---

### Frage 43
Typische **Cross-Cutting Concerns**, die mit AOP behandelt werden, sind:
- A) Logging
- B) Geschäftslogik
- C) Security
- D) Transaktionssteuerung

**Lösung**: A, C, D. *B ist nicht querschnittlich.*

---

### Frage 44
Wofür steht **SOA**?
- A) Service-Oriented Architecture
- B) System Oriented Approach
- C) Service Of Applications
- D) Standard Object Authentication

**Lösung**: A.

---

### Frage 45
Welche HTTP-Methode entspricht „Daten erstellen" in REST?
- A) GET
- B) POST
- C) PUT
- D) DELETE

**Lösung**: B. *POST = erstellen, PUT = update/ersetzen.*

---

### Frage 46
Welche der folgenden ist **kein** Bestandteil einer SOAP-Nachricht?
- A) Envelope
- B) Header
- C) Body
- D) Routing

**Lösung**: D. *Routing ist kein SOAP-Element. Optional auch: Fault.*

---

### Frage 47
**WSDL** wird verwendet, um …
- A) Web-Services zu beschreiben (types, message, portType, binding).
- B) Daten in JSON zu übertragen.
- C) RESTful Services zu definieren.
- D) Datenbanken zu konfigurieren.

**Lösung**: A.

---

### Frage 48
Welche Aussagen zu **Microservices** stimmen?
- A) Lose gekoppelt
- B) Leicht wartbar
- C) Unabhängig voneinander zusammensetzbar
- D) Bilden einen großen Monolithen

**Lösung**: A, B, C.

---

### Frage 49
Vorteile von **REST** gegenüber XML-basierten Web Services:
- A) Einfacher zu verwenden
- B) JSON, CSV, XML als Formate möglich
- C) Standardisierte Beschreibungssprache (WSDL)
- D) Verzeichnis (UDDI) verfügbar

**Lösung**: A, B. *C und D sind Vorteile von **XML-basiert**, nicht REST.*

---

## E) Qualitätssicherung

### Frage 50
Welche Methoden zählen zur **analytischen QS**?
- A) Schulungen
- B) Software Testen
- C) Reviews
- D) Metriken

**Lösung**: B, C, D. *Schulungen = konstruktive (menschliche) QS.*

---

### Frage 51
**Verifikation** beantwortet die Frage …
- A) „Bauen wir das richtige Produkt?"
- B) „Bauen wir das Produkt richtig?"
- C) „Wann ist das Produkt fertig?"
- D) „Wie viel kostet das Produkt?"

**Lösung**: B. *Validation = „richtiges Produkt?"; Verifikation = „richtig bauen?"*

---

### Frage 52
Ordne die Begriffe zu (IEEE 610.12):
- A) Software Error = inkorrekter Programmschritt
- B) Software Fault = menschliche Aktion
- C) Software Failure = Unfähigkeit des Systems, geforderte Funktion zu erfüllen
- D) Software Error = menschliche Aktion mit inkorrektem Resultat

**Lösung**: C, D. *Error = menschliche Aktion; Fault = inkorrekter Schritt im Code; Failure = Fehlverhalten.*

---

### Frage 53
**Dijkstra**: „Testing can show the presence of bugs, but not their absence." Was bedeutet das?
- A) Tests beweisen die Korrektheit eines Programms.
- B) Tests können nur Bugs **finden**, nicht das Fehlen von Bugs garantieren.
- C) Tests sind nutzlos.
- D) Tests sind nur statisch sinnvoll.

**Lösung**: B.

---

### Frage 54
Welche Testüberdeckungen wurden in der VO genannt?
- A) Statement
- B) Branch
- C) Path
- D) Mehrfache Bedingungsüberdeckung

**Lösung**: A, B, C, D. *Alle wurden genannt + einfache Bedingungsüberdeckung.*

---

### Frage 55
Der **GQM-Ansatz** für Metriken besteht aus:
- A) Goals → Questions → Metrics
- B) General → Quality → Measurement
- C) Goals → Quality → Maintenance
- D) Generic → Quantitative → Method

**Lösung**: A.

---

### Frage 56
Welche Qualitätsfaktoren der ISO/IEC 25010:2011 sind **neu** gegenüber ISO 9126:1990?
- A) Compatibility
- B) Security
- C) Functionality
- D) Maintainability

**Lösung**: A, B. *Compatibility und Security wurden eigenständig in 25010.*

---

### Frage 57
**CMMI-DEV** hat wie viele Reifegradstufen?
- A) 3
- B) 4
- C) 5
- D) 6

**Lösung**: C. *Initial, Repeatable, Defined, Managed, Optimizing.*

---

### Frage 58
Welche CMMI-Stufe beschreibt „durch Messen gesteuert, vorhersagbar hohe Qualität"?
- A) Stufe 2 – Repeatable
- B) Stufe 3 – Defined
- C) Stufe 4 – Managed
- D) Stufe 5 – Optimizing

**Lösung**: C. *Stufe 4 = Managed.*

---

### Frage 59
**ISO 9000** ist eine Standard-Familie für …
- A) Qualitätsmanagementsysteme
- B) Projektmanagement
- C) Software-Architektur
- D) Coding-Standards

**Lösung**: A.

---

### Frage 60
**Konstruktive QS** umfasst:
- A) Technische Maßnahmen (Methoden, Sprachen, Werkzeuge)
- B) Organisatorische Maßnahmen (SE-Prozessmodelle)
- C) Menschliche Maßnahmen (Schulungen)
- D) Reviews und Tests

**Lösung**: A, B, C. *Reviews und Tests sind analytisch.*

---

## F) Projektmanagement

### Frage 61
Was beschreibt das „magische Dreieck"?
- A) Code – Test – Doku
- B) Zeit – Kosten – Qualität (mit Funktionalität)
- C) People – Process – Product
- D) Anforderungen – Design – Implementierung

**Lösung**: B.

---

### Frage 62
Welche Aussage zur **Reinen Projektorganisation** stimmt?
- A) MA werden für Projekte „abgezogen".
- B) Ineffiziente Nutzung von Experten zwischen Projekten.
- C) Schnelle Reaktionszeiten und Ansprechpartner für Kunden.
- D) Sehr stabiles berufliches Weiterkommen.

**Lösung**: A, B, C. *D ist Nachteil: unsicheres Weiterkommen.*

---

### Frage 63
Welche Phase gehört zu den **4 Projektphasen**?
- A) Projektdefinition
- B) Projektplanung
- C) Projektverfolgung
- D) Projektabschluss

**Lösung**: A, B, C, D. *Alle 4 Phasen sind richtig.*

---

### Frage 64
Was sagt der **Schätztrichter** nach Boehm?
- A) Aufwand wächst exponentiell.
- B) Schätzungen werden umso **genauer**, je näher man dem Projektende ist.
- C) Schätzungen werden mit der Zeit ungenauer.
- D) Schätzungen sind in der Mitte am genauesten.

**Lösung**: B.

---

### Frage 65
Welche der folgenden gehören zu **empirischen Schätzverfahren**?
- A) Expertenschätzung
- B) Delphi-Methode
- C) COCOMO
- D) Analogieschätzung

**Lösung**: A, B, D. *COCOMO = algorithmisch.*

---

### Frage 66
Bei der **Delphi-Methode** …
- A) … schätzt jeder Experte **anonym**.
- B) … gibt es nur eine Runde.
- C) … gibt es einen Koordinator, der die Schätzungen sammelt und anonymisiert.
- D) … konvergiert die Schätzung über mehrere Runden.

**Lösung**: A, C, D. *Mehrere Runden, daher B falsch.*

---

### Frage 67
Welche Function-Point-Kategorien gibt es?
- A) EI (External Input), EO (External Output)
- B) EQ (External Inquiry), ILF (Internal Logical File)
- C) EIF (External Interface File)
- D) NFR (Non-Functional Requirement)

**Lösung**: A, B, C. *D ist keine FP-Kategorie.*

---

### Frage 68
Welche der folgenden COCOMO-Projektarten gibt es?
- A) Organic
- B) Semidetached
- C) Embedded
- D) Distributed

**Lösung**: A, B, C. *D ist keine COCOMO-Projektart.*

---

### Frage 69
Wofür steht **KDSI** in COCOMO 81?
- A) Kilo Delivered Source Instructions
- B) Knowledge Driven Software Implementation
- C) Key Development Schedule Index
- D) Key Decision Support Instructions

**Lösung**: A.

---

### Frage 70
Welche „sonstigen" Schätzverfahren gibt es?
- A) Koste-es-was-es-wolle-Schätzung
- B) Schmerzschwellen-Schätzung
- C) Parkinsonsches Gesetz: Aufwand passt sich an Kapazität an
- D) Bottom-Up-Methode

**Lösung**: A, B, C. *Bottom-Up gehört zu empirisch.*

---

### Frage 71
Welche Aussage zum **WBS** (Work-Breakdown Structure) stimmt?
- A) Es ist eine hierarchische Struktur (Baum).
- B) Es gibt 2 Typen: objektorientiert und ablauforientiert.
- C) Testen gehört nicht dazu.
- D) Es ist die Grundlage für die Kostenschätzung.

**Lösung**: A, B, D. *Testen ist auch „Teilprojekt".*

---

### Frage 72
Im **PERT-Diagramm** bedeutet **FE** = ...
- A) „Festgelegtes Ende"
- B) „Frühstes Ende" = FA + Dauer
- C) „Finales Ergebnis"
- D) „Frühestes Ereignis"

**Lösung**: B.

---

### Frage 73
Welche der folgenden Aussagen über **Personalmanagement** stimmen?
- A) "Adding manpower to a late software project makes it later" (Fred Brooks).
- B) Mann-Monate sind eine perfekte Maßeinheit.
- C) Einarbeitungszeit muss beachtet werden.
- D) Personal sollte früh aufgestockt werden, nicht erst gegen Ende.

**Lösung**: A, C, D. *Mann-Monate sind laut Brooks ein Mythos!*

---

### Frage 74
Welche **3 Arten von Risiken** wurden in der VO genannt?
- A) Projektrisiken (Zeit/Budget)
- B) Produktrisiken (Qualität/Leistung)
- C) Wirtschaftliche Risiken (Unternehmen)
- D) Personalrisiken (Krankheit)

**Lösung**: A, B, C.

---

### Frage 75
Welche **Risikoplanungs-Strategien** gibt es?
- A) Vermeidung
- B) Minimierung
- C) Notfallplan
- D) Ignorieren

**Lösung**: A, B, C.

---

## G) Konfigurationsmanagement

### Frage 76
Welche Aktivitäten/Themen gehören zum **Konfigurationsmanagement**?
- A) Änderungsmanagement
- B) Versionsmanagement
- C) Automatisierung (Build, CI/CD, DevOps)
- D) Anforderungserhebung

**Lösung**: A, B, C. *Anforderungserhebung gehört zu RE.*

---

### Frage 77
Welche Aussage zu **Git** stimmt?
- A) Git ist ein **dezentrales** Versionskontrollsystem.
- B) Jeder Entwickler hat ein eigenes Repository.
- C) Revisionen werden mit **SHA-1 Hash** identifiziert.
- D) Git ist nur lokal nutzbar.

**Lösung**: A, B, C.

---

### Frage 78
Welche Git-Aktionen ermöglichen die Arbeit mit einem Remote-Server?
- A) clone (Repository herunterladen)
- B) push (Änderungen hochladen)
- C) pull (Änderungen vom Server holen + integrieren)
- D) commit (Änderungen lokal speichern)

**Lösung**: A, B, C. *Commit ist lokal.*

---

### Frage 79
Eine gute **Commit Message** sollte …
- A) … Zusammenfassung und Details trennen.
- B) … die Zusammenfassung auf 50 Zeichen begrenzen.
- C) … Referenzen (z. B. Issue-Tracker) angeben.
- D) … einen kompletten Roman in einem Satz schreiben.

**Lösung**: A, B, C.

---

### Frage 80
**Tangled Commits** sind …
- A) … ein Best Practice.
- B) … Commits mit Änderungen mehrerer Tasks – sollten vermieden werden.
- C) … Commits mit einer einzigen, klar abgegrenzten Änderung.
- D) … leicht retrospektiv analysierbar.

**Lösung**: B. *„Verknäulte" Commits sind schlecht.*

---

### Frage 81
Welche Merging-Strategien wurden genannt?
- A) Lock-Modify-Unlock
- B) Copy-Modify-Merge
- C) Feature Branches
- D) Delete-Replace

**Lösung**: A, B, C.

---

### Frage 82
**Semantic Versioning** verwendet das Muster MAJOR.MINOR.PATCH. Was bedeuten die Teile?
- A) MAJOR = inkompatible API-Änderungen
- B) MINOR = abwärtskompatible neue Funktionalität
- C) PATCH = abwärtskompatible Bug Fixes
- D) MINOR = inkompatible API-Änderungen

**Lösung**: A, B, C.

---

### Frage 83
Welche Aussage zur **Software Automation Pipeline** ist richtig?
- A) Continuous Integration: automatisches Bauen, Testen, Integrieren.
- B) Continuous Delivery: Release ist bereit für Produktivumgebung; Deployment manuell.
- C) Continuous Deployment: Jede getestete Änderung wird automatisch in Produktion ausgebracht.
- D) DevOps: Erweiterung um Operations-Seite (Backups, Monitoring, Scaling).

**Lösung**: A, B, C, D. *Alle vier stimmen!*

---

### Frage 84
Was unterscheidet **Continuous Delivery** von **Continuous Deployment**?
- A) Bei Delivery wird der finale Deployment-Schritt **manuell** ausgelöst.
- B) Bei Deployment wird **automatisch** in Produktion ausgebracht.
- C) Delivery hat keine Tests.
- D) Beide bedeuten dasselbe.

**Lösung**: A, B.

---

### Frage 85
Welche DevOps Practices wurden genannt?
- A) Versionskontrolle für alle Bereiche (auch Konfigurationsdateien)
- B) Proaktives Monitoring
- C) Virtualisierung/Container (Docker, Kubernetes)
- D) Reine Wasserfall-Entwicklung

**Lösung**: A, B, C.

---

### Frage 86
„Wall of Confusion" beschreibt …
- A) … das Spannungsfeld zwischen Development (will Änderung) und Operations (will Stabilität).
- B) … technische Schwierigkeiten beim Build.
- C) … gesetzliche Compliance-Probleme.
- D) … wird durch DevOps adressiert.

**Lösung**: A, D.

---

### Frage 87
**POM** im Maven-Kontext bedeutet …
- A) Project Object Model
- B) Plain Old Maven
- C) Process Optimization Model
- D) Production Object Mapping

**Lösung**: A.

---

### Frage 88
Welche Aussage zur **Änderungskommission** stimmt?
- A) Sie betrachtet Änderungen aus rein technischer Sicht.
- B) Sie betrachtet Änderungen aus **strategischer und organisatorischer Sicht**.
- C) Sie bewertet Konsequenzen, Kosten, Nutzen, Releaseplan und betroffene Benutzer.
- D) In agilen Methoden ist auch der Kunde involviert.

**Lösung**: B, C, D.

---

## H) Querschnitt-Fragen

### Frage 89
Was ist **kein** typischer Inhalt eines Release Notes-Dokuments?
- A) Versionsnummer
- B) Datum
- C) Fixed Bugs
- D) Komplette Spezifikation der Architektur

**Lösung**: D. *Architektur gehört nicht in Release Notes.*

---

### Frage 90
Welche Aussage zur **Definition of Done** ist falsch?
- A) Soll messbar sein.
- B) Team-/projektspezifisch.
- C) Festlegt, wann etwas "fertig" ist.
- D) Wird immer vom Product Owner allein festgelegt.

**Lösung**: D. *DoD wird typischerweise vom Team gemeinsam erstellt.*

---

### Frage 91
Welche der folgenden Aussagen zu **agilen vs. klassischen** Modellen stimmen?
- A) Agile Modelle erwarten Änderungen.
- B) Klassische Modelle nutzen viele Dokumente, agile nutzen direkte Kommunikation.
- C) Agile Modelle benötigen ständige Kundenmitwirkung.
- D) Klassische Modelle planen viel im Voraus.

**Lösung**: A, B, C, D. *Alle stimmen!*

---

### Frage 92
Sortiere die Reihenfolge der Aktivitäten im **Spiralmodell** in einer Runde:
- A) Entwicklungsziele → Risikoanalyse → Entwicklung → Planung
- B) Implementation → Test → Deploy → Maintain
- C) Spezifikation → Design → Codierung → Test
- D) Backlog → Sprint → Review → Retrospektive

**Lösung**: A. *Spiralmodell-Runden: Ziele/Beschränkungen → Risikoanalyse → Entwicklungsphase → Planungsphase.*

---

### Frage 93
Welche **Reihenfolge** ist im Sinne der CMMI-Stufen korrekt?
- A) Initial → Repeatable → Defined → Managed → Optimizing
- B) Initial → Defined → Repeatable → Managed → Optimizing
- C) Initial → Managed → Optimizing → Defined → Repeatable
- D) Optimizing → Managed → Defined → Repeatable → Initial

**Lösung**: A.

---

### Frage 94
Welche **Story Card**-Elemente gehören auf die Vorderseite?
- A) Priorisierung, Name, Story Points
- B) Beschreibung (WER/WAS/WARUM), Risiko
- C) Akzeptanzkriterien
- D) Vorbedingung / Aktion / Ergebnis

**Lösung**: A, B. *C und D gehören auf die Rückseite (Akzeptanzkriterien).*

---

### Frage 95
Was beschreibt der **Schätztrichter** typischerweise?
- A) Genauigkeit der Schätzung wächst über den Projektverlauf.
- B) Schätzfehler nimmt mit der Zeit ab.
- C) Frühe Schätzungen sind sehr genau.
- D) Schätzungen werden nach Projektende noch ungenauer.

**Lösung**: A, B.

---

### Frage 96
**Kano-Modell** – ordne zu:
- A) Sicherheit/Rostschutz → Basis-Merkmal
- B) Sonderausstattung/Design → Begeisterungs-Merkmal
- C) Beschleunigung/Verbrauch → Leistungs-Merkmal
- D) Dellen/keine Zulassung → Rückweisungs-Merkmal

**Lösung**: A, B, C, D. *Alle korrekt zugeordnet.*

---

### Frage 97
Was passiert bei einem **Gewöhnungseffekt** im Kano-Modell?
- A) Begeisterungs-Merkmale werden zu Basis-Merkmalen.
- B) Basis-Merkmale werden zu Begeisterungs-Merkmalen.
- C) Es entstehen neue Rückweisungs-Merkmale.
- D) Leistungs-Merkmale werden irrelevant.

**Lösung**: A. *Beispiel: SMS war früher begeisternd, heute Basis.*

---

### Frage 98
Welche der folgenden Aussagen zur **Aspektorientierung** (AOP) ist **falsch**?
- A) Aspekte enthalten Pointcuts und Advices.
- B) Join Points sind Punkte, an denen Aspekte eingreifen können.
- C) AOP wird typischerweise für die Hauptgeschäftslogik verwendet.
- D) Advices können Before, After oder Around sein.

**Lösung**: C. *AOP ist für **Cross-Cutting Concerns** (Logging, Security, Transaktionen), nicht für Hauptgeschäftslogik.*

---

### Frage 99
Welche Aussagen zur **Continuous Integration** stimmen?
- A) Findet meistens auf einem CI-Server statt.
- B) Tools: Jenkins, GitHub Actions, Travis CI, GitLab CI.
- C) Automatisches Bauen, Testen und Integrieren von Code.
- D) Sie ersetzt das Versionsmanagement.

**Lösung**: A, B, C.

---

### Frage 100
Welche der folgenden Aussagen zur **Function-Point-Methode** stimmt?
- A) Sie wurde 1979 von A. Albrecht bei IBM entwickelt.
- B) Sie schätzt aus **Benutzersicht**.
- C) UFP × VAF = FP.
- D) VAF = 0.65 + 0.01 × TDI.

**Lösung**: A, B, C, D. *Alle 4 stimmen!*

---

## I) Tiefere Verständnisfragen

### Frage 101
Warum sind **Daily Scrum Meetings** wichtig?
- A) Team bekommt täglich Projekt-Überblick.
- B) Erzeugt Peer-Druck, das zu tun, was man angekündigt hat.
- C) Können durch E-Mails ersetzt werden (laut Folie).
- D) Adressieren das Problem „Wie verspätet sich ein Projekt um ein Jahr? Um einen Tag zu jedem Zeitpunkt."

**Lösung**: A, B, D. *E-Mails können das **nicht** ersetzen.*

---

### Frage 102
Was sagt das **„90/90 Law of Project Management"**?
- A) 90 % der Projekte scheitern.
- B) Der Projektfortschritt erreicht schnell 90 %, bleibt dann bei 90 %.
- C) 90 % der Anforderungen kommen vom Kunden.
- D) 90 % der Bugs sind in 10 % des Codes.

**Lösung**: B. *Aus den "Laws of PM" nach Shtub.*

---

### Frage 103
Welche der folgenden Eigenschaften gehören zur **Dependency Injection mit Annotations (Spring)**?
- A) `@Autowired` ermöglicht Autowiring.
- B) `@Bean` markiert ein Objekt als Bean.
- C) Beans werden im Container als Singleton behandelt.
- D) Es benötigt zwingend eine XML-Konfiguration.

**Lösung**: A, B, C. *Annotations ersetzen XML.*

---

### Frage 104
Welche Aussage zur **Anforderungsabstimmung** stimmt?
- A) Bei Konflikten: **Identifikation → Analyse → Auflösen → Dokumentation**.
- B) Abstimmungs-/Weisungsmethoden setzen sich durch (Durchsetzung).
- C) Annäherungsmethoden sind kooperativ.
- D) Dokumentation der Auflösung dient der Nachvollziehbarkeit.

**Lösung**: A, B, C, D.

---

### Frage 105
Welche Aussagen zum **Burndown Chart** stimmen?
- A) Zeigt verbleibenden Gesamtaufwand pro Tag.
- B) Wird täglich aktualisiert und neu geschätzt.
- C) Bei Missbrauch (Management-Review) sollte es eingestampft werden.
- D) Ist ein Selbstzweck und muss perfekt aussehen.

**Lösung**: A, B, C.

---

### Frage 106
Was sind die **Aufgaben** eines Komponenten-**Frameworks**?
- A) Verdrahtung der Komponenten
- B) Konfiguration
- C) Lebenszyklus-Management
- D) Algorithmusoptimierung

**Lösung**: A, B, C.

---

### Frage 107
Welche der folgenden Aktivitäten im V-Modell entspricht **Verifikation**?
- A) Sicherstellen, dass das Produkt den Spezifikationen entspricht.
- B) Sicherstellen, dass das Produkt die Kundenwünsche erfüllt.
- C) Test gegen Anforderungen.
- D) User-Akzeptanztest.

**Lösung**: A. *„Bauen wir das Produkt richtig?" – gegen Spezifikation.*

---

### Frage 108
Welche Aussagen zur **Reuse-Strategie** stimmen?
- A) Reuse kann die Produktivität erhöhen.
- B) Das NIH-Syndrom („Not Invented Here") kann Reuse behindern.
- C) Es entstehen Kosten für Suche/Verstehen/Anpassen.
- D) Reuse ist immer billiger als Neuentwicklung.

**Lösung**: A, B, C. *D ist zu absolut – manchmal teurer.*

---

### Frage 109
**Lese- und Beobachtungstechniken** unterscheiden sich:
- A) Ad-hoc-Lesen → Stellungnahme
- B) Ablauforientiertes Lesen → Walkthrough
- C) Schrittweise Abstraktion → Notwendigkeit prüfen
- D) Perspektivbasiertes Lesen → vollständiges Bild aus mehreren Sichtweisen

**Lösung**: A, B, C, D.

---

### Frage 110
Welche Aussage zum **Pflichtenheft** ist **falsch**?
- A) Es wird vom Auftragnehmer erstellt.
- B) Beschreibt die konkrete Realisierung.
- C) Beschreibt nur das WAS, nie das WIE.
- D) Soll leicht veränderbar sein und ist Referenz für Wartungspersonal.

**Lösung**: C. *Pflichtenheft beschreibt **WIE**, Lastenheft das **WAS**.*

---

## J) Anwendungsfälle / Case-Style Fragen

### Frage 111
Du arbeitest in einem agilen Team an einer User Story mit 21 Story Points. Was machst du als Product Owner?
- A) In den nächsten Sprint einplanen.
- B) Als Epic markieren und in kleinere Stories aufteilen.
- C) Mehr Personal beschaffen.
- D) Sofort umsetzen, weil hoch priorisiert.

**Lösung**: B. *> 13 Story Points = Epic, muss vor Implementierung geteilt werden.*

---

### Frage 112
Ein Entwickler will alle Logging-Aufrufe an einer zentralen Stelle definieren, ohne den Code der einzelnen Klassen zu ändern. Was verwendet er?
- A) Direct call
- B) Dependency Injection
- C) Aspektorientierte Programmierung (AOP)
- D) Singleton-Pattern

**Lösung**: C. *Logging = klassisches Cross-Cutting Concern.*

---

### Frage 113
Ein Team will Konfigurationsdateien (für den Betrieb) versionieren. Welche DevOps-Practice ist das?
- A) Versionskontrolle für alle Bereiche (auch Betrieb)
- B) Automatisiertes Testen
- C) Proaktives Monitoring
- D) Kanban

**Lösung**: A.

---

### Frage 114
In welcher CMMI-Stufe sind Erfolge stark von **einzelnen Personen** abhängig?
- A) Stufe 1 – Initial
- B) Stufe 2 – Repeatable
- C) Stufe 3 – Defined
- D) Stufe 5 – Optimizing

**Lösung**: B. *Repeatable: Planung/Meilensteine vorhanden, aber Erfolg hängt von Personen ab.*

---

### Frage 115
Welcher Schätzansatz ist für ein Projekt sinnvoll, das **sehr ähnlich** zu einem bereits abgeschlossenen Projekt ist?
- A) Analogieschätzung
- B) Delphi-Methode
- C) Expertenschätzung
- D) Sonstige (Schmerzschwelle)

**Lösung**: A.

---

### Frage 116
Ein Junior-Entwickler ändert in seinem ersten Commit gleichzeitig: ein Typo im README, einen Bug-Fix in der Login-Logik und ein neues Feature. Was sollte er stattdessen tun?
- A) Alles in einem Commit lassen – wirkt produktiv.
- B) Drei separate Commits mit aussagekräftigen Messages und Issue-Referenzen.
- C) Den README-Typo entfernen, weil unwichtig.
- D) Alles auf den Master ohne Branch pushen.

**Lösung**: B. *Best Practice: 1 Commit pro Task, sinnvolle Messages.*

---

### Frage 117
Welche Beobachtungs-/Befragungs-Technik wäre für die Anforderungserhebung in einer Flughafen-Tower-Software am **wenigsten** geeignet?
- A) Hintergrundstudie
- B) Interview mit Fluglotsen
- C) **Apprenticing** ("in die Lehre gehen")
- D) Fragebogen

**Lösung**: C. *Apprenticing ist in kritischen Umfeldern nicht einsetzbar.*

---

### Frage 118
Du musst einen Web-Service entwerfen, der von vielen verschiedenen Plattformen genutzt werden soll, einfach zu nutzen ist, und JSON unterstützt. Welche Lösung?
- A) RESTful Web Service
- B) XML-basierter Web Service mit SOAP
- C) Microservice intern in Java
- D) COM-Komponente

**Lösung**: A. *REST: einfach, JSON-fähig, platformunabhängig.*

---

### Frage 119
Welche Pipeline-Stufe stellt sicher, dass eine **Änderung automatisch in Produktion** ausgebracht wird?
- A) Build Automation
- B) Continuous Integration
- C) Continuous Delivery
- D) Continuous Deployment

**Lösung**: D.

---

### Frage 120
Was ist der **wichtigste Unterschied** zwischen Continuous Delivery und Continuous Deployment?
- A) Delivery hat keine Tests.
- B) Bei Delivery erfolgt der finale Deployment-Schritt **manuell**.
- C) Deployment hat keine Tests.
- D) Beide sind völlig identisch.

**Lösung**: B.

---

## K) Stolperfallen / Fallen

### Frage 121
Welche **falschen** Aussagen kommen vor?
- A) Bei Continuous Deployment ist der letzte Schritt manuell.
- B) Im Daily Scrum reden alle Teilnehmer.
- C) Story Points entsprechen exakt Personentagen.
- D) Velocity wird in Personentagen gemessen.

**Lösung**: A, B, C, D – **alle falsch**. *(A: Delivery! B: Nur „Schweine"! C: Story Points sind relativ! D: Velocity in Story Points!)*

---

### Frage 122
Welche Aussage zu Function Points ist **richtig**?
- A) Sie schätzen aus Entwicklersicht.
- B) ILF = External Interface File.
- C) FP = UFP × VAF, wobei VAF = 0.65 + 0.01 × TDI.
- D) Function Points wurden von Boehm entwickelt.

**Lösung**: C. *Aus **Benutzer**sicht, ILF = Internal, Albrecht (IBM).*

---

### Frage 123
Welche Aussage zum **V-Modell** ist **falsch**?
- A) Es lehnt Dokumentation ab.
- B) Es integriert Qualitätssicherung.
- C) Es ist anpassbar.
- D) Es eignet sich für große Projekte.

**Lösung**: A. *V-Modell ist dokumentationsstark.*

---

### Frage 124
Welche Aussage über **Software Engineering vs. „Hacken"** stimmt **nicht**?
- A) Personal Software: Developer = User
- B) Industrial-strength Software: Client = User
- C) Personal Software: Robustheit ist entscheidend
- D) Industrial-strength Software: Portabilität als ökonomischer Vorteil

**Lösung**: C. *Bei Personal Software ist Robustheit nicht entscheidend.*

---

### Frage 125
Welche der folgenden ist **kein** Vorteil agiler Methoden?
- A) Verbessertes Kosten/Nutzen-Verhältnis
- B) Bessere durchschnittliche Code-Qualität
- C) Vorhersagbares Ergebnis
- D) Reaktion auf Änderungen

**Lösung**: C. *Vorhersagbares Ergebnis ist ein **Nachteil** agiler Methoden.*

---

## Zusatz: Lückenfüller (Kurz-Fragen)

### Frage 126
Wie viele Werte hat das Agile Manifest? → **4**

### Frage 127
Wer hat das Wasserfall-Modell formal beschrieben? → **Royce, 1970**

### Frage 128
Wer prägte den Begriff „Mythical Man-Month"? → **Fred Brooks, 1975**

### Frage 129
Wer entwickelte COCOMO? → **Barry Boehm**

### Frage 130
Wofür steht „PDCA"? → **Plan-Do-Check-Act (Qualitätsmanagement)**

### Frage 131
Wofür steht „REST"? → **Representational State Transfer**

### Frage 132
Wie viele Phasen hat eine Inspektion (nach IEEE)? → **6**

### Frage 133
In welcher CMMI-Stufe ist der Prozess „institutionalisiert"? → **Stufe 3 (Defined)**

### Frage 134
Wie viele Hüte hat „6-Hut-Denken"? → **6**

### Frage 135
Was bedeutet "INVEST" für das I? → **Independent (unabhängig)**

---

## Tipps zur Klausur

- **Lies jede Frage sorgfältig.** Achte auf Wörter wie *„nicht"*, *„falsch"*, *„immer"*, *„nur"*.
- **Bei Mehrfach-Auswahl**: Frage dich für jede Option einzeln „Stimmt das?".
- **Begründe** dir selbst die Antwort (auch wenn nur im Kopf) – das hilft, Fallen zu erkennen.
- **Definitionen** sind häufig prüfungsrelevant – kenne die genauen Wörter (z. B. „kontrollierte Änderung", „beobachtbares Verhalten", „abschätzbare Wahrscheinlichkeit").
- **Akronyme**: Stelle sicher, dass du alle aus der `ZUSAMMENFASSUNG.md` parat hast.
- **Zahlen**: Achte auf Größenordnungen (Team 5–10, Sprint ~ 1 Monat, Daily 15 Min, > 13 Story Points = Epic, KDSI für COCOMO).
- **Bei Aufgaben zu COCOMO/FP**: Tabellen aus der Folien-Übersicht (im Handout enthalten) im Kopf haben.

**Viel Erfolg morgen!**
