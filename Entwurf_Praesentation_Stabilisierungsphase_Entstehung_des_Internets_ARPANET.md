# Präsentation: Die Stabilisierungsphase in der Genese des Internets




## Folie 1: Titel & Agenda

**Titel:** Die Stabilisierungsphase: Vom visionären Projekt zum stabilen Netzwerk
**Fallbeispiel:** Die Entstehung von ARPANET

**Agenda:**
1. Theoretischer Rahmen: Das Phasenmodell (Stabilisierung)
2. Zielsetzung: Technik & Soziales
3. Kopplung heterogener Akteure & Handlungsprogramme
4. Soziale Schließung & Institutionalisierung
5. Aktivitätsstimulierung: Die RFC-Kultur
6. Systematische Erforschung & Prototypenbau
7. Pfadentscheidungen & Lock-in-Effekte
8. Fazit: Warum sich das Netz stabilisierte

---

## Folie 2: Theoretischer Rahmen – Was ist die Stabilisierungsphase?

 

**Definition:**
Die Stabilisierungsphase ist der Übergang von der Erfindung (Invention) zur Innovation. Die Technik wird in die Gesellschaft „eingebettet“.

**Zentrale Merkmale:**
*   **Ziel A (Technik):** Systematische Erforschung und Erprobung bis zum Prototyp.
*   **Ziel B (Soziales):** Stabilisierung durch soziale Vernetzung in turbulenten, oft feindlichen Umwelten.
*   **Folgen:** Rekombination von technisch-apparativen und sozialen Komponenten. Der „sozio-technische Kern“ bleibt erhalten.

**Leitfrage für den Fall ARPANET:**
Wie wurde aus einem losen Forschungsverbund ein stabiles, funktionierendes Netzwerk?

---

## Folie 3: Die Ausgangslage – Ein heterogenes Feld

 

**Das Problem:**
Die Entwicklung von ARPANET war zu komplex für eine einzelne Stelle. Larry Roberts (ARPA) wollte nicht „alle Eier in einen Korb“ legen.

**Die Lösung: Kopplung heterogener Akteure**
*   **Gründung der Network Working Group (NWG) 1969:**
    *   Start mit 5 Hauptmitgliedern (UCLA, SRI, University of Utah).
    *   **Prinzip:** Offene Mitgliedschaft (RFC 3). Wachstum auf über 300 Mitglieder.
*   **Rollenverteilung:**
    *   **ARPA:** Finanzierung, Terminsetzung, strategische Steuerung.
    *   **BBN:** Entwicklung der IMP-Hardware und -Software.
    *   **Universitäten/Forschungszentren:** Protokolldiskussion, Entwicklung, Testung.

**Soziologische Relevanz:**
Dies ist keine reine Auftragsforschung, sondern ein *strategiefähiger Akteur* (ARPA) schafft ein Netzwerk, in dem unterschiedliche Interessen gebündelt werden.

---

## Folie 4: Kopplung der Handlungsprogramme – Der Kompromiss
 
**Die Herausforderung:**
Unterschiedliche Prioritäten der Akteure:
*   **BBN:** Termindruck, schnelle Inbetriebnahme.
*   **NWG:** Allgemeine, flexible Protokolle für verschiedene Anwendungen.

**Der Stabilisierungsmechanismus:**
*   **Verhandlung & Fokussierung:** Man einigte sich auf einen kleineren Umfang der ersten Protokollgruppe.
*   **Telnet** (Terminal-Sitzung) und **FTP** (Dateiübertragung) als gemeinsamer Nenner.
*   **Ergebnis:** Ein Netz, das *tatsächlich funktioniert* und als Basis für spätere Erweiterungen dient.

**Theoretische Einordnung:**
Dies ist die *Kopplung der Handlungsprogramme*. Trotz unterschiedlicher Orientierungen entsteht ein gemeinsames Interesse: die Funktionsfähigkeit des Netzes.

---

## Folie 5: Soziale Schließung – Störungseliminierung durch Institutionen


**Das Problem:**
Mit wachsender Teilnehmerzahl reichte unorganisierte Zusammenarbeit nicht mehr aus. Unsicherheit und Informationsoffenheit mussten reduziert werden.

**Die institutionelle Antwort (Störungseliminierung):**
*   **NIC (Network Information Center) bei SRI:**
    *   Archivierung der NWG Notes und RFCs.
    *   Benennung von *Station Agents* und *Technical Liaison Contacts* pro Institution.
*   **NMC (Network Measurement Center) in UCLA:**
    *   Leitung: Leonard Kleinrock. Messung der Netzleistung, Analyse des Verhaltens.
*   **NCC (Network Control Center) bei BBN:**
    *   Vertragliche Verpflichtung. Troubleshooting, Diagnosis, Repair.

