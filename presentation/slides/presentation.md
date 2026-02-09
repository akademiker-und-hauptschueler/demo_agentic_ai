---
marp: true
theme: theme/theme.css
paginate: false
footer: "© 2026 Dennis Grewe | Martin Jäger · Der Akademiker und der Hauptschüler · Agentische KI in 2026"
---

<!-- _class: title-slide -->

# Deep Dive: Agentische KI
## Vom Chatbot zum digitalen Team

**Dennis Grewe · Martin Jäger**  
*Der Akademiker und der Hauptschüler*

---

<!-- _class: agenda-slide -->

<h1 class="agenda-main-title">Agenda</h1>

<div class="agenda-grid">
  <div class="agenda-item">
    <span class="agenda-num">01</span>
    <div class="agenda-line"></div>
    <h3 class="agenda-item-title">Ziel & Leitidee</h3>
    <p class="agenda-item-desc">Für wen diese Session gedacht ist und welcher rote Faden uns leitet</p>
  </div>
  <div class="agenda-item">
    <span class="agenda-num">02</span>
    <div class="agenda-line"></div>
    <h3 class="agenda-item-title">Einordnung & Konzepte</h3>
    <p class="agenda-item-desc">Von klassischer KI über LLMs zu Agenten und agentischen Systemen</p>
  </div>
  <div class="agenda-item">
    <span class="agenda-num">03</span>
    <div class="agenda-line"></div>
    <h3 class="agenda-item-title">Tool-Landschaft</h3>
    <p class="agenda-item-desc">Browser, IDE, CLI bis OpenClaw – Autonomie und Risiken im Überblick</p>
  </div>
  <div class="agenda-item">
    <span class="agenda-num">04</span>
    <div class="agenda-line"></div>
    <h3 class="agenda-item-title">KI als Mitarbeiter</h3>
    <p class="agenda-item-desc">Praktisches Beispiel: Social Media Management durch Agenten</p>
  </div>
  <div class="agenda-item">
    <span class="agenda-num">05</span>
    <div class="agenda-line"></div>
    <h3 class="agenda-item-title">Live-Demo</h3>
    <p class="agenda-item-desc">Geschäftsreiseplanung mit Multi-Agenten-System und technischem Walkthrough</p>
  </div>
  <div class="agenda-item">
    <span class="agenda-num">06</span>
    <div class="agenda-line"></div>
    <h3 class="agenda-item-title">Risiken & Chancen</h3>
    <p class="agenda-item-desc">Zusammenfassung der Risiken und Ausblick auf die Zukunft</p>
  </div>
</div>

---

<!-- _class: goal-slide -->

<div class="goal-slide-content">
  <h1 class="goal-slide-title">Ziele</h1>
  <p class="goal-slide-lead">Konzept der <strong>agentischen KI</strong> verständlich und erlebbar machen.</p>
  <p class="goal-slide-label"></p>
  <div class="goal-cards">
    <div class="goal-card">
      <span class="goal-card-num">01</span>
      <div class="goal-card-line"></div>
      <p class="goal-card-title">Personen am Anfang ihres KI Abenteuers</p>
    </div>
    <div class="goal-card">
      <span class="goal-card-num">02</span>
      <div class="goal-card-line"></div>
      <p class="goal-card-title">Führungskräfte und Entscheidungsträger:innen ohne tiefen technischen Hintergrund</p>
    </div>
  </div>
</div>
<div class="goal-slide-figure">
  <img src="../assets/goal.jpg" alt="Ziel erreichen" />
</div>

---

<!-- _class: roadmap-slide -->

<div class="roadmap-slide-content">
  <h1 class="roadmap-slide-title">Leitidee</h1>
  <blockquote class="roadmap-quote">Agentische KI ist <strong>kein besserer Chatbot</strong> – sondern ein <strong>digitales Team</strong> mit Rollen, Aufgaben und Verantwortung.</blockquote>
  <p class="roadmap-label">Wir schauen uns auf der Karte an:</p>
  <div class="roadmap-narrative">
    <p class="roadmap-step"><strong>Einordnung</strong> – Von klassischer KI über LLMs zu Agenten und agentischen Systemen.</p>
    <p class="roadmap-step"><strong>Tool-Landschaft</strong> – Wo kann ich welches Tool nutzen und welche Risiken gibt es?</p>
  </div>
