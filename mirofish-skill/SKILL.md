---
name: mirofish-sim
description: >
  Swarm-Intelligence-Simulation nach MiroFish-Paradigma: Multi-Agenten-Welten aus Seed-Material
  aufbauen, emergentes Verhalten simulieren, Prognoseberichte generieren. IMMER verwenden bei:
  Simulation, Prognose, Vorhersage, Szenarienplanung, Was-wäre-wenn, Zukunftsszenario,
  Schwarmintelligenz, Multi-Agenten-Simulation, Social Simulation, Sentiment-Prognose,
  Policy Rehearsal, Krisenprojektion, Stakeholder-Verhalten vorhersagen, Impact Assessment,
  Marktentwicklung simulieren, Romanende vorhersagen, Plot simulieren. Auch bei: "simuliere
  die Reaktion auf...", "was passiert wenn...", "prognostiziere...", "Szenario durchspielen",
  "Planspiel", "Agenten-Simulation", "MiroFish", "Predictive World", "GraphRAG Simulation".
---

# MiroFish Swarm Intelligence Simulation Skill

## Konzept

Dieser Skill implementiert das **MiroFish-Paradigma**: Aus Seed-Informationen (Nachrichten, Policy-Entwürfe, Finanzsignale, Romanfragmente, Strategiedokumente) wird ein hochauflösendes digitales Paralleluniversum konstruiert. Tausende autonome Agenten mit individueller Persönlichkeit, Langzeitgedächtnis und Verhaltenslogik interagieren frei. Durch gezielte Variablen-Injektion ("Gottesperspektive") lassen sich Zukunftsverläufe präzise durchspielen.

**Kernprinzip**: Nicht Daten extrapolieren, sondern emergentes Verhalten aus Agenteninteraktionen ableiten — Schwarmintelligenz statt statistischer Regression.

---

## 5-Phasen-Workflow

### Phase 1: Graphkonstruktion (Seed → Knowledge Graph)

**Input**: Seed-Material des Nutzers (Text, Daten, Links, Dokumente)

**Schritte**:
1. Entitäten extrahieren: Personen, Organisationen, Orte, Konzepte, Ereignisse
2. Beziehungen identifizieren: Macht, Einfluss, Abhängigkeit, Konflikt, Kooperation
3. Zeitliche Dimension: Chronologie der Ereignisse, kausale Ketten
4. Kontextuelles Wissen: Hintergrund, Normen, kulturelle Faktoren
5. GraphRAG-Struktur aufbauen: Entitäten als Knoten, Beziehungen als Kanten, Attribute als Properties

**Output-Format** (Markdown-Tabelle oder strukturiertes JSON):
```
WISSENSGRAPH:
- Entitäten: [Liste mit Typ, Rolle, Attribute]
- Beziehungen: [Quelle → Ziel, Typ, Stärke, Richtung]
- Kontext-Layer: [Regulatorisch, Kulturell, Technologisch, Ökonomisch]
- Zeitachse: [Chronologische Meilensteine]
```

### Phase 2: Umgebungsaufbau (Agenten & Parameter)

**Schritte**:
1. Agenten-Personas generieren basierend auf extrahierten Entitäten
2. Jedem Agenten zuweisen:
   - **Persönlichkeitsprofil**: Werte, Motivation, Risikoaffinität, Kommunikationsstil
   - **Wissensstand**: Was weiß der Agent, was nicht
   - **Gedächtnis**: Bisherige Erfahrungen, Prägungen
   - **Verhaltensregeln**: Reaktionsmuster, Entscheidungslogik
   - **Soziale Position**: Einfluss, Netzwerk, Reputation
3. Simulationsparameter definieren:
   - Zeitrahmen & Granularität (Stunden/Tage/Wochen)
   - Kommunikationskanäle (öffentlich, bilateral, Gruppen)
   - Externe Schocks / Variablen-Injektionen
   - Abbruchkriterien / Konvergenzmetriken

**Output-Format**:
```
AGENTEN-REGISTER:
Agent [ID]: [Name/Rolle]
  Profil: [Kurzcharakterisierung]
  Motivation: [Primär/Sekundär]
  Einfluss: [1-10]
  Netzwerk: [Verbundene Agenten]
  Wissenslücken: [Was fehlt]

SIMULATIONSPARAMETER:
  Zeitrahmen: [Start → Ende, Schrittweite]
  Injektionspunkte: [Geplante Variablen]
  Beobachtungsmetriken: [KPIs der Simulation]
```

### Phase 3: Simulation (Interaktion & Emergenz)

**Schritte**:
1. Initiale Runde: Agenten reagieren auf Seed-Situation
2. Folgerunden: Agenten reagieren aufeinander (Kettenreaktion)
3. Pro Runde dokumentieren:
   - Wer kommuniziert mit wem
   - Welche Positionen verschieben sich
   - Welche Allianzen/Konflikte entstehen
   - Welche Information verbreitet sich wie schnell
4. Variablen-Injektion an definierten Punkten
5. Emergente Muster identifizieren:
   - Tipping Points
   - Kaskadeneffekte
   - Polarisierung/Konsensbildung
   - Unerwartete Koalitionen

**Output-Format** (pro Simulationsrunde):
```
RUNDE [N] — [Zeitpunkt]
  Schlüsselinteraktionen:
    [Agent A] → [Agent B]: [Aktion/Aussage] → Effekt: [Reaktion]
  Emergente Muster: [Beobachtung]
  Stimmungsverlauf: [Aggregiert]
  Überraschungen: [Unerwartete Entwicklungen]
```

