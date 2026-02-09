# Gamma.app – Agentische KI (Look & Feel + Narrative)

**Verwendung:** In Gamma „Paste“ nutzen und diesen Text einfügen. Anschließend unter **Theme / Design** ein eigenes Theme anlegen und die Farben/Schrift aus „Look & Feel“ übernehmen. Die ersten beiden Karten (diese + Look & Feel) können nach dem Anwenden des Themes gelöscht werden.  
**Quelle:** Der Akademiker und der Hauptschüler · Podcast-Spec & Präsentation

---

## Look & Feel (Podcast-Branding)

Diese Werte aus der Podcast-Theme (`theme.css`) in Gamma als **eigenes Theme** anlegen, damit die Präsentation zum Look des Podcasts passt:

- **Hintergrund (dunkel):** `#0A0A0A`
- **Sekundär dunkel:** `#1A1A1A`, `#2A2A2A`
- **Akzent Rot (Primär):** `#FF1744`
- **Akzent Cyan:** `#00E5FF`
- **Akzent Türkis:** `#1DE9B6`
- **Text hell:** `#E0E0E0`, **Weiß:** `#FFFFFF`
- **Schrift:** Inter, Segoe UI oder Helvetica Neue
- **Stil:** Dunkles Theme, klare Überschriften, Red/Cyan-Gradient oder Akzente für Titel

---

# Agentische KI in 2026
## Vom Chatbot zum digitalen Team

---

# Agenda

1. **Ziel & Leitidee** – Für wen, wozu, roter Faden  
2. **Einordnung** – KI → LLM → Agent → Agentische KI  
3. **Tool-Landschaft** – Vom Browser bis OpenClaw (Autonomie & Risiken)  
4. **KI als Mitarbeiter** – Beispiel Social Media  
5. **Demo-Szenario** – Geschäftsreiseplanung mit Multi-Agenten  
6. **Technische Demo** – CLI, Rollen, Repository  

---

# 1. Ziel des Vorhabens

Das Konzept der **agentischen KI** soll für eine **nicht-technische Zielgruppe** verständlich, greifbar und erlebbar gemacht werden.

**Zielgruppe:**
- Personen am Anfang einer Berufsausbildung  
- Führungskräfte und Entscheidungsträger:innen ohne tiefen technischen Hintergrund  

**Fokus:** mentale Modelle, Rollenverständnis, organisatorische Analogien – **nicht** technische Details.

---

# 2. Leitidee

> Agentische KI ist **kein besserer Chatbot** –  
> sondern ein **digitales Team** mit Rollen, Aufgaben und Verantwortung.

**Eskalationspfad (Konzepte):**
1. Klassische KI  
2. LLMs (Sprachmodelle)  
3. Agenten  
4. Multi-Agenten-Systeme  
5. Agentische Organisation  

**Zusätzlich:** Wo wird das genutzt? Browser → IDE → CLI → lokale Agenten → OpenClaw – mit zunehmender Autonomie und zunehmenden Risiken.

---

# 3. Einordnung: Künstliche Intelligenz (KI)

**KI** ist ein Sammelbegriff für Systeme, die Aufgaben übernehmen, für die normalerweise **menschliche Intelligenz** benötigt wird.

**Beispiele:** Sprache verstehen, Entscheidungen treffen, Muster erkennen.

---

# 3. Einordnung: Large Language Models (LLMs)

Ein **LLM** versteht und erzeugt Sprache sehr gut.

- Reagiert auf Eingaben  
- Hat **kein** eigenes Ziel  
- Handelt **nicht** selbstständig  
- Kein dauerhaftes Gedächtnis  

**Analogie:** Ein sehr gut ausgebildeter Praktikant, der nur arbeitet, wenn man ihn direkt anspricht.

---

# 3. Einordnung: Agent

Ein **Agent** …
- verfolgt ein Ziel  
- trifft Entscheidungen  
- handelt eigenständig  
- nutzt Werkzeuge (LLM, Suche, Dateien …)  