</div>
<div class="roadmap-slide-figure">
  <img src="../assets/planning.jpg" alt="Roadmap und Planung" />
</div>

---

<!-- _class: section-slide section-slide-einordnung -->

<img class="section-slide-bg" src="../assets/einordnung.jpg" alt="" />
<div class="section-slide-content">
  <h1 class="section-slide-title">Einordnung</h1>
  <p class="section-slide-subtitle">KI, LLM, Agenten, etc.</p>
</div>

---

<!-- _class: einordnung-road-slide -->

# Einordnung: Von KI zu agentischen Systemen

<div class="einordnung-grid">
  <div class="einordnung-item">
    <div class="einordnung-icon-wrapper">
      <!-- Brain icon -->
      <svg class="einordnung-icon" viewBox="0 0 24 24" aria-hidden="true">
        <path fill="currentColor" d="M12 4c-2.2 0-4 1.8-4 4 0 1 .4 2 1 2.7-.8.5-1.3 1.4-1.3 2.4 0 1.5 1.2 2.8 2.7 2.8.4 0 .8-.1 1.2-.2-.1.5-.1 1 0 1.5.4 1.3 1.5 2.2 2.8 2.2 1.6 0 2.9-1.3 2.9-2.9 0-.6-.2-1.2-.5-1.7.8-.5 1.4-1.3 1.4-2.2 0-1.2-.6-2.2-1.6-2.7.5-.8.8-1.8.8-2.8 0-2.2-1.8-4-4-4z"/>
      </svg>
    </div>
    <div class="einordnung-text">
      <div class="einordnung-title">Künstliche Intelligenz</div>
      <div class="einordnung-sub">Basisfähigkeiten (Methoden, Algorithmen)</div>
    </div>
  </div>

  <div class="einordnung-item">
    <div class="einordnung-icon-wrapper">
      <!-- Text file icon -->
      <svg class="einordnung-icon" viewBox="0 0 24 24" aria-hidden="true">
        <path fill="currentColor" d="M6 2h12a2 2 0 0 1 2 2v16a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2zm0 2v16h12V4H6zm2 2h8v2H8V6zm0 4h8v2H8v-2zm0 4h5v2H8v-2z"/>
      </svg>
    </div>
    <div class="einordnung-text">
      <div class="einordnung-title">Large Language Models</div>
      <div class="einordnung-sub">Sprachmodelle (textbasierte KI)</div>
    </div>
  </div>

  <div class="einordnung-item">
    <div class="einordnung-icon-wrapper">
      <!-- Robot icon -->
      <svg class="einordnung-icon" viewBox="0 0 24 24" aria-hidden="true">
        <path fill="currentColor" d="M12 2a3 3 0 0 1 3 3v2h1a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3V10a3 3 0 0 1 3-3h1V5a3 3 0 0 1 3-3zm0 2a1 1 0 0 0-1 1v2h2V5a1 1 0 0 0-1-1zm-2 5a1 1 0 0 0-1 1v8a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1v-8a1 1 0 0 0-1-1h-6zm1 2h4v5h-4V9zm0 6h4v1h-4v-1z"/>
        <circle cx="9" cy="8" r="1.2" fill="currentColor"/>
        <circle cx="15" cy="8" r="1.2" fill="currentColor"/>
      </svg>
    </div>
    <div class="einordnung-text">
      <div class="einordnung-title">Agent</div>
      <div class="einordnung-sub">Interaktive Systeme (Assistenten)</div>
    </div>
  </div>

  <div class="einordnung-item">
    <div class="einordnung-icon-wrapper">
      <!-- Human employee icon -->
      <svg class="einordnung-icon" viewBox="0 0 24 24" aria-hidden="true">
        <path fill="currentColor" d="M12 2c-2.2 0-4 1.8-4 4 0 1.2.5 2.3 1.4 3.1C7.8 9.5 7 11 7 12.5V15h2v-2.5c0-1.1.9-2 2-2s2 .9 2 2V15h2v-2.5c0-1.5-.8-3-2.4-3.4C15.5 8.3 16 7.2 16 6c0-2.2-1.8-4-4-4zm0 2a2 2 0 0 1 2 2c0 .6-.3 1.2-.7 1.6l-.3.2V8h-2v.2l-.3-.2C10.3 7.2 10 6.6 10 6a2 2 0 0 1 2-2z"/>
        <path d="M12 18v4M10 20h4" stroke="currentColor" stroke-width="0.8" fill="none"/>
        <path fill="currentColor" d="M8 14h2v4H8zm6 0h2v4h-2z"/>
      </svg>
    </div>
    <div class="einordnung-text">
      <div class="einordnung-title">Agentische KI</div>
      <div class="einordnung-sub">Autonome Agenten (Teams)</div>
    </div>
  </div>
