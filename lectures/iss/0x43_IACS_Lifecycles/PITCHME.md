+++?image=assets/img/lifecycle.svg&size=70%

@snap[north span-100 text-left text-07]
### Lifecycle
@snapend

@snap[south text-05 docslink]
@box[bg-gray text-white demo-box-pad](entnommen aus Guideline Industrial Security, Pierre Kobes 2017)
@snapend

note:

Hersteller
- Komponenten und Systeme anbieten die frei von Schwachstellen sind und erfüllen die Sicherheitsanforderungen der Zielmärkte.
- Die Produktlebenszyklen sind unabhängig von IACS-Lebenszyklen.
- Organisation des Herstellers richtet  einen Produktentwicklungsprozess ein, dadurch Vermeiden der Entstehung von Schwachstellen systematisch
- Qualität der Produkte zu verbessern, indem sicherheitsspezifische Maßnahmen in den Entwicklungsprozess einbezogen werden.
- ausführliche Dokumentation zur Verbesserung der Sicherheit bei der Integration des Produkts in Automatisierungslösungen enthalten, einschließlich Härtungsrichtlinien.
- professionelles Behandeln von Vorfällen, bei denen bei der Kommerzialisierung des Produkts Schwachstellen entdeckt werden, einschließlich Updates und Patch-Management.
- Gemäß IEC 62443-4-1 muss der Produktlieferant das Produkt während seiner gesamten Lebensdauer unterstützen.

Spezifikation, Design, Implementierung, das Testen, Kommerzialisierung, Freigabe und Wartung und schließlich dem Ausstieg aus dem Markt. 

Das Beispiel eines Sicherheitspatches des Betriebssystems verdeutlicht die Abhängigkeiten zwischen den Prozessen der beteiligten Parteien. Der Anbieter von Anwendungssoftware, die unter einem bestimmten Betriebssystem ausgeführt wird, muss überprüfen, ob die Software ordnungsgemäß ausgeführt wird, wenn eine aktualisierte Version des Betriebssystems veröffentlicht wird. 

In vielen Fällen müssen mehrere Versionen der Anwendungssoftware getestet und diese Kompatibilitätsinformationen veröffentlicht werden. Die nächste Rolle in diesem Prozess ist der Systemintegrator, der überprüfen muss, ob der Sicherheitspatch für die Automatisierungslösung relevant ist, für die der Integrator verantwortlich ist, und Richtlinien für die Bereitstellung des Patches festlegen muss. 

Schließlich muss der Eigentümer des Assets festlegen, wann der Patch in Abhängigkeit von den Betriebsbedingungen der Produktion oder des Prozesses auf die Automatisierungslösung angewendet werden kann. Eine typische Situation ist, dass Patches nur während der nächsten geplanten Wartungsphase angewendet werden können.

IACS-Lebenszyklen
Eine allgemein akzeptierte Strukturierung des IACS-Lebenszyklus besteht darin, ihn in die Phasen Spezifikation, Integration / Inbetriebnahme, Betrieb / Wartung und Außerbetriebnahme zu unterteilen. 

**Hauptverantwortlicher** Stakeholder ist der Betreiber, der eine Anforderungsspezifikation erstellen muss, die die Risiken und strategischen Ziele seiner Organisation berücksichtigt.

physische Umgebung, IT Sicherheitsrichtlinien --> Kritikalität IEC 62443-2-1  -- IEC 27001 [2] und 27002