### Phase 4: Berichterstellung (ReportAgent)

**Schritte**:
1. Simulationsergebnisse konsolidieren
2. Prognose in Szenarien destillieren:
   - **Basisszenario** (wahrscheinlichster Verlauf, ~60% Konfidenz)
   - **Optimistisches Szenario** (günstige Wendungen, ~20%)
   - **Pessimistisches Szenario** (Eskalation/Worst Case, ~20%)
3. Tipping Points & Entscheidungsknoten herausarbeiten
4. Handlungsempfehlungen ableiten
5. Unsicherheiten und Modellgrenzen benennen

**Output-Format**:
```
PROGNOSE-BERICHT: [Titel]

1. EXECUTIVE SUMMARY
   [3-5 Sätze Kernaussage]

2. SEED-ANALYSE
   [Ausgangslage, Schlüsselakteure, initiale Dynamik]

3. SIMULATIONSERGEBNISSE
   3.1 Basisszenario: [Beschreibung, Wahrscheinlichkeit, Zeitverlauf]
   3.2 Optimistisches Szenario: [Beschreibung, Auslöser]
   3.3 Pessimistisches Szenario: [Beschreibung, Risikofaktoren]

4. TIPPING POINTS
   [Kritische Entscheidungsmomente mit Hebel-Wirkung]

5. HANDLUNGSEMPFEHLUNGEN
   [Konkrete Maßnahmen pro Szenario]

6. MODELLGRENZEN & UNSICHERHEITEN
   [Wo die Simulation an Grenzen stößt]

7. AGENTEN-INSIGHTS
   [Überraschende Erkenntnisse aus Agentenverhalten]
```

### Phase 5: Deep Interaction (Dialog mit der Simulationswelt)

Nach Berichterstellung bietet der Skill dem Nutzer an:
- **Mit einzelnen Agenten sprechen**: Perspektive eines Stakeholders einnehmen
- **Variablen nachinjizieren**: "Was passiert, wenn jetzt [X] eintritt?"
- **Zeitachse verschieben**: Simulation ab einem anderen Punkt fortsetzen
- **Gegenprobe**: Annahmen hinterfragen, alternative Seeds testen

---

## Anwendungsszenarien

### Enterprise / KRITIS
- Policy-Impact-Assessment vor Veröffentlichung
- Krisenreaktion simulieren (PR-Desaster, Regulierung, Cyberangriff)
- Stakeholder-Reaktionen auf Strategiewechsel vorhersagen
- M&A-Szenarien: Marktreaktion auf Übernahme

### Public Opinion / Sentiment
- Medienreaktionen auf Pressemitteilungen simulieren
- Social-Media-Sturm vorhersagen und Gegenmaßnahmen testen
- Wahlkampf-Szenarien durchspielen

### Kreativ / Narrativ
- Romanenden vorhersagen / alternative Verläufe generieren
- Charakter-Interaktionen simulieren für Storyentwicklung
- Historische Was-wäre-wenn-Szenarien

### Finanz / Markt
- Marktreaktion auf regulatorische Änderungen simulieren
- Investor-Sentiment bei verschiedenen Nachrichten-Szenarien
- Wettbewerbsdynamik modellieren

---

## Qualitätsprinzipien

1. **Emergenz vor Extrapolation**: Ergebnisse entstehen aus Agenteninteraktionen, nicht aus linearer Fortschreibung
2. **Transparente Unsicherheit**: Jede Prognose benennt Konfidenz, Annahmen und blinde Flecken
3. **Falsifizierbare Szenarien**: Jedes Szenario enthält konkrete Indikatoren, an denen seine Eintrittwahrscheinlichkeit messbar wird
4. **Adversariales Denken**: Mindestens ein Agent vertritt systematisch Gegenposition
5. **Gedächtniskonsistenz**: Agenten widersprechen sich nicht selbst über Runden hinweg
6. **Keine Pseudo-Präzision**: Keine falschen Prozentzahlen ohne Begründung, Bandbreiten statt Punktschätzungen

---

## Workflow-Steuerung

Wenn der Nutzer einen Simulations-Auftrag gibt:

1. **Seed prüfen**: Ist genug Material vorhanden? Falls nicht → gezielt nachfragen
2. **Scope klären**: Makro (Gesellschaft/Markt) oder Mikro (Team/Individuum)? Zeitrahmen?
3. **Phase 1-4 sequenziell durchlaufen**, Output pro Phase zeigen
4. **Phase 5 anbieten**: "Willst du mit einem Agenten sprechen oder eine Variable injizieren?"

Bei kurzen/informellen Anfragen ("Was passiert wenn...") → komprimierter Durchlauf: Direkter Mini-Graph → 3-5 Agenten → 3 Runden → Kurzprognose mit Szenarien.

Bei umfangreichen Anfragen → voller 5-Phasen-Workflow mit detailliertem Output pro Phase.

---

## Sprachregeln

- Deutsch als Default (Skill-Nutzer: Mark Zimmermann, deutschsprachiger Enterprise-Kontext)
- Englisch wenn Seed-Material englisch ist oder Nutzer auf Englisch fragt
- Keine Weichmacher, keine Motivationslyrik — direkte Aussagen
- Prognosen als Szenarien, nie als Gewissheiten

---

## Attribution

Inspiriert durch das MiroFish-Projekt (github.com/666ghj/MiroFish, AGPL-3.0).
Kein Code aus MiroFish übernommen. Eigenständige Methodik-Implementierung.