</div>

<div class="einordnung-arrow">
  <div class="einordnung-arrow-label">Entwicklung</div>
  <div class="einordnung-arrow-line"></div>
</div>

---

<!-- _class: concept-slide -->

<div class="concept-slide-content">
  <h1 class="concept-slide-title">Künstliche Intelligenz (KI)</h1>
  <p class="concept-slide-lead"><strong>KI</strong> ist ein Sammelbegriff für Systeme, die Aufgaben übernehmen, für die normalerweise <strong>menschliche Intelligenz</strong> benötigt wird.</p>
  <p class="concept-slide-label">Beispiele</p>
  <ul class="concept-slide-list">
    <li>Sprache verstehen</li>
    <li>Entscheidungen treffen</li>
    <li>Muster erkennen</li>
  </ul>
  <p class="concept-slide-analogy"><strong>Einordnung:</strong> Basis für alles Weitere – KI als Oberbegriff, LLMs und Agenten als konkrete Ausprägungen.</p>
</div>
<div class="concept-slide-figure">
  <div class="concept-slide-placeholder">Abbildung: KI (z. B. Basisfähigkeiten)</div>
</div>

---

<!-- _class: concept-slide -->

<div class="concept-slide-content">
  <h1 class="concept-slide-title">Large Language Models (LLMs)</h1>
  <p class="concept-slide-lead">Ein <strong>LLM</strong> ist ein KI-System, das Sprache sehr gut versteht und erzeugt.</p>
  <p class="concept-slide-label">Wichtige Eigenschaften</p>
  <ul class="concept-slide-list">
    <li>Reagiert auf Eingaben</li>
    <li>Hat <strong>kein</strong> eigenes Ziel</li>
    <li>Handelt <strong>nicht</strong> selbstständig</li>
    <li>Besitzt kein dauerhaftes Gedächtnis</li>
  </ul>
  <p class="concept-slide-analogy"><strong>Analogie:</strong> Ein sehr gut ausgebildeter Praktikant, der nur arbeitet, wenn man ihn direkt anspricht.</p>
</div>
<div class="concept-slide-figure">
  <div class="concept-slide-placeholder">Abbildung: LLM (z. B. Sprachmodell)</div>
</div>

---

<!-- _class: concept-slide -->

<div class="concept-slide-content">
  <h1 class="concept-slide-title">Agent</h1>
  <p class="concept-slide-lead">Ein <strong>Agent</strong> ist ein System, das ein Ziel verfolgt, Entscheidungen trifft, eigenständig handelt und Werkzeuge nutzt – z. B. LLMs, Suche, Dateien.</p>
  <p class="concept-slide-note">Ein Agent <strong>nutzt</strong> ein LLM – er <strong>ist</strong> kein LLM.</p>
  <p class="concept-slide-label">Kernmerkmale</p>
  <ul class="concept-slide-list">
    <li>Verfolgt ein Ziel</li>
    <li>Trifft Entscheidungen</li>
    <li>Handelt eigenständig</li>
    <li>Nutzt Werkzeuge (LLM, Suche, Dateien …)</li>
  </ul>
  <p class="concept-slide-analogy"><strong>Analogie:</strong> Ein Mitarbeiter mit klarer Aufgabe.</p>
</div>
<div class="concept-slide-figure">
  <div class="concept-slide-placeholder">Abbildung: Agent (z. B. Assistent)</div>
</div>

---

<!-- _class: concept-slide -->

<div class="concept-slide-content">
  <h1 class="concept-slide-title">Agentische KI</h1>
  <p class="concept-slide-lead"><strong>Agentische KI</strong> beschreibt Systeme, in denen mehrere spezialisierte Agenten <strong>koordiniert</strong> auf ein <strong>gemeinsames Ziel</strong> hinarbeiten.</p>
  <p class="concept-slide-label">Merkmale</p>
  <ul class="concept-slide-list">
    <li>Mehrere spezialisierte Agenten</li>
    <li>Koordination untereinander</li>
    <li>Gemeinsames Ziel</li>
  </ul>
  <p class="concept-slide-analogy"><strong>Analogie:</strong> Ein Unternehmen mit Arbeitsteilung, Rollen und Kontrollmechanismen.</p>