**Wichtig:** Ein Agent **nutzt** ein LLM – er **ist** kein LLM.

**Analogie:** Ein Mitarbeiter mit klarer Aufgabe.

---

# 3. Einordnung: Agentische KI

**Agentische KI:** Mehrere spezialisierte Agenten arbeiten **koordiniert** auf ein **gemeinsames Ziel** hin.

**Analogie:** Ein Unternehmen mit Arbeitsteilung, Rollen und Kontrollmechanismen.

---

# 4. Tool-Landschaft: Autonomie & Risiken

Mit jedem Schritt werden die Agenten **mächtiger** und **eigenständiger** – bis hin zum „Ersatz“ eines vollwertigen Mitarbeiters. Dafür steigen auch **Risiken:** Data Leaks, Abhängigkeit, Kontrollverlust.

**Roter Faden:** Browser → IDE → CLI → lokale Agenten → **OpenClaw** (vollständig lokal, maximale Autonomie).

---

# Stufe 1: Agentische KI im Browser

**Beispiele:** Perplexity Comet, Atlas

- Nutzung im Browser, keine Installation  
- **Automatisierung:** Recherche, Zusammenfassung, Formulierung  
- Geringe Autonomie, Nutzer bleibt im Loop  
- **Risiko:** gering  

**Use Case:** Schnelle Recherche, Social-Media-Ideen, erste Entwürfe – „digitaler Praktikant im Browser“.

---

# Stufe 2: IDE-basierte Agenten

**Beispiele:** Cursor, Google Antigravity

- Agent arbeitet **im Code- und Projektkontext**  
- Höhere Autonomie: Refaktorierung, Implementierung, Debugging  
- Kontrolle durch IDE, Versionierung, Freigabe  

**Risiken:** Zugriff auf Quellcode; Datenschutz bei Cloud-Backends.

---

# Stufe 3: CLI-basierte agentische KI

**Beispiele:** Gemini CLI, Claude Code

- Agent führt **Aktionen in Shell und Dateisystem** aus  
- Hohe Autonomie: Der Agent „handelt“, nicht nur antwortet  
- Ideal für **rollenbasierte Demos** (wie in dieser Session)  

**Risiken:** Fehlgeleiteter Befehl kann Systeme oder Daten beeinträchtigen.

---

# Stufe 4: Lokale Agentensysteme

**Beispiele:** Claude Cowork

- Agent läuft **lokal**, Zugriff auf Anwendungen, Fenster, Kontext  
- Hohe Autonomie: wie ein „Mitarbeiter am Schreibtisch“  
- Illusion eines **vollwertigen digitalen Mitarbeiters**  

**Risiken:** Umfassender Zugriff auf lokale Daten; Data Leaks, Compliance.

---

# Stufe 5: Vollständig lokale KI (OpenClaw)

**Beispiele:** OpenClaw und vergleichbare Systeme

- **Maximale Autonomie:** Modell und Agent laufen vollständig lokal  
- Kann als **vollwertiger Ersatz** für wiederkehrende Tätigkeiten gedacht werden  
- **Höchstes Risiko:** Fehlverhalten trifft direkt den Arbeitsplatz; Data Leaks, Abhängigkeit  

**Kernbotschaft:** Kein Tool mehr, sondern ein **digitaler Kollege** – Rollenklärung, Grenzen und Risikobewusstsein sind zentral.

---

# Tool-Landschaft: Überblick

| Stufe | Tools | Autonomie | Risiko |
|-------|--------|-----------|--------|
| 1 | Browser (Comet, Atlas) | Gering | Gering |
| 2 | IDE (Cursor, Antigravity) | Mittel | Mittel |
| 3 | CLI (Gemini CLI, Claude Code) | Hoch | Mittel–hoch |
| 4 | Lokale Agenten (Claude Cowork) | Hoch | Hoch |
| 5 | Lokal full-blown (OpenClaw) | Sehr hoch | Sehr hoch |

