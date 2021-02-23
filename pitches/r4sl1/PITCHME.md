+++
## Ready for Security Level 1
### Herbert Dirnberger @fab[linkedin] 

@snap[north-west span-40 text-05 text-left text-gray]
@quote[Für eine sichere digitale Welt. Cybersicherheit wird zum wichtigsten Sicherheitsthema der Zukunft – gerade im Zeitalter der Digitalisierung.](Siemens 2019)
@snapend

note: @snap[south text-05 text-left span-100 text-gray] 
### Herausforderung Industrial IoT (Internet of Things)
Automatisierungssysteme der kritischen Infrastruktur und Produktionsanlagen sind konkrete Ziele von Cyberangriffen. Die Systeme sind meist sehr anfällig und die Angriffe haben meist schwere Folgen.
## 
Um diese zu schützen erfordert es ein tiefes Verständnis und Kenntnis für Automatisierung, Produktionsprozesse, Cybersicherheit, Informationstechnologie, Best Practices und Standards.
@snapend

+++ 
@snap[north text-left text-07 span-100]
## Austria Cyber Security Challenge
### Österreichs größter „Hacker-Wettbewerb“
@snapend 

@snap[west span-50] 
![Logo](assets/img/csa-team.jpg)
@snapend

@snap[east span-45] 
![Logo](assets/img/csca.png)
@snapend