</div>
<div class="concept-slide-figure">
  <div class="concept-slide-placeholder">Abbildung: Agentische KI (z. B. Team)</div>
</div>

---

<!-- _class: section-slide section-slide-einordnung -->

<img class="section-slide-bg" src="../assets/einordnung.jpg" alt="" />
<div class="section-slide-content">
  <h1 class="section-slide-title">Quo vadis</h1>
  <p class="section-slide-subtitle">Welche Tools gibt es?</p>
</div>

---

# Tool-Landschaft: Überblick

| Stufe | Tools | Autonomie | Risiko |
|-------|--------|-----------|--------|
| 1 | Browser (Perplexity Comet, OpenAI Atlas) | Gering | Gering |
| 2 | Coding Tools (Cursor, Google Antigravity) | Mittel | Mittel |
| 3 | Coding Agents (Gemini CLI, Anthropic Claude Code, Cursor) | Hoch | Mittel–hoch |
| 4 | "Lokale" Agenten (Anthropic Claude Cowork) | Hoch | Hoch |
| 5 | Vollständig Autonomer Agent (z.B.: OpenClaw) | Sehr hoch | Sehr hoch |

In dieser Session zeigen wir euch Beispiele für die einzelnen Stufen

---

<!-- _class: tool-stage-slide -->

<div class="tool-stage-content">
  <h1 class="tool-stage-title">Stufe 1: KI im Browser</h1>
  <p class="tool-stage-examples">Beispiele: Perplexity Comet, OpenAI Atlas</p>
  <ul class="tool-stage-list">
    <li>Nutzung im Browser, keine Installation (außer Browser)</li>
    <li><strong>Automatisierung:</strong> Recherche, Zusammenfassung, Formulierung</li>
    <li>Geringe Autonomie, Nutzer bleibt im Loop · <strong>Risiko:</strong> gering</li>
  </ul>
  <p class="tool-stage-use-case">Use Case: Schnelle Recherche, Social-Media-Ideen, erste Entwürfe – „digitaler Praktikant im Browser“.</p>
  <div class="tool-stage-hands-on">Hands-on: KI als Social-Media-Manager nutzen</div>
</div>
<div class="tool-stage-figure">
  <div class="tool-stage-placeholder">Abbildung / Screenshot: Browser-Tool (z. B. Comet, Atlas)</div>
</div>

---

<!-- _class: tool-stage-slide -->

<div class="tool-stage-content">
  <h1 class="tool-stage-title">Stufe 2: IDE-basierte Agenten</h1>
  <p class="tool-stage-examples">Beispiele: Cursor, Google Antigravity</p>
  <ul class="tool-stage-list">
    <li>Agent arbeitet <strong>im Code- und Projektkontext</strong></li>
    <li>Höhere Autonomie: Refaktorierung, Implementierung, Debugging</li>
    <li>Kontrolle durch IDE, Versionierung, Freigabe</li>
  </ul>
  <p class="tool-stage-risks">Risiken: Zugriff auf Quellcode; Datenschutz bei Cloud-Backends.</p>
  <div class="tool-stage-hands-on">Hands-on: IDE mit KI-Assistent nutzen</div>
</div>
<div class="tool-stage-figure">
  <div class="tool-stage-placeholder">Abbildung / Screenshot: IDE (z. B. Cursor, Antigravity)</div>
</div>

---

<!-- _class: tool-stage-slide -->

<div class="tool-stage-content">
  <h1 class="tool-stage-title">Stufe 3: Terminal-basierte Agenten</h1>
  <p class="tool-stage-examples">Beispiele: Gemini CLI, Anthropic Claude Code, Cursor</p>
  <ul class="tool-stage-list">
    <li>Agent arbeitet <strong>im Terminal-Kontext</strong></li>
    <li>Höhere Autonomie: Refaktorierung, Implementierung, Debugging</li>
    <li>Kontrolle durch Terminal, Versionierung, Freigabe</li>
  </ul>
  <p class="tool-stage-risks">Risiken: Zugriff auf Quellcode; Datenschutz bei Cloud-Backends.</p>
  <div class="tool-stage-hands-on">Hands-on: Erstellung einer Web-Anwendung für AH</div>
