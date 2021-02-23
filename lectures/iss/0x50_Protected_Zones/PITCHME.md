## Geschützte Zonen
Zonen & Conduits, Security Level

+++?image=assets/img/zone2.svg
@snap[north span-100 text-left text-07]
### Zonen & Conduits 
Zonen sind logische Gruppierungen, um Systeme zu segmentieren.
@snapend

@snap[south text-04]
@box[bg-orange text-white rbox-padding](Conduits sind spezielle Formen von Zonen für die zonenübergreifende Kommunikation)
@snapend

note:
Burg und Zoogeschichten

+++
@snap[north span-100 text-left text-07]
### Security Levels
Risikobasiert - 5 Stufen in SL-T Target, SL-A Achieved, SL-C Capability
@snapend 

@snap[east span-99 text-left text-05]

**SL0** - keine besonderen Anforderungen

**SL1** - Schutz gegen **ungewollten, zufälligen** Verstoß

**SL2** - Schutz gegen **gewollten Verstoß** unter Verwendung von einfachen Mitteln, mit niedrigem Ressourcen, allgemeinen Fähigkeiten und niedriger Motivation

**SL3** - Schutz gegen gewollten Verstoß unter Verwendung von **technisch ausgefeilten Mitteln**, mit moderatem Aufwand, **automatisierungstechnisch** spezifischen Kompetenzen und moderater Motivation,

**SL4** -  Schutz gegen gewollten Verstoß unter Verwendung von technisch ausgefeilten Mitteln, mit erheblichem Aufwand, automatisierungstechnisch spezifischen Kompetenzen und **hoher Motivation**.
@snapend

note: 
> Ursprung: Safety 20 Jahre SIL

> SL0

> SL1 - Basisbedrohung
- durch lasche, nachlässige Anwendung von Sicherheitsrichtlinien  von wohlmeinenden Mitarbeitern verursacht 
- Bedrohung durch Außenstehende
- --> Durchsetzung von Richtlinien und Verfahren behoben.
- zufällig, nichtbeabsichtigt !!
- Sicherstellen, dass das Steuerungssystem unter normalen Produktionsbedingungen zuverlässig arbeitet
- DoS-Situationen verhindert, die durch zufällige/unbeabsichtigte Handlungen eines Unternehmens verursacht werden.
- Verhindern der unbefugten Weitergabe von Informationen zB durch Abhören oder zufällige/unbeabsichtigte Enthüllung
- Identifizieren und authentifizieren aller Benutzer (Menschen, Softwareprozesse und Geräte) mithilfe von Mechanismen, 
die vor dem zufälligen/unbeabsichtigten Zugriff nicht authentifizierter Entitäten schützen.
- Schützen Sie die Integrität des IACS vor zufälliger/unbeabsichtigter Manipulationen.
- Beschränken Sie die Verwendung des IACS gemäß den angegebenen Berechtigungen zum Schutz vor zufälligem/unbeabsichtigtm Missbrauch.
- Verhindern Sie die zufällige/unbeabsichtigte Umgehung der Segmentierung von Zonen und Leitungen.
- Überwachen Sie den Betrieb des IACS und reagieren Sie auf erkannte Vorfälle, 
indem Sie die forensischen Beweise sammeln und bei Fragen bereitstellen.

> Beispiel für Auslegung SL1

- Careless Employee, contractor - hazard, accident, by mischance

- Mitarbeiter, externer Servicemitarbeiter verursachen versehentlich einen Produktionsausfall aufgrund mangelnden SystemknowHow und 
unzureichender Vorgaben und Absicherung. zB Löschen von kritischen Systemdateien
- unbeabsichtigtes Einschleusen von Schadsoftware über Wechseldatenträger und externe Hardware Infektion mit Schadsoftware über Internet
- Menschliches Fehlverhalten, Fahrlässigkeit 
- Fehlkonfiguration sicherheitsrelevanter Komponenten 
- unkoordinierten Einspielen von Updates oder Patches 
- Kompromittierung von Systemen durch nicht genehmigte Soft- und Hardware
- Erstellung nicht freigegebener Konfigurationen für Infrastruktur- und Sicherheitskomponenten 
- Technisches Fehlverhalten und höhere Gewalt (Defekt von Komponenten, Softwarefehlr)
- unkoordinierte UDP Scans um Netzwerkgeräte aufzufinden durch IT Personal

> Script Kiddie SL1/SL2
- Da auch bei SL1 der sorglose, übermotivierte, sich überschätzende Mitarbeiter Skript Kiddie Werkzeuge einsetzen wird.
und bei SL2 auch Angriffe mit einfachen Skript Kiddie Werkzeugen gestartet werden können

> SL2 - erweiterte Bedrohungen
- Ressourcen bzw. Aufwand
- vorsätzlich bzw. gewollt
- Kompetenzen bzw. Fähigkeiten
- Beispiel für Auslegung: Insider or Intruder, frustrierter Mitarbeiter, Hacker, Cyber Crime

> SL3 - raffinierten Bedrohungen
- vorsätzlich bzw. gewollt
- raffiniert buzw. ausgefeilt
- Ressourcen bzw. Aufwand
- Beispiel für Auslegung: Aktivitistengruppen, Arbeitsteilige Hackergruppen, Terroristen

> SL4
- vorsätzlich bzw. gewollt
- ausgefeilt, raffiniert, ausgeklügelten
- erweiterten Ressourcen, erheblicher Aufwand
- systemspezifischen Fähigkeiten, Kompetnezen
- Beispiel für Auslegung: Regierung, Nation State, Geheimdienste, NSA, APT-28

> (adv.)
- SL auch als Vektor über alle FR darstellbar
- SL-C(SPS)= {2,2,3,2,2,3,3}     {IAC,UC,SI,DC,RDF,TRE,RA} 

> Functional Requirements
- FR1 - IAC, Identification and Authentication Control
- FR2 – UC, Use Control
- FR3 - SI, System Integrity
- FR4 – DC, Data Confidentiality
- FR5 – RDF, Restricted Data Flow
- FR6 – TRE, Timely Response to Events
- FR7 – RA Resource Availability

+++
@snap[north span-100 text-left text-07]
### Maturity Levels
Reifegrad der Security Organisation
@snapend

@snap[east span-99 text-left text-05]
**ML1** – Ad-hoc Prozesse

**ML2** – **Dokumentierte Prozesse**, aber nicht zwingend wiederholbar

**ML3** – Dokumentierte Prozesse, welche wiederholbar sind und beständig befolgt werden

**ML4** – Dokumentierte Prozesse, wiederholbar, beständig befolgt werden, **gemessen und laufend verbessert werden **
@snapend    

note:
Kompetenz und Befähigung, Policies. Certification, Practices, Training, Standards

NIST / C2M2 – Maturity Levels (As Examples)
ML 3 – Practices are managed with policies and governance from organization. Policies are reviewed and adjustments made as needed and include compliance with specified standards and/or guidelines.
ML 2 – Risk practices are approved by management and expressed as policy, policies, processes, and procedures are defined, implemented and validated. Adequate resources are provided.
ML 1 – Risk practices are performed but may be adhoc, typically by individual thus outcome may vary depending on the individual.
ML 0 – Practices are not formalized, often case by case, and risk is managed in an ad hoc and sometimes reactive manner.
 
+++?image=assets/img/pl.png
@snap[north span-100 text-left text-07]
### Protection Level
@snapend

note:
Secure physical Access
Organize for Security
Secure solution Design
Secure Operation
Secure Lifecycle Management