**Folge:**
ARPANET wandelte sich von einem Forschungsprojekt zu einem System mit klarer institutioneller Struktur. Die *soziale Schließung* reduzierte Verwirrung und Unsicherheit.

---

## Folie 6: Aktivitätsstimulierung – Die Erfindung der RFC


**Das Problem:**
Wie werden Ideen festgehalten und diskutiert, wenn das Netz noch nicht fertig ist?

**Die Lösung: Requests for Comments (RFC)**
*   **Erste RFC (RFC 1) am 7. April 1969 von Steve Crocker.**
*   **Prinzip:** Informell, offen für Diskussion, jeder kann veröffentlichen.
*   **Zyklus der Wissensbildung:**
    1.  Forscher schreibt technischen Vorschlag.
    2.  Andere lesen, diskutieren, schlagen Änderungen vor.
    3.  Lösung wird im Netz getestet.
    4.  Fehler treten auf, Vorschlag wird überprüft.
*   **Rollenwandel der RFC:** Vom Ideenaustausch zur grundlegenden Dokumentation der Netzprotokolle (bis heute).

**Theoretische Einordnung:**
Dies ist die *Aktivitätsstimulierung*. Individuelles Wissen wird zu gemeinsamem, dokumentiertem Wissen. Die rekursive Stimulierung führt zu technologischen Durchbrüchen.

---

## Folie 7: Systematische Erforschung – Hardware & Software wachsen zusammen


**Das Problem:**
Kein detailliertes technisches Design von ARPA. Die NWG musste den Denkraum nutzen.

**Die Prinzipien:**
*   **Generality:** Mechanismen für mehr als einen Fall.
*   **Flexibility:** Neue Funktionen ohne Neuentwurf des Systems.

**Die Herausforderung der Koordination:**
*   NWG diskutierte Protokolle, während BBN die IMPs entwickelte.
*   **Kein fertiges Enddesign:** Hardware und Software entwickelten sich *parallel*.
*   Ständiger Informationsaustausch und Anpassung der Schnittstellen (Host-IMP Interface) notwendig.

**Das Ergebnis:**
*   Entstehung des **Schichtenmodells** (RFC 1).
*   Untere Schichten: IMP-Software (BBN).
*   Obere Schichten: Host-Software (NWG).
*   Das Netz wandelte sich von einer Sammlung von Ideen zu einer *integrierten technischen Architektur*.

---

## Folie 8: Erprobung bis zum Prototyp – Der Pfad wird betoniert


**Die technische Umsetzung:**
*   **IMP-IMP-Protokoll (BBN):** Paketierung, Routing, Fehlerbehandlung. Erreichte schnell Reifegrad.
*   **Host-Host-Protokoll (NWG):** Logische Verbindungen, Flusskontrolle. Durchlief viele Änderungen (RFC 1 bis NCP).

**Der Wendepunkt (Pfadentscheidung):**
*   Anfangs häufige Änderungen am Host-Host-Protokoll.
*   **Problem:** Mit Beginn der Umsetzung wurden Änderungen *teuer* (fast fertige Anwendungen mussten neu bearbeitet werden).
*   **MIT-Position:** Protokoll ist nun nutzbar. Erfahrung aus dem Betrieb sammeln statt theoretischer Änderungen.
*   **Crocker (RFC 73):** Nutzung des Netzes zeigt klarere Bedürfnisse. Ziel: Ein Protokoll, das *tatsächlich funktioniert*.

**Folge:**
Die Einigung war eine *technisch erprobte Einigung*, nicht nur eine soziale. Der Pfad wurde stabilisiert.

---

## Folie 9: Soziale Netzwerke als Basis der Stabilisierung – Standardisierung


**Die Frage:** Wer setzte die Standards? Keine einzelne Stelle.

**Der Prozess der Standardisierung (4 Dimensionen):**
1.  **Dokumentation:** Eine dokumentierte Version (z.B. RFC 107) legt fest, wie das Protokoll funktioniert.
2.  **Implementierung:** Alle setzen die Änderungen nach Spezifikation um.
3.  **Kompatibilität:** Mechanismen (z.B. Versionsnummern, RFC 135) sichern Kompatibilität zwischen verschiedenen Versionen.
4.  **Koordination:** Änderungen werden koordiniert und dokumentiert (z.B. Socket-Struktur, RFC 147).

**Die soziale Dimension:**
*   Ein Standard stabilisiert sich nicht allein durch technische Richtigkeit.
*   Er stabilisiert sich, weil ein **Netzwerk von Akteuren** ihn annimmt, nutzt und unterstützt (ARPA, Universitäten, Forscher).
*   *Soziale Schließung* bedeutet hier: Die Akteure einigen sich auf gemeinsame Spezifikationen und schließen Alternativen aus.