</div>
<div class="tool-stage-figure">
  <div class="tool-stage-placeholder">Abbildung / Screenshot: Terminal (z. B. Cursor, Claude Code)</div>
</div>

---

<!-- _class: tool-stage-slide -->

<div class="tool-stage-content">
  <h1 class="tool-stage-title">Stufe 4: "Lokale" Agentensysteme</h1>
  <p class="tool-stage-examples">Beispiele: Claude Cowork</p>
  <ul class="tool-stage-list">
    <li>Agent läuft <strong>lokal</strong>, Zugriff auf Anwendungen, Fenster, Kontext</li>
    <li>Integration mit Sprachmodellen in der Cloud</li>
    <li>Hohe Autonomie: wie ein „Mitarbeiter am Schreibtisch“</li>
    <li>Illusion eines vollwertigen digitalen Mitarbeiters</li>
  </ul>
  <p class="tool-stage-risks">Risiken: Umfassender Zugriff auf lokale Daten; Data Leaks, Compliance.</p>
  <div class="tool-stage-hands-on">Hands-on: > **Erstelle einen vollständigen, realistischen und verständlichen Reiseplan**  
> inklusive Kostenübersicht und Management-Zusammenfassung.</div>
</div>
<div class="tool-stage-figure">
  <div class="tool-stage-placeholder">Abbildung / Screenshot: Lokaler Agent (z. B. Claude Cowork)</div>
</div>

---

<!-- _class: tool-stage-slide -->

<div class="tool-stage-content">
  <h1 class="tool-stage-title">Stufe 5: Vollständig autonome KI (OpenClaw)</h1>
  <p class="tool-stage-examples">Beispiele: OpenClaw und vergleichbare Systeme</p>
  <ul class="tool-stage-list">
    <li><strong>Maximale Autonomie:</strong> Agent(en) und Werkzeuge laufen vollständig lokal</li>
    <li>Anbindung an Sprachmodelle in der Cloud oder lokal</li>
    <li>Kann als vollwertiger Ersatz für wiederkehrende Tätigkeiten gedacht werden</li>
    <li>Erledigt Aufgaben eigenständig <strong>ohne menschliche Intervention</strong></li>
    <li><strong>Höchstes Risiko:</strong> Fehlverhalten trifft den Arbeitsplatz; Data Leaks, Abhängigkeit</li>
  </ul>
  <p class="tool-stage-note">Kernbotschaft: Kein Tool mehr, sondern ein <strong>digitaler Kollege</strong> – Rollenklärung, Grenzen und Risikobewusstsein sind zentral.</p>
</div>
<div class="tool-stage-figure">
  <div class="tool-stage-placeholder">Abbildung: OpenClaw (kein Hands-on in dieser Session)</div>
</div>

---

# Tool-Landschaft: Überblick

In dieser Session spannt sich der Bogen vom **praktischen Einstieg** bis zur **Live-Demo:**

- **Einstieg:** Agentische KI im Browser – z. B. Social Media unterstützen, Recherche, erste Entwürfe. Geringe Autonomie, überschaubares Risiko.
- **Heute live:** Ein **Multi-Agenten-System** übernimmt eine komplexe Aufgabe (Geschäftsreise planen): mehrere Agenten mit klaren Rollen arbeiten zusammen.

Dazwischen stehen IDE, CLI und lokale Systeme – mehr Autonomie, mehr Möglichkeiten, aber auch mehr **Risiken** (Data Leaks, Kontrollverlust). Wir ordnen die Stufen kurz ein und erleben dann die Demo.

---

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

<!-- _class: multiagent-slide -->

# Multi-Agenten-System: Geschäftsreiseplanung

**Gesamtziel:** Vollständiger, realistischer Reiseplan inkl. Kostenübersicht und Management-Zusammenfassung.

Mehrere **spezialisierte Agenten** arbeiten zusammen – wie in einem Team mit klaren Rollen.