**Diese Session:** Überblick + Demo auf **Stufe 3** (CLI) als nachvollziehbarer Anker.

---

# 5. KI als Mitarbeiter – Beispiel

**Früher:** Ein Social-Media-Manager mit klaren Aufgaben (Posts erstellen, veröffentlichen, analysieren, optimieren, messen).

**Heute:** Ein Agent kann das übernehmen – z. B. mit agentischer KI **im Browser** (Stufe 1): geringe Autonomie, überschaubares Risiko.

*„Logge dich ein und lass uns gemeinsam einen Social-Media-Post erstellen.“*

---

# 6. Demo-Szenario: Geschäftsreiseplanung

Ein agentisches System plant eine **dreitägige Geschäftsreise nach Berlin**.

**Das System soll:**
- Reiseoptionen recherchieren  
- Kosten kalkulieren  
- Plausibilität prüfen  
- Ergebnisse verständlich aufbereiten  

**Warum dieses Szenario?** Alltagsnah, keine Fachkenntnisse nötig, typische Büro- und Managementprozesse.

---

# 7. Multi-Agenten: Gesamtziel

> **Erstelle einen vollständigen, realistischen und verständlichen Reiseplan**  
> inklusive Kostenübersicht und Management-Zusammenfassung.

Mehrere **spezialisierte Agenten** übernehmen Rollen wie in einem Team.

---

# Agent 1: Planung & Koordination

**Rolle:** Projektleitung  

**Aufgaben:**
- Ziel verstehen  
- Teilaufgaben definieren  
- andere Agenten beauftragen  
- Ergebnisse zusammenführen  

---

# Agent 2: Recherche

**Rolle:** Assistenz / Sachbearbeitung  

**Aufgaben:**
- Anreiseoptionen (Zug/Flug)  
- Hotelvorschläge  
- grobe Preisrahmen  

---

# Agent 3: Budget & Kosten

**Rolle:** Controlling  

**Aufgaben:**
- Gesamtkosten berechnen  
- Alternativen vergleichen  
- Budgetgrenzen beachten  

---

# Agent 4: Qualität & Plausibilität

**Rolle:** Qualitätssicherung  

**Aufgaben:**
- Zeitpläne prüfen  
- Widersprüche erkennen  
- unrealistische Annahmen markieren  

---

# Agent 5: Ergebnis & Kommunikation

**Rolle:** Management-Kommunikation  

**Aufgaben:**
- Ergebnisse zusammenfassen  
- verständliche Darstellung  
- Entscheidungsvorlage erstellen  

---

# 8. Technische Demo (CLI)

**Ziel:** Live zeigen, dass Agenten **rollenbasiert** arbeiten – ohne Programmierung, Fokus auf Denkweise.

**Tools (Stufe 3):** z. B. Gemini CLI, Claude Code  

**Prinzip:** Jeder Agent erhält eine Rolle, ein Ziel, klare Verantwortlichkeiten; Kommunikation textbasiert, Ergebnisse werden schrittweise zusammengeführt.

---

# 9. GitHub-Repository

**Zweck:** Technische Referenz, didaktische Anleitung, Ausgangspunkt für eigene Experimente.

**Struktur (Auszug):** `docs/` (concept, didactics, architecture), `prompts/` (planner, research, budget, quality, summary), `demo/walkthrough.md`, `visuals/diagrams.md`

---

# Abschluss & Nächste Schritte

**Heute:** Einordnung (KI → LLM → Agent → Multi-Agent), Tool-Landschaft (Browser bis OpenClaw), Demo mit rollenbasierten CLI-Agenten.

**Mitnehmen:** Agentische KI = digitales Team mit Rollen und Verantwortung; mehr Autonomie = mehr Nutzen, aber auch mehr Risiken (z. B. Data Leaks).

**Fragen?**

---

*© 2026 Dennis Grewe | Martin Jäger · Der Akademiker und der Hauptschüler · Agentische KI*