@snap[south-west text-05 span-100 text-gray]
Die CSA – Cyber Security Austria veranstaltete in Zusammenarbeit mit dem Bundeskanzleramt, dem BM für Inneres, dem BM für Landesverteidigung, dem BM für Bildung, Wissenschaft und Forschung sowie dem BM für Digitalisierung und Wirtschaftsstandort 2020 schon zum **neunten** Mal die Austria Cyber Security Challenge. 
@box[demo-box-pad](https://www.verbotengut.at)
@snapend


+++ 
@snap[north text-left text-07 span-100]
## Ransomware vs Produktion
### Referenzliste von Produktionsstillständen
@snapend 

@snap[south-east span-35 text-05 text-left text-gray]
@quote[You must protect it yourself.]
@snapend

@snap[west span-35] 
![Logo](assets/img/egregor.png)
@snapend


@snap[south-west text-05 span-35] 
@box[bg-gray text-white demo-box-pad](LockerGogA --> NORSK HYDRO)
@box[bg-green text-white demo-box-pad](Snake --> HONDA)
@box[bg-gray text-white demo-box-pad](Ryuk --> EVRAZ)
@box[bg-orange text-white demo-box-pad](eGregor --> **IHR UNTERNEHMEN** )
@snapend


@snap[east text-05 span-35 text-gray] 
![Logo](assets/img/scadaandme.png)
@box[demo-box-pad](entnommen aus SCADA and Me: A Book for Children and Management, Robert M. Lee 2013)
@snapend

note:
https://www.it-daily.net/it-sicherheit/cybercrime/21240-horrorszenario-produktionsstillstand-durch-cyber-angriffe 
https://www.zdnet.com/article/one-of-roman-abramovichs-companies-got-hit-by-ransomware/)




+++?image=assets/img/iec62443_overview.png&size=75%
@snap[north span-100 text-07 text-left]
## IEC 62443 Basics
### Grundbausteine des Standards einfach erklärt
@snapend

@snap[south text-05 span-60 text-gray] 
@box[demo-box-pad]([eigene Darstellung])
@snapend

+++
@snap[north span-100 text-07 text-left]
## IEC 62443 IACS Lifecycle
### Security von Anfang an mitdenken!
@snapend

@snap[west text-04 span-55 text-gray] 
![Logo](assets/img/lifecycle.svg)
@box[demo-box-pad](entnommen aus Guideline Industrial Security, Pierre Kobes 2017)
@snapend

@snap[east text-05 span-45 text-gray] 
![Logo](assets/img/iec62443_cycle.png)
@box[demo-box-pad]([eigene Darstellung])
@snapend





note:

+++
@snap[north span-100 text-07 text-left]
## Security Level 
### SL-Stufen aus Sicht der Angriffsresistenz
@snapend

@snap[west text-04 span-100 text-gray] 
![Logo](assets/img/sl.png)
@box[demo-box-pad](entnommen aus TeleTrusT-Prüfschema nach IEC 62443-4-2 2019-05)
@snapend


@snap[south text-04 span-100 text-gray text-left] 
**SL1: Mitarbeiter/Servicedienstleister ohne Motivation (Zufall, Fehler, Irrtum, falsche Handlung etc.)**
SL2: Mitarbeiter/Servicedienstleister mit Motivation
SL3: Hackerkollektiv (Cybercrime)
SL4: Hackerkollektiv (staatlich)
@snapend



+++?image=assets/img/blueprint.png&size=70%
@snap[north span-100 text-07 text-left]
## Secure Production Cell
### IEC 62443-3-3 SL1 konformer Blueprint
@snapend


@snap[south text-05 span-45 text-gray] 
@box[demo-box-pad]([eigene Darstellung])
@snapend






+++?image=assets/img/sr15.png&size=60%
@snap[north span-100 text-07 text-left]
## SL1 Readyness (SR 1.5)
### Verwaltung von Authentifikatoren 
@snapend



+++?image=assets/img/sr211.png&size=60%
@snap[north span-100 text-07 text-left]
## SL1 Readyness (SR 2.11)
### Zeitstempel
@snapend

+++?image=assets/img/sr31.png&size=60%
@snap[north span-100 text-07 text-left]
## SL1 Readyness (SR 3.1)
### Integrität der Kommunikation
@snapend

+++?image=assets/img/audit.png&size=80%
@snap[north span-100 text-07 text-left]
## SL1 Readyness
### Berichtsübersicht eines 62443-3-3 SL1 Assessments
@snapend

+++?image=assets/img/measures.png&size=65%
@snap[north span-100 text-07 text-left]
## Secure Production Measures
### Abgestimmte Massnahmen für die Integration
@snapend

note:
Allgemein: Für die Anlage wird vom Systemintegrator/AN die Konzeption der Industrial Security nach dem Security Level 1 der IEC 62443-3-3 angestrebt. Grundlage Zellenschutzkonzept
- SR 5.1 Network Segmentation
- SR 5.2 Zone Boundary Protection 
 
(1) Der einwandfreie Betrieb der Anlage muss gegeben sein, auch wenn keine Verbindungen zu den AG Data Center Anwendungssystemen besteht (=Automation Cell Offline Modus). 
- SR 7.2 Resource Management

(3) Es ist eine strikte Trennung von den Netzwerken Industrial Ethernet PN/IE und Profinet PN/IO vorzusehen. 
- SR 5.1 Network Segmentation
- SR 5.2 Zone Boundary Protection 
 
(4) Für Fernwartung, -diagnose, -Fehlerbehebung der vernetzten Gesamt- bzw. Einzelanlagen wird seitens AG ein VPN Zugang samt definierten Freigabeprozess nur für namentlich bekannte und genannte Servicetechniker des AN zur Verfügung gestellt. - VPN Lizenz wird seitens AG gestellt 
- SR 1.1 Human User Identification and Authentication
 
(5) aktuelle Firmwares verwenden - Projektiert wird mit stabilen TIA V15.1, jedoch Upgradefähigkeit von TIA, CPU, Firmware ist gegeben.
 
(6) Systemhärtung aller Geräte (SPS, HMI, Switches, etc) 
       Security Settings PLC  lt. Siemens Vorgabe
       Security Settings HMI  lt. Siemens Vorgabe, kein PC (einfach ;-) )
 
- SR 7.6 Network and Security Configuration Settings
- SR 7.7 Least Functionality
 
(7) Physikalische Schnittstellen (Ethernet, USB) vermeiden, ausg. Servicedosen im         
Schaltschrank
 
- SR 2.3 Use Control for Portable und Mobile Devices
- SR 2.4 Mobile Code
 
(8) Authentifizierung an Panel via Simatic Logon, Einrichtung durch AG
 
- SR 1.3 Account Management
- SR 1.7 Strength of Password-based Authentication
 
 
Der Datenaustausch mit den AG Data Center Shares z.B. Datensicherung ist nur über die Protokolle SMBv3 bzw. FTPS unter Einhaltung der Passwort Richtlinie möglich. Sollte Roboter kein FTPS,SFTP unterstützen sind Gateways in der Zelle bereitzustellen - Roboterprogramme Ablegen in gewisser Form --> gemeinsam sinnvolle Struktur. AG Data Share Center
 
 
(9) Datensicherung aller Devices, auch Stromquellen, ausgenommen Industriefirewall
- SR 7.3 System Backup
- SR 7.4 System Recovery 
 