<div class="multiagent-diagram">
  <svg class="multiagent-svg" viewBox="0 0 720 380" xmlns="http://www.w3.org/2000/svg" aria-labelledby="multiagent-title">
    <title id="multiagent-title">Ablauf Multi-Agenten-System Geschäftsreiseplanung</title>
    <!-- Goal -->
    <rect x="260" y="8" width="200" height="36" rx="6" fill="#1A1A1A" stroke="#00E5FF" stroke-width="1.5"/>
    <text x="360" y="30" text-anchor="middle" fill="#00E5FF" font-size="12" font-weight="600">Gesamtziel: Reiseplan + Kosten + Zusammenfassung</text>
    <!-- Agent 1: Planung -->
    <rect x="290" y="58" width="140" height="52" rx="6" fill="#1A1A1A" stroke="#FF1744" stroke-width="1.5"/>
    <text x="360" y="78" text-anchor="middle" fill="#FF1744" font-size="11" font-weight="700">Agent 1: Planung &amp; Koordination</text>
    <text x="360" y="94" text-anchor="middle" fill="#E0E0E0" font-size="9">Projektleitung · Ziel, Teilaufgaben, Beauftragung</text>
    <!-- Arrow goal -> A1 -->
    <path d="M 360 44 L 360 58" stroke="#00E5FF" stroke-width="1.5" fill="none"/>
    <!-- Agents 2,3,4 -->
    <rect x="40" y="128" width="160" height="48" rx="6" fill="#1A1A1A" stroke="#00E5FF" stroke-width="1.5"/>
    <text x="120" y="148" text-anchor="middle" fill="#00E5FF" font-size="10" font-weight="600">Agent 2: Recherche</text>
    <text x="120" y="162" text-anchor="middle" fill="#E0E0E0" font-size="8">Anreise, Hotel, Preisrahmen</text>
    <rect x="280" y="128" width="160" height="48" rx="6" fill="#1A1A1A" stroke="#00E5FF" stroke-width="1.5"/>
    <text x="360" y="148" text-anchor="middle" fill="#00E5FF" font-size="10" font-weight="600">Agent 3: Budget &amp; Kosten</text>
    <text x="360" y="162" text-anchor="middle" fill="#E0E0E0" font-size="8">Kosten, Alternativen, Budget</text>
    <rect x="520" y="128" width="160" height="48" rx="6" fill="#1A1A1A" stroke="#00E5FF" stroke-width="1.5"/>
    <text x="600" y="148" text-anchor="middle" fill="#00E5FF" font-size="10" font-weight="600">Agent 4: Qualität &amp; Plausibilität</text>
    <text x="600" y="162" text-anchor="middle" fill="#E0E0E0" font-size="8">Zeitpläne, Widersprüche prüfen</text>
    <!-- Arrows A1 -> A2, A3, A4 -->
    <path d="M 320 110 L 120 128" stroke="#2A2A2A" stroke-width="1.2" fill="none"/>
    <path d="M 360 110 L 360 128" stroke="#2A2A2A" stroke-width="1.2" fill="none"/>
    <path d="M 400 110 L 600 128" stroke="#2A2A2A" stroke-width="1.2" fill="none"/>
    <!-- Agent 5 -->
    <rect x="240" y="198" width="240" height="52" rx="6" fill="#1A1A1A" stroke="#1DE9B6" stroke-width="1.5"/>
    <text x="360" y="218" text-anchor="middle" fill="#1DE9B6" font-size="11" font-weight="700">Agent 5: Ergebnis &amp; Kommunikation</text>
    <text x="360" y="234" text-anchor="middle" fill="#E0E0E0" font-size="9">Zusammenfassung, Darstellung, Entscheidungsvorlage</text>
    <!-- Arrows A2,A3,A4 -> A5 -->
    <path d="M 120 176 L 280 198" stroke="#2A2A2A" stroke-width="1.2" fill="none"/>
    <path d="M 360 176 L 360 198" stroke="#2A2A2A" stroke-width="1.2" fill="none"/>
    <path d="M 600 176 L 440 198" stroke="#2A2A2A" stroke-width="1.2" fill="none"/>
    <!-- Output -->
    <rect x="280" y="268" width="160" height="36" rx="6" fill="#2A2A2A" stroke="#1DE9B6" stroke-width="1.5"/>
    <text x="360" y="290" text-anchor="middle" fill="#E0E0E0" font-size="10">Reiseplan + Entscheidungsvorlage</text>
    <path d="M 360 250 L 360 268" stroke="#1DE9B6" stroke-width="1.2" fill="none"/>
  </svg>
</div>

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
