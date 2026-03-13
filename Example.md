# Das agentische Betriebssystem: Was bis 2030 passiert

*Eine Prognose auf Basis einer MiroFish-Schwarmintelligenz-Simulation mit 8 autonomen Agenten, 10 Simulationsrunden und einer 4-Jahres-Projektion.*

Google hat im Februar 2026 mit dem „Intelligent OS" das App-Modell der letzten 15 Jahre in Frage gestellt. Nicht auf einer Folie, sondern als konkrete Plattformarchitektur für Android. Die Frage ist: Was passiert, wenn KI-Agenten die Bedienoberfläche ersetzen? Nicht als Gedankenexperiment, sondern im Alltag von Milliarden Nutzern?

Ich habe diese Frage durch eine Simulation geschickt. Acht Agenten mit eigenen Motivationen, Wissenslücken und Netzwerken. Fünf Variablen-Injektionen. Zehn Runden über vier Jahre. Das Ergebnis ist weder Googles Maximalvision noch der Skeptiker-Worst-Case. Es ist komplizierter. Und ehrlich gesagt interessanter.

## Die Ausgangslage

Google bringt zwei Mechanismen gleichzeitig: AppFunctions (Entwickler deklarieren, was ein Agent aufrufen darf) und UI-Automation (der Agent bedient die App selbst, ohne Zutun des Entwicklers). Das Erste gibt Kontrolle. Das Zweite nimmt sie. Beides zusammen erzeugt asymmetrischen Druck auf jeden App-Entwickler weltweit.

Samsung zeigt das bereits auf dem Galaxy S26. Wer Gemini bittet, Katzenfotos zu zeigen, bekommt sie in Gemini angezeigt. Die Galerie-App wird nie geöffnet. Der Nutzer merkt es nicht. Der Entwickler schon.

## Die acht Agenten

Die Simulation bildet nicht „die Branche" ab, sondern konkrete Akteure mit widersprüchlichen Interessen:

Ein VP Product bei einem großen Lieferdienst, der sofort ein 8-köpfiges Team auf AppFunctions ansetzt, weil er weiß: Wenn sein Dienst nicht die beste Agent-Anbindung hat, empfiehlt Gemini den Wettbewerber.

Eine Indie-Entwicklerin mit einem 3-Personen-Startup, die die AppFunctions-Dokumentation liest und feststellt: 3 bis 4 Personenwochen Aufwand. Für sie ist das existenzbedrohend.

Ein Google Developer Relations Lead, der die neue Architektur mit Charm-Offensive und Codelabs verkauft. Sein Narrativ: „Wir geben euch mehr Reichweite, nicht weniger." Ob das stimmt, zeigt die Simulation.

Eine DG-COMP-Juristin in Brüssel, die nach Präzedenzfällen sucht. Wenn Gemini entscheidet, welche App eine Aufgabe erledigt, ist das Self-Preferencing nach DMA?

Eine Privacy-Aktivistin aus dem Noyb-Umfeld, die den Test-Case will. Agent bestellt autonom Essen, wählt falsch, jemand hat eine Allergie. Art. 22 DSGVO, automatisierte Entscheidung. Klingt abstrakt, bis es jemandem passiert.

Dazu Samsung, die IPCC-Welt (als Proxy für institutionelle Beobachter), ein ESA-Navigationsingenieur. Und 50.000 simulierte Endanwender, aufgeteilt in Early Adopter, Mainstream, Skeptiker und Enterprise-Nutzer.

## 2026: Der Schock und der erste Unfall

Die erste Runde verläuft wie erwartet. Tier-1-Unternehmen investieren sofort. Indie-Entwickler fallen zurück. Die Schere öffnet sich nicht langsam, sie reißt auf. In der Entwickler-Community kursiert ein Satz: „Google just told 90% of Android devs: your UI doesn't matter anymore." 12.000 Reposts.

Dann kommt die WWDC im Juni. Apple stellt seine Antwort vor: Agent-Fähigkeiten, aber mit Bestätigung für jeden Schritt. Privacy-First. Kein autonomes Agieren in fremden Apps. Die Botschaft an die Branche: Agentische KI geht auch ohne Kontrollverlust. Das ist der Moment, in dem die Debatte ihr Framing bekommt. Nicht „Agent ja oder nein", sondern „Agent mit oder ohne Kontrolle".