(10) Alle Devices (Roboter, HMI, Switches, Controller, etc)  syncen mit Zeitserver
- SR 2.8 Auditable Events
- SR 2.11 Timestamps
 
Time SyncSystem should have a uniform system time and the possibility to synchronize this systemtime with an external time source
 
(11) Kommunikation HMI <-> Datafeed, MDE Server mittels OPC UA/TLS
- SR 3.1 Communication Integrity
- SR 4.3 Use of Cryptography
 
The communication between control device and enterprise application is secured by transport layer security protocols like OPC UA/TLS, mqtts for secure communication between enterprise application and control device. For secure file transmission smbv3, secure webdav and ftps could be used. For secure remote access RDP and ssh with TLS support could be to utilized. Not listed protocols eg. Rest API etc need a clearance and can be integrated with secure gateways or bridges





+++
@snap[north span-100 text-07 text-left]
## Zusammenfassung
@snapend

@snap[east text-06 span-49] 
@box[bg-green text-white demo-box-pad](Secure Production Cell Template)
@box[bg-white]()
@box[bg-gray text-white demo-box-pad](SL1 Readyness)
@box[bg-white]()
@box[bg-green text-white demo-box-pad](SL3 --> Data Center/Cloud Services)
@snapend

@snap[west text-06 span-50] 
@box[bg-gray text-white demo-box-pad](Ransomware vs Produktion)
@box[bg-white]()
@box[bg-green text-white demo-box-pad](Best Practice IEC 62443)
@box[bg-white]()
@box[bg-gray text-white demo-box-pad](Strategie - System Design - Operations )
@snapend

+++
@snap[north span-100 text-04 text-left]
## [BONUS] Buchempfehung
### Guideline Industrial Security: IEC 62443 is easy
### Pierre Kobes 2017

**ISBN-13:** 978-3800743384
**Herausgeber:** VDE VERLAG GmbH; Neuerscheinung Edition (25. Juli 2017)
![Kobes](assets/img/kobes.jpg)
@snapend


+++
@snap[north span-100 text-04 text-left]
## [BONUS] Foundational u. System Requirements
### nach IEC 62443-1-1 und 62443-3-3


**/IAC/** Identifizierung und Authentifizierung
**/UC /** Nutzungskontrolle (use control)
**/SI /** Systemintegrität 
**/DC /** Vertraulichkeit der Daten (data confidentiality)
**/RDF/** Eingeschränkter Datenfluss (RDF, restricted data flow)
**/TRE/** Rechtzeitige Reaktion auf Ereignisse (timely response to events)
**/RA /** Verfügbarkeit der Ressourcen (resource availability)
@snapend

@snap[south text-04 span-100 text-gray] 
![Logo](assets/img/fr.png)
@box[demo-box-pad](entnommen aus Guideline Industrial Security, Pierre Kobes 2017)
@snapend

+++
@snap[north span-100 text-04 text-left]
## [BONUS] Charter of Trust 
### zwischen Gesellschaft, Politik und Geschäftspartner.
@snapend

@snap[west span-45 text-05 text-left text-gray]
@quote[Die Daten von Einzelnen und Unternehmen zu schützen]
@quote[Menschen, Unternehmen und Infrastrukturen vor Schaden zu bewahren]
@quote[Ein zuverlässiges Fundament zu schaffen, auf dem das Vertrauen in eine vernetzte digitale Welt verankert ist und wachsen kann]
@snapend

@snap[east text-05 span-55 text-gray] 
![Logo](assets/img/charter-of-trust.svg)
@box[demo-box-pad](entnommen aus https://assets.new.siemens.com/siemens/assets/api/uuid:9bbe02e9-fcb2-4948-9977-a668cac52e50/version:1567432347/charter-of-trust-presentation-en-20190902-website.pdf) 
@snapend

@snap[south-west text-05 text-gray span-100]
### Cyber Security Alliance
 **SIEMENS**, NXP, MITSUBISHI, IBM, MSC, AES, AIRBUS, ALLIANZ, ATOS, CISCO, DAIMLER, DELL, T-SYTEMS, SGS, TOTAL, TÜV SÜD & more
@box[demo-box-pad](https://new.siemens.com/global/en/company/topic-areas/cybersecurity.html)
@snapend














