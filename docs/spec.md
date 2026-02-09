# Agentische KI – Vom Chatbot zum digitalen Team  
**Textbasierte Spezifikation für Podcast, Demo & Begleitmaterial**

## 1. Ziel des Vorhabens

Ziel dieser Session ist es, das Konzept der *agentischen Künstlichen Intelligenz* für eine **nicht-technische Zielgruppe** verständlich, greifbar und erlebbar zu machen.

Die Zielgruppe umfasst insbesondere:
- Personen am Anfang einer Berufsausbildung
- Führungskräfte und Entscheidungsträger:innen ohne tiefen technischen Hintergrund

Der Fokus liegt **nicht** auf technischen Details, sondern auf:
- mentalen Modellen
- Rollenverständnis
- organisatorischen Analogien
- praktischer Einordnung für Arbeitswelt und Unternehmen

---

## 2. Didaktische Leitidee

> Agentische KI ist kein besserer Chatbot –  
> sondern ein digitales Team mit Rollen, Aufgaben und Verantwortung.

Das Konzept wird entlang eines **klaren Eskalationspfads** vermittelt:
1. Klassische KI
2. LLMs (Sprachmodelle)
3. Agenten
4. Multi-Agenten-Systeme
5. Agentische Organisation

Zusätzlich ordnet Abschnitt 4 die **Werkzeuge** ein: vom Browser über IDE und CLI bis zu lokalen Vollagenten (z. B. OpenClaw) – mit zunehmender Autonomie und zunehmenden Risiken.

---

## 3. Begriffsdefinitionen (zielgruppengerecht)

### 3.1 Künstliche Intelligenz (KI)

KI ist ein Sammelbegriff für Systeme, die Aufgaben übernehmen,  
für die normalerweise menschliche Intelligenz benötigt wird  
(z. B. Sprache verstehen, Entscheidungen treffen, Muster erkennen).

---

### 3.2 Large Language Models (LLMs)

Ein LLM ist ein KI-System, das Sprache sehr gut versteht und erzeugt.

Wichtige Eigenschaften:
- reagiert auf Eingaben
- hat kein eigenes Ziel
- handelt nicht selbstständig
- besitzt kein dauerhaftes Gedächtnis

**Analogie:**  
Ein sehr gut ausgebildeter Praktikant, der nur arbeitet, wenn man ihn direkt anspricht.

---

### 3.3 Agent

Ein Agent ist ein System, das:
- ein Ziel verfolgt
- Entscheidungen trifft
- eigenständig handelt
- Werkzeuge (z. B. LLMs, Suche, Dateien) nutzt

Ein Agent **nutzt** ein LLM – er **ist** kein LLM.

**Analogie:**  
Ein Mitarbeiter mit klarer Aufgabe.

---

### 3.4 Agentische KI

Agentische KI beschreibt Systeme, in denen:
- mehrere spezialisierte Agenten
- koordiniert
- auf ein gemeinsames Ziel hinarbeiten

**Analogie:**  
Ein Unternehmen mit Arbeitsteilung, Rollen und Kontrollmechanismen.

---

## 4. Landschaft agentischer KI-Tools: Autonomie und Risiken

Die Spezifikation folgt einer **klaren Erzählung**: vom allgemeinen Überblick über KI, LLM und agentische KI hin zu konkreten Werkzeugen – und zwar entlang eines **Eskalationspfads der Autonomie**. Mit jedem Schritt werden die Agenten mächtiger und eigenständiger, bis hin zu einem echten „Ersatz“ eines vollwertigen Mitarbeiters – verbunden mit zunehmenden Chancen, aber auch Risiken (z. B. Data Leaks, Abhängigkeit, Kontrollverlust).

### 4.1 Stufe 1: Agentische KI im Browser (Automatisierung)

**Beispiele:** Perplexity Comet, Atlas, vergleichbare Browser-basierte Assistenten

- Nutzung direkt im Browser, keine Installation.
- Fokus auf **Automatisierung** von Recherche, Zusammenfassung, Formulierung.
- Geringe Autonomie: Der Nutzer bleibt im Loop, Aktionen sind sichtbar und begrenzt.
- **Risiko:** Relativ gering, da Datenfluss und Kontext meist begrenzt und nachvollziehbar sind.

**Use Case:** Schnelle Recherche, Social-Media-Ideen, erste Entwürfe – „digitaler Praktikant im Browser“.