Dann, im Sommer: der unvermeidliche Unfall. In der Simulation bestellt ein Gemini-Agent für eine Familie mit Erdnussallergie ein Gericht mit Erdnüssen. Virales TikTok-Video. 28 Millionen Views. Die Mutter sagt: „I trusted the AI to order for my family."

Der Vorfall ist technisch lösbar. Google fügt Allergen-Bestätigungsflows ein. Aber die Haftungsfrage kristallisiert sich an diesem Moment, und sie hat keine Antwort. Wer ist verantwortlich, wenn ein Agent in einer Drittanbieter-App einen Fehler macht? Google sagt: Die App hat das Allergen nicht getaggt. Die App sagt: Der Agent hat die Nutzernotiz ignoriert. Juristische Grauzone, und zwar eine, die Adoption bremst.

Die Skeptiker-Fraktion unter den Endanwendern wächst von 20 auf 34 Prozent. Das Mainstream-Segment schiebt seine Adoption um Monate auf.

## 2027: Brüssel greift ein

Die EU-Kommission eröffnet eine formale DMA-Voruntersuchung. Zwei Hebel: Art. 6(5), Selbstbevorzugung, und Art. 6(3), Interoperabilität. Die Kernfrage: Muss Google die Agent-Infrastruktur für Drittagenten öffnen?

Wenn ja, ist das der größte strukturelle Eingriff in eine mobile Plattform seit der Browser-Choice-Entscheidung gegen Microsoft 2009.

Google reagiert proaktiv mit einem „Agent Choice Screen". Bei der Ersteinrichtung wählt der Nutzer seinen bevorzugten Agenten. Das Ergebnis in der Simulation: 73 Prozent wählen Gemini (Bekanntheit), 14 Prozent wählen „Keinen Agent" (Opt-out), der Rest verteilt sich. Der Choice Screen ist ein regulatorischer Erfolg und ein UX-Fiasko zugleich. Die meisten Nutzer sind überfordert von einer Wahl, die sie nicht verstehen.

Was die Simulation hier zeigt: Eine paradoxe Allianz entsteht. Große App-Anbieter und Indie-Entwickler kämpfen gemeinsam für Multi-Agent-Interoperabilität, aber aus völlig verschiedenen Gründen. Die Großen wollen Verhandlungsmacht. Die Kleinen wollen überleben. Das Ergebnis wäre dasselbe.

Samsung erkennt die Chance schneller als erwartet und kündigt einen eigenen „Galaxy Agent Hub" an. Nutzer wählen dort zwischen Gemini, Samsungs eigenem Agent und Drittagenten. Die Machtverschiebung geht nicht von Google zu den Nutzern, sondern von Google zu den OEMs.

Ende 2027: 28 Prozent der Android-Nutzer nutzen Agent-Funktionen regelmäßig.

## 2028: Ein Standard entsteht

Google und Anthropic kündigen gemeinsam das „Universal Agent Protocol" (UAP) an. AppFunctions und MCP verschmelzen zu einem offenen Standard. W3C-Submission geplant.

Das ist der Moment, in dem aus einem Google-Feature ein Infrastrukturprotokoll wird. Vergleichbar mit der Rolle von HTTP für das Web. Niemand redet darüber, aber alles läuft darüber.

Die erste „UI-less App" erreicht nennenswerte Nutzerzahlen: ein InsurTech-Startup mit 340.000 Kunden, das ausschließlich über Agent-Interaktion Policen abschließt. Keine Oberfläche, kein Screen, kein Icon. Nur eine Capability im UAP-Ökosystem. Proof of Concept für die Post-UI-These, zumindest für transaktionale Dienste.

Die Indie-Entwicklerin aus der Simulation profitiert paradoxerweise. Ein Open-Source-SDK senkt den Agent-Integrationsaufwand von 4 Wochen auf 2 Tage. Ihre Nische, handkuratierte lokale Restaurantdaten, wird von Agenten bevorzugt, weil die Datenqualität stimmt. Zum ersten Mal schlägt Nische Skala.

