## Anwendungsgebiet, Rollen und Struktur

+++?image=assets/img/reference.svg&size=50%
@snap[north span-100 text-left text-07]
### Anwendungsgebiet
OT (L0-L3), Enterprise IT (L4+, Engineering Workstations)

@snapend

@snap[north-east span-15 text-04]
@box[bg-gray text-white rounded box-padding](L5 Connected World)
![](assets/img/f_reference.pdf)
@snapend

@snap[south-east bg-orange span-30 text-05 text-left]
@quote[No Disruption, never down](Mike Spear, Honeywell)
@snapend

@snap[south text-03 docslink]
@box[bg-gray text-white demo-box-pad](Quelle: IEC 62443-1-1)
@snapend

@snap[south-west span-25 text-05]
@box[bg-white text-gray rounded box-padding](L0 Sensor & Actuators)
@box[bg-gray text-white rounded box-padding](L00 Physical Process)
@snapend

note:
L4 - L5 connected world
L3 - L4 mes, erp
Integrität des Datenaustauschs zwischen Geschäfts (L4-L5)- und Automatisierungsystem (L0-L3) wird in IEC 62443 berücksichtigt.
L2 -  L3 data historian servers, scada, hmi
L1 -  L2 dcs, plc, rtu, ied
L0 -  L1 sensor
L00 - L0 process

+ networking, monitoring, diagnostic, assessment system, data logging, safety, maintenance, quality assurance, regulatory compliance
+ network, firealls, routers, switches, gateways, fieldbus system
+ operation system, applications
+ human

Asset Checkliste
- wirtschaftlicher Wert
- Funktion, Backup, Management, Notfall
- geistiges Eigentum
- Schutz Mitarbeiter, Umwelt, Öffentlichkeit (environmental protection)
- Gesetzliche Anforderung (egulatory compliance)

Sehr gutes Beispiel Mengui Plant 
Quelle: Alignment Report for Reference Architectural Model for Industrie 4.0/Intelligent Manufacturing System Architecture

+++
@snap[north span-100 text-left text-07]
### Rollen und Verantwortung
Betreiber, Integratoren, Hersteller, Dienstleister und Behörden
@snapend

@snap[west span-50 text-left text-04]
**Betreiber** (Asset Owner, Anlageneigentümer) und ggf. **Service Provider**
- Spezifikation der Anforderungen
- Definition Security Level
- Betrieb und Wartung der Automatisierungslösung
- Change Management
- Patch Management
- Incident Handling
- Backup and Recovery
- Stilllegung
@snapend

@snap[south span-80 text-left text-04]
**Integrator** (Systemintegrator)
- Entwurf nach projektspezifischen Anforderungen
- Bereitstellung und Inbetriebnahme der Automatisierungslösung samt Sicherheitssystemen
<br><br>
@snapend

@snap[east span-40 text-left text-04]
**Hersteller** (Komponentenlieferanten)
- Entwicklung
- Vermarktung 
- Wartung von Komponenten 
- Schwachstellenmanagement
- Incident Handling 
- Patchbereitstellung
<br><br>
@snapend

note:
Rollen können von verschiedenen Organisationen wahrgenommen werden. z.B. Übertragung von Aufgaben von Anlageneigentümer an Dienstleister

Das ganzheitliches Sicherheitskonzept umfasst technische und organisatorische Maßnahmen über den Lebenszyklus, die von folgenden Stakeholder erfüllt werden.

+++?image=assets/img/structure.svg&size=80%
@snap[north span-100 text-left text-07]
### Struktur
@snapend

@snap[south text-05 docslink]
@box[bg-gray text-white demo-box-pad](entnommen aus Guideline Industrial Security, Pierre Kobes 2017)
@snapend

note: 
4 Bereiche, 14 Dokumente
(noch nicht alle Dokumente sind veröffentlicht, Stand Dez. 2019)

1. Kapitel "Allgemein"
- allgemeine Konzepte, Terminologien und Methoden

2. Kapitel "Richtlinien und Prozesse"
Richtlinien und Prozesse für die Entwicklung und Betrieb eines umfassenden Schutzkonzepts (Betreiber und Servicedienstleister und Integrator (Bereitstellung Konfiguration)
- Patchmanagement während Betrieb (Betrifft Betreiber, Integrator und Hersteller)
IEC 62443-2-1, Requirements for an IACS security management system (asset owner)
IEC 62443-2-4, Requirements for IACS solution suppliers [system integrator, service providers)

Zielgruppe: Anlagenbetreiber und Servicedienstleister und Systemintegrator (Bereitstellung Konfiguration)

3. Kapitel "System"
- technische Anforderungen an Steuerungssystem (Hersteller)
- Schritte zur Unterteilung der Systemarchitektur in Zonen und Conduits
- basierend einer Risikoanalyse - Definition der Sicherheitslevel je Zone und Conduit
IEC 62443-3-3, System security requirements and security levels (product suppliers, System Integrator)

4. Kapitel "Komponenten"
- Sicherheitsanforderungen des Entwicklungsprozesses (Produktanbieter)
- Ziel Schwachstellen vermeiden.
- technischen Anforderungen an die Geräte
-- Controller und RTU (embedded)
-- Host based (Operator und Engineering Workstations
-- Network (Firewall, Switches, ...)
-- Applications (HMI, Historian, ... )