---

### 4.2 Stufe 2: Entwicklungsumgebungs- und IDE-basierte Agenten

**Beispiele:** Cursor, Google Antigravity (IDE-integrierte agentische Assistenten)

- Agent arbeitet **im Kontext von Code und Projektdateien**.
- Höhere Autonomie: Refaktorierung, Implementierung, Debugging über viele Dateien hinweg.
- Der Nutzer behält die Kontrolle durch IDE, Versionierung und explizite Freigabe.

**Risiken:** Zugriff auf Quellcode und ggf. Umgebung; Datenschutz und Lizenzfragen bei Cloud-Backends.

---

### 4.3 Stufe 3: CLI-basierte agentische KI

**Beispiele:** Gemini CLI, Claude Code (und vergleichbare Kommandozeilen-Tools)

- Agent führt **Aktionen in der Shell und im Dateisystem** aus (Skripte, Befehle, Dateien lesen/schreiben).
- Noch höhere Autonomie: Der Agent kann „handeln“, nicht nur antworten.
- Ideal für **rollenbasierte Demos** (z. B. Planer, Recherche, Budget, Qualität) wie in dieser Session.

**Risiken:** Fehlende Abschottung; ein fehlgeleiteter Befehl kann Systeme oder Daten beeinträchtigen.

---

### 4.4 Stufe 4: Lokale Agentensysteme (Desktop/Co-Pilot)

**Beispiele:** Claude Cowork und ähnliche lokale oder desktop-nahe Agenten

- Agent läuft **lokal oder in kontrollierter Umgebung**, mit Zugriff auf Anwendungen, Fenster, Kontext.
- Hohe Autonomie: Kann wie ein „Mitarbeiter am Schreibtisch“ agieren – Aufgaben übernehmen, zwischen Tools wechseln.
- Stärkere Illusion eines **vollwertigen digitalen Mitarbeiters**.

**Risiken:** Umfassender Zugriff auf lokale Daten und Anwendungen; Data Leaks und Compliance, wenn sensible Daten in den Kontext gelangen.

---

### 4.5 Stufe 5: Vollständig lokale, „full-blown“ agentische KI (OpenClaw u. Ä.)

**Beispiele:** OpenClaw und vergleichbare lokale Agentensysteme

- **Maximale Autonomie:** Modell und Agent laufen vollständig lokal; kein zwingender Datenabfluss nach extern.
- Der Agent kann als **vollwertiger Ersatz** für wiederkehrende und strukturierte Tätigkeiten gedacht werden – mit Zugriff auf Rechner, Netzwerk, Anwendungen.
- Gleichzeitig **höchstes Risikoprofil:** Fehlverhalten oder Kompromittierung betreffen direkt den Arbeitsplatz; Data Leaks, ungewollte Aktionen und Abhängigkeit von einem einzigen System nehmen zu.

**Didaktischer Punkt:** Hier wird die Erzählung „vom Chatbot zum digitalen Team“ zugespitzt: Ein solcher Agent ist kein Tool mehr, sondern ein **digitaler Kollege mit hoher Eigenständigkeit** – entsprechend sind Rollenklärung, Grenzen, Kontrolle und Risikobewusstsein zentral.

---

### 4.6 Zusammenfassung: Use Case und roter Faden

| Stufe | Typische Tools        | Autonomie     | Risiko (u. a. Data Leaks) |
|-------|------------------------|---------------|----------------------------|
| 1     | Browser (Comet, Atlas) | Gering        | Gering                     |
| 2     | IDE (Cursor, Antigravity) | Mittel    | Mittel                     |
| 3     | CLI (Gemini CLI, Claude Code) | Hoch  | Mittel–hoch                |
| 4     | Lokale Agenten (Claude Cowork) | Hoch  | Hoch                       |
| 5     | Lokal full-blown (OpenClaw)    | Sehr hoch | Sehr hoch              |

**Use Case dieser Session:** Die Zielgruppe erhält einen **einordnenden Überblick** (KI → LLM → Agent → Multi-Agent) und sieht anschließend, **wo** agentische KI heute eingesetzt wird – vom Browser bis zum lokalen Vollagenten. Die Demo mit CLI-Tools (Stufe 3) bleibt der zentrale, nachvollziehbare Anker; die Nennung von IDE- und lokalen Systemen bis OpenClaw schafft Orientierung und sensibilisiert für Autonomie und Risiken.