---

## Folie 10: Pfadentscheidungen – Warum TCP/IP und nicht OSI?


**Der offizielle Übergang:**
*   1. Januar 1983: ARPANET wechselt offiziell zu TCP/IP.

**Warum setzte sich TCP/IP durch?**
*   **Praktische Verbreitung:** TCP/IP entwickelte sich *praktisch* in der ARPA-Umgebung.
*   **Unterstützung:** ARPA-Finanzierung, Zusammenarbeit von Universitäten, praktische Erprobung.
*   **Netzwerkeffekt:** Der Wert einer Technologie steigt mit der Zahl ihrer Nutzer.
*   **Lock-in-Effekt:** Institutionen bleiben bei einem System, weil der Wechsel teuer ist.

**Die Konkurrenz (OSI):**
*   OSI war ein internationales Bestreben zur Vereinheitlichung.
*   Bot ein systematisch attraktives Konzept, aber: Der Übergang erforderte Änderung bestehender Systeme, Investitionen und Praktiken.
*   **Fazit:** Der Weg, der sich um TCP/IP bildete, gewann praktische Verbreitung und Unterstützung, *bevor* OSI sich als umfassende Alternative durchsetzen konnte.

---

## Folie 11: Die Kosten des Ausstiegs – Warum Pfadwechsel schwer sind


**Die Logik des Lock-in:**
*   Wenn sich eine Technologie verbreitet, wird um sie herum ein ganzes System aufgebaut:
    *   Infrastruktur entsteht.
    *   Firmen spezialisieren sich auf Produktion.
    *   Menschen lernen sie zu nutzen.
    *   Institutionen investieren.
*   **Folge:** Die Kosten für den Wechsel zu einer Alternative steigen.

**Die Wurzeln im ARPANET:**
*   Als die wiederholten Änderungen am Host-Host-Protokoll nach Beginn der Umsetzung teuer wurden (Abschnitt 8), wurde es bevorzugt, das Protokoll zu *stabilisieren* und Erfahrung zu sammeln.
*   **Soziologische Erkenntnis:** Die Investition in die Umsetzung selbst schränkte die späteren Optionen ein. Dies wiederholt sich im größeren Maßstab, wenn TCP/IP in Netzen und Institutionen verwurzelt ist.

---

## Folie 12: Warum wurde ARPANET 1990 geschlossen?


**Die Fakten:**
*   ARPANET war anfangs ein Forschungs- und Militärnetz (ARPA-finanziert).
*   1986 entstand NSFNET, um Universitäten und Forschungszentren zu verbinden.
*   Andere Netze entstanden, die die Verbindung bieten konnten.
*   **1990:** Schließung von ARPANET.

**Die soziologische Interpretation:**
*   Es wurde nicht geschlossen, weil das kommerzielle Internet es dazu zwang.
*   Es wurde geschlossen, weil seine historische und technische Rolle auf ein *breiteres Netzsystem* überging.
*   **Offene Frage:** War es technisch unnötig geworden, oder war das breitere Internet für die neuen Interessen und Institutionen geeigneter?
*   **Perspektive Weyer:** Die Schließung ist nicht nur eine technische Entscheidung, sondern das Ergebnis der gemeinsamen Veränderung von technischer, sozialer und wirtschaftlicher Struktur.

---

## Folie 13: Fazit – Die Mechanik der Stabilisierung


**Warum stabilisierte sich das Internet?**

1.  **Kopplung heterogener Akteure:** ARPA als strategiefähiger Akteur, NWG als offenes Netzwerk, BBN als Industrie partner.
2.  **Kopplung der Handlungsprogramme:** Kompromiss zwischen Termindruck (BBN) und Flexibilität (NWG) durch Fokussierung auf Telnet/FTP.
3.  **Soziale Schließung (Störungseliminierung):** Institutionalisierung durch NIC, NMC, NCC. Reduktion von Unsicherheit.
4.  **Aktivitätsstimulierung:** RFC-Kultur als rekursiver Zyklus der Wissensbildung und Dokumentation.
5.  **Pfadentscheidungen:** Frühe Investitionen in NCP/TCP/IP erhöhten die Exit-Kosten. Lock-in-Effekt.
6.  **Soziale Netzwerke als Basis:** Standardisierung durch Akzeptanz und Nutzung, nicht nur durch technische Richtigkeit.

**Kernaussage:**
Die Stabilisierung des Internets war kein rein technischer Prozess. Sie war das Ergebnis eines *sozio-technischen* Prozesses, in dem soziale Netzwerke, institutionelle Strukturen und technische Entscheidungen untrennbar miteinander verwoben waren.

---

## Folie 14: Diskussionsfragen


---

## Folie 15: 