34 Prozent regelmäßige Agent-Nutzung. Aber 80 Prozent der Agent-Interaktionen entfallen auf fünf Kategorien: Essen bestellen, Fahrten buchen, Kalender, Nachbestellungen, Schnellsuche. Alles andere bleibt beim Menschen.

## 2029: Enterprise wacht auf

Bis hierhin haben KRITIS-Unternehmen, Banken und das Gesundheitswesen agentische App-Steuerung auf Firmengeräten blockiert. Jetzt wird der Effizienzdruck zu groß. Eine Studie beziffert die Zeitersparnis bei Agent-gestützten mobilen Workflows auf 41 Prozent in Logistik und Facility Management. CIOs sagen nicht mehr Nein.

Aber Enterprise-Agenten laufen nicht auf Gemini. Sie laufen auf privaten Agent-Instanzen hinter Zero-Trust-Perimetern. UAP macht das möglich: dasselbe Protokoll, kontrollierte Umgebung. Es entsteht eine Zwei-Klassen-Architektur. Consumer-Agenten sind bequem, aber intransparent. Enterprise-Agenten sind kontrolliert, aber aufwändig.

Die Privacy-Front öffnet ein neues Feld: Agent-Profiling. Agenten lernen aus Nutzerverhalten und bilden implizite Profile. In der Simulation formuliert die Privacy-Aktivistin eine Beschwerde, die es auf den Punkt bringt: „Gemini weiß aus meinem Bestellverhalten, dass ich schwanger bin, bevor ich es meiner Familie gesagt habe." Abgeleitete Gesundheitsdaten, DSGVO Art. 9. Ungelöst.

42 Prozent regelmäßige Nutzung. Gen Alpha, die erste Smartphone-Generation mit Agenten, kennt keine Welt ohne sie. „Eine App öffnen" klingt für sie so antiquiert wie „eine Telefonnummer wählen" für Millennials.

## 2030: Die neue Normalität

51 Prozent der Nutzer interagieren regelmäßig mit Agenten. Der Tipping Point ist überschritten. Aber „regelmäßig" heißt nicht „für alles". Das Hybrid-Modell hat sich verfestigt, und es sieht nicht nach einem Übergang aus. Es sieht nach einem Endzustand aus.

Was Agenten machen: Essen bestellen, Fahrten, Nachbestellungen, Termine, Routinetransaktionen, Smart-Home-Steuerung. Alles, was Wiederholung ohne Urteilsvermögen erfordert.

Was Menschen machen: Social Media browsen, Fotos bearbeiten, spielen, komplexe Konfigurationen, Finanzplanung, Gesundheitsmanagement. Alles, wo Entdeckung, Kreativität oder Kontrolle zählt.

Die Grauzone dazwischen: Shopping (Agent für die Nachbestellung, menschlich für die Entdeckung), Reisen (Agent für Standardrouten, menschlich für Planung), Kommunikation (Agent für Schnellantworten, menschlich für alles, was zählt).

2.300 Apps existieren ohne klassische Oberfläche. 90 Prozent davon sind transaktionale Dienste. Die These „Apps sterben" ist falsch. Die These „Oberflächen werden optional" ist für eine Teilmenge wahr geworden.

Die größte Überraschung: Die Indie-Entwicklerin hat überlebt. Mehr als das: Ihr Unternehmen ist auf 11 Personen gewachsen. Ihr Geschäftsmodell hat sich gedreht, von „App mit Oberfläche" zu „lokale Daten-Kuratierung als Capability". Agenten bevorzugen ihre Daten, weil sie qualitätsgeprüft und lokal verifiziert sind. Die App existiert noch, hat aber den Charakter einer Visitenkarte.

Der VP Product beim Lieferdienst sieht, dass 60 Prozent seines Umsatzes über Agent-Kanäle kommen. Nutzer sagen „ich hab über Gemini bestellt", nicht „ich hab bei Lieferando bestellt". Die Marke löst sich von der Oberfläche und existiert als „Agent Reputation Score", ein Rating, das Agenten bei der Auswahl berücksichtigen.