---

## 5. KI als Mitarbeiter

Vor ein paar Jahren hattest du einen Social-Media-Manager, der sich um die Social-Media-Accounts der Firma kümmerte. Er hatte eine klare Aufgabe:
- Social-Media-Posts erstellen
- Social-Media-Posts veröffentlichen
- Social-Media-Posts analysieren
- Social-Media-Posts optimieren
- Social-Media-Posts messen

Heute kann das ein Agent übernehmen. Logge dich ein und lass uns gemeinsam einen Social-Media-Post erstellen.

**Zusammenspiel:** Der Agent und agentische KI im Browser (z. B. Perplexity Comet, Atlas) zeigen die **erste Stufe** der Tool-Landschaft (Abschnitt 4.1) – Automatisierung mit geringer Autonomie und überschaubarem Risiko.

---

## 6. Demonstrationsszenario

### 6.1 Szenario: Geschäftsreiseplanung

Ein agentisches System plant eine dreitägige Geschäftsreise nach Berlin.

Das System soll:
- Reiseoptionen recherchieren
- Kosten kalkulieren
- Plausibilität prüfen
- Ergebnisse verständlich aufbereiten

Dieses Szenario ist bewusst gewählt, da es:
- alltagsnah ist
- keine Fachkenntnisse erfordert
- typische Büro- und Managementprozesse widerspiegelt

---

## 7. Multi-Agenten-Architektur

### 7.1 Gesamtziel

> Erstelle einen vollständigen, realistischen und verständlichen Reiseplan  
> inklusive Kostenübersicht und Management-Zusammenfassung.

---

### 7.2 Agentenrollen

#### Agent 1 – Planungs- & Koordinationsagent
**Rolle:** Projektleitung  
**Aufgaben:**
- Ziel verstehen
- Teilaufgaben definieren
- andere Agenten beauftragen
- Ergebnisse zusammenführen

---

#### Agent 2 – Rechercheagent
**Rolle:** Assistenz / Sachbearbeitung  
**Aufgaben:**
- Anreiseoptionen (Zug/Flug)
- Hotelvorschläge
- grobe Preisrahmen

---

#### Agent 3 – Budget- & Kostenagent
**Rolle:** Controlling  
**Aufgaben:**
- Gesamtkosten berechnen
- Alternativen vergleichen
- Budgetgrenzen beachten

---

#### Agent 4 – Qualitäts- & Plausibilitätsagent
**Rolle:** Qualitätssicherung  
**Aufgaben:**
- Zeitpläne prüfen
- Widersprüche erkennen
- unrealistische Annahmen markieren

---

#### Agent 5 – Ergebnis- & Kommunikationsagent
**Rolle:** Management-Kommunikation  
**Aufgaben:**
- Ergebnisse zusammenfassen
- verständliche Darstellung
- Entscheidungsvorlage erstellen

---

## 8. Technische Demonstration (CLI-basiert)

### 8.1 Ziel der Demo

- Live zeigen, dass Agenten **rollenbasiert arbeiten**
- Keine Programmierung erforderlich
- Fokus auf Denkweise statt Technik

---

### 8.2 Werkzeuge

Mögliche Tools (entsprechend **Stufe 3** der Tool-Landschaft, Abschnitt 4.3):
- Gemini CLI
- Claude Code

Beide ermöglichen:
- rollenbasierte Prompts
- iterative Zusammenarbeit
- sichtbare Agenteninteraktion

---

### 8.3 Prinzip der Umsetzung

- Jeder Agent erhält:
  - eine Rolle
  - ein Ziel
  - klare Verantwortlichkeiten
- Die Kommunikation erfolgt textbasiert
- Ergebnisse werden schrittweise zusammengeführt

---

## 9. GitHub-Repository (Nachbau & Dokumentation)

### 9.1 Ziel des Repositories

Das Repository dient als:
- technische Referenz
- didaktische Anleitung
- Ausgangspunkt für eigene Experimente

---

### 9.2 Struktur

```text
demo_agentic_ai/
├── README.md
├── docs/
│   ├── concept.md
│   ├── didactics.md
│   ├── architecture.md
├── prompts/
│   ├── planner.md
│   ├── research.md
│   ├── budget.md
│   ├── quality.md
│   └── summary.md
├── demo/
│   └── walkthrough.md
└── visuals/
    └── diagrams.md