## Was die Simulation wirklich zeigt

Drei Erkenntnisse, die mich beschäftigen.

Erstens: Der Indie-Entwickler wird zum Schlüsselakteur. Nicht durch Macht, sondern durch Narrativ. „Kleine Entwicklerin gegen Big Tech" bewegt Regulierer stärker als jede technische Analyse. Ohne die Indie-Stimme hätte die DMA-Untersuchung ein anderes Tempo gehabt.

Zweitens: Ein einzelner Vorfall, der Allergie-Fall, bremst die Adoption um Monate und zieht regulatorische Aufmerksamkeit an, die Google über Jahre beschäftigt. Die Asymmetrie zwischen Aufbau (Monate) und Zerstörung (Sekunden) von Vertrauen ist der zentrale Risikofaktor der agentischen Ära. Das unterschätzt jeder, der Adoptionskurven extrapoliert.

Drittens, und das ist der wichtigste Punkt: Die Disruption ist nicht technisch, sie ist ökonomisch. Die Technologie steht bereit. Governance steht nicht bereit. Die nächsten vier Jahre werden weniger von Code bestimmt als von Regulierung, Haftungsrecht und Machtverhandlungen zwischen Plattformen, Entwicklern und Staaten. Wer den Agenten kontrolliert, kontrolliert den Zugang zum Kunden. Das ist die eigentliche Frage, und sie ist 2030 nicht beantwortet.

## Die Adoption im Zeitverlauf

| Jahr | Regelmäßige Nutzung | Was passiert |
|------|---------------------|--------------|
| 2026 H1 | 8 % | Architektur-Schock, Entwickler-Ökosystem spaltet sich |
| 2026 H2 | 18 % | Allergie-Vorfall, Vertrauenskrise, DMA-Voruntersuchung |
| 2027 | 28 % | Agent Choice Screen, Samsung Agent Hub, paradoxe Allianz |
| 2028 | 34 % | UAP-Standard, erste UI-less App, Indie-Recovery |
| 2029 | 42 % | Enterprise-Welle, AI Act Enforcement, Agent-Profiling |
| 2030 | 51 % | Hybrid-Modell als Endzustand, Agent Neutrality-Debatte |

Die Adoption folgt keiner S-Kurve. Sie folgt einer Treppenfunktion: Sprünge bei Schlüsselereignissen, Plateaus dazwischen. Der Endzustand ist kein „Agent für alles", sondern ein stabiles Hybrid-Modell mit klarer Domänentrennung.

## Was die Simulation nicht abbildet

Ein technologischer Bruch. Zum Beispiel ein On-Device-Modell, das so gut wird, dass es ohne AppFunctions und ohne UAP direkt aus Pixeln Aktionen ableitet. Das würde den gesamten Standardisierungsaufwand obsolet machen. Oder ein geopolitischer Bruch: China setzt einen eigenen Agent-Standard, der nicht kompatibel ist. Dann fragmentiert nicht nur die App-Welt, sondern die Agent-Welt.

Und: Die Simulation unterstellt Akteure mit konsistenten Strategien. Reale Plattformkonzerne ändern ihren Kurs abrupt. Apple könnte radikaler antworten als modelliert. Oder gar nicht. Regulatorische Timelines sind in der Simulation optimistisch. EU-Verfahren brauchen in der Realität 18 bis 36 Monate, nicht 6 bis 12.

Trotzdem: Die Richtung stimmt. Nicht weil die Simulation die Zukunft kennt, sondern weil die Agenteninteraktionen Muster erzeugen, die in der linearen Analyse unsichtbar bleiben. Die paradoxe Allianz zwischen Indie und Tier-1, die Machtverschiebung zu OEMs statt zu Nutzern, der disproportionale Effekt eines einzelnen Unfalls. Das sind emergente Ergebnisse. Kein Analyst hätte sie so vorhergesagt, und kein Modell garantiert, dass sie so eintreten. Aber sie sind plausibel. Und sie sind es wert, durchdacht zu werden.
