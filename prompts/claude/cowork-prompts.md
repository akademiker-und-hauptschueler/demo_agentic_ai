# Claude Cowork – Demo-Prompts: Geschäftsreiseplanung

> **Kontext:** Diese Prompts sind für eine YouTube-Demo konzipiert.
> Claude Cowork (Stufe 4: lokaler Desktop-Agent) plant eine dreitägige
> Geschäftsreise von Stuttgart nach Berlin.
>
> **Ziel:** Zeigen, wie Cowork autonom recherchiert, Dokumente erstellt,
> Kosten kalkuliert und ein professionelles Ergebnis liefert –
> wie ein "Mitarbeiter am Schreibtisch".
>
> **Hinweis:** Die Prompts werden nacheinander in Claude Cowork eingegeben.
> Zwischen den Prompts kann das Video kommentiert/geschnitten werden,
> um den Prozess für die Zuschauer nachvollziehbar zu machen.

---

## Prompt 1: Briefing & Projektstart

> **Zweck:** Cowork erhält den Gesamtauftrag und erstellt zunächst eine
> Übersicht der Teilaufgaben. Das zeigt auf YouTube den "Kickoff" –
> der Agent versteht die Aufgabe und strukturiert sie selbstständig.

```text
Du bist mein persönlicher Reiseplanungs-Assistent.

Ich benötige einen vollständigen Reiseplan für eine dreitägige
Geschäftsreise von Stuttgart nach Berlin.

Rahmenbedingungen:
- Reisezeitraum: nächste Woche Dienstag bis Donnerstag
- Budget: max. 1.500 € (inkl. Anreise, Hotel, Verpflegung)
- Anreise: Vergleich Bahn (1. Klasse) vs. Flug (Economy)
- Hotel: zentral gelegen, Business-Niveau (min. 4 Sterne)
- Termine: Dienstag 14:00 Uhr Meeting in Berlin-Mitte,
  Mittwoch ganztägig Workshop, Donnerstag Abreise nach dem Frühstück

Erstelle mir bitte zuerst eine strukturierte Übersicht aller
Teilaufgaben, die du abarbeiten wirst. Speichere das als Datei
"reiseplan_aufgaben.md" auf meinem Desktop.
```

---

## Prompt 2: Recherche – Anreise & Hotel

> **Zweck:** Cowork recherchiert aktiv im Browser nach echten Verbindungen
> und Hotels. Das ist der visuell beeindruckendste Teil für YouTube –
> man sieht, wie der Agent selbstständig Webseiten öffnet, sucht und
> Informationen sammelt.

```text
Recherchiere jetzt bitte konkrete Reiseoptionen:

1. Bahnanreise Stuttgart → Berlin:
   - Suche auf bahn.de nach ICE-Verbindungen für nächsten Dienstag
   - Notiere Abfahrtszeiten, Dauer und Preise (1. Klasse)
   - Finde eine Verbindung, die bis 12:30 Uhr in Berlin ankommt

2. Fluganreise Stuttgart → Berlin:
   - Suche Flugoptionen für Dienstag morgen
   - Vergleiche Preise und Gesamtreisezeit (inkl. Flughafen-Transfer)

3. Hotel in Berlin-Mitte:
   - Suche ein 4-Sterne-Hotel nahe Friedrichstraße oder Potsdamer Platz
   - 2 Übernachtungen (Dienstag + Mittwoch), Einzelzimmer mit Frühstück
   - Finde 2-3 Optionen mit Preisen

Trage alle Ergebnisse in eine übersichtliche Datei
"reiseplan_recherche.md" auf meinem Desktop ein.
```

---

## Prompt 3: Kostenübersicht & Budgetvergleich

> **Zweck:** Cowork erstellt eigenständig eine Kalkulation und vergleicht
> Alternativen. Zeigt die "Controlling"-Fähigkeit des Agenten –
> strukturiertes Denken und Zahlenarbeit.

```text
Erstelle auf Basis deiner Recherche-Ergebnisse eine detaillierte
Kostenübersicht.

Vergleiche zwei Szenarien:
- Variante A: Anreise mit der Bahn
- Variante B: Anreise mit dem Flugzeug

Berücksichtige folgende Posten pro Variante:
- Anreise (Hin- und Rückfahrt)
- Hotel (2 Nächte inkl. Frühstück)
- Verpflegung (Tagespauschale 40 €)
- Lokaler Nahverkehr in Berlin (Tageskarte BVG)
- Gesamtkosten und Differenz zum Budget (1.500 €)

Erstelle eine übersichtliche Tabelle und eine klare Empfehlung,
welche Variante wirtschaftlicher ist. Speichere das als
"reiseplan_kosten.md" auf meinem Desktop.
```

---

## Prompt 4: Qualitätsprüfung & Plausibilität

> **Zweck:** Cowork überprüft sein eigenes Ergebnis kritisch.
> Das demonstriert auf YouTube den "Qualitätssicherungs"-Aspekt –
> der Agent denkt mit, statt nur abzuarbeiten.

```text
Überprüfe jetzt bitte den bisherigen Reiseplan auf Plausibilität:

1. Zeitplan-Check:
   - Komme ich mit der gewählten Anreise rechtzeitig zum
     14:00-Uhr-Termin?
   - Ist genug Puffer eingeplant (Hotel-Check-in, Mittagessen)?
   - Passt der Abreise-Zeitplan am Donnerstag?

2. Kosten-Check:
   - Liegen alle Varianten im Budget (1.500 €)?
   - Sind die Preise realistisch und aktuell?
   - Gibt es versteckte Kosten (z.B. Umbuchungsgebühren, Parkhaus)?

3. Logik-Check:
   - Ist das Hotel in sinnvoller Entfernung zu den Terminen?
   - Gibt es Widersprüche oder unrealistische Annahmen?

Falls du Probleme findest, korrigiere diese direkt.
Dokumentiere die Ergebnisse deiner Prüfung als
"reiseplan_qualitaet.md" auf meinem Desktop.
```

---

## Prompt 5: Ergebnisdokument & Management-Zusammenfassung

> **Zweck:** Cowork fasst alles in einem professionellen Dokument zusammen.
> Das ist das Finale der Demo – der Zuschauer sieht ein fertiges,
> vorzeigbares Ergebnis, wie es ein echter Mitarbeiter liefern würde.

```text
Erstelle jetzt ein finales, professionelles Ergebnisdokument, das
alle bisherigen Ergebnisse zusammenfasst.

Das Dokument soll enthalten:

1. Management Summary (max. 5 Sätze):
   - Empfohlene Variante, Gesamtkosten, Kernaussage

2. Reiseplan im Detail:
   - Tagesübersicht (Dienstag, Mittwoch, Donnerstag)
   - Uhrzeiten, Orte, Aktivitäten

3. Kostenübersicht:
   - Tabelle mit allen Posten
   - Empfohlene Variante markiert

4. Anlagen-Verweise:
   - Verweis auf die Detail-Dokumente (Recherche, Kosten, Qualität)

Speichere das finale Dokument als "Geschaeftsreise_Berlin.md"
auf meinem Desktop. Es soll so aussehen, als käme es von einem
professionellen Reisebüro oder einer Assistenz.
```

---

## Optionaler Bonus-Prompt: Kalender & Checkliste

> **Zweck:** Kann optional gezeigt werden, um noch mehr Autonomie zu
> demonstrieren. Cowork erstellt eine Packliste und prüft
> Kalendereinträge – "der Agent denkt über den Auftrag hinaus."

```text
Erstelle abschließend noch zwei Dinge:

1. Eine Reise-Checkliste mit allem, was ich nicht vergessen sollte:
   - Dokumente (Bahnticket, Hotelbestätigung, Meeting-Unterlagen)
   - Technik (Laptop, Ladekabel, Adapter)
   - Persönliches (Kleidung für 3 Tage Business)

2. Prüfe, ob ich Kalendereinträge anlegen soll für:
   - Anreise Dienstag
   - Meeting Dienstag 14:00
   - Workshop Mittwoch ganztags
   - Abreise Donnerstag

Speichere die Checkliste als "reise_checkliste.md" auf meinem Desktop.
```

---

## Hinweise zur YouTube-Demo

### Aufbau für das Video
1. **Intro (vor Cowork):** Kurz erklären, was Cowork ist (Stufe 4, lokaler Agent)
2. **Prompt 1:** Briefing zeigen → Cowork erstellt Aufgabenübersicht
3. **Prompt 2:** Recherche → Cowork öffnet Browser, sucht Verbindungen/Hotels
4. **Prompt 3:** Kosten → Cowork erstellt Tabellen und Vergleich
5. **Prompt 4:** Qualitätsprüfung → Cowork hinterfragt sich selbst
6. **Prompt 5:** Finales Dokument → professionelles Ergebnis
7. **Outro:** Ergebnis zeigen, einordnen (Chancen, Risiken, Fazit)

### Tipps für eine gute Demo
- **Desktop vorher aufräumen:** Nur relevante Apps sichtbar
- **Browser-Lesezeichen:** bahn.de, booking.com etc. vorbereiten (nicht nötig, aber hilft wenn Cowork Probleme hat)
- **Zwischen den Prompts kommentieren:** Erkläre dem Zuschauer, was Cowork gerade tut
- **Ergebnisse am Ende zeigen:** Die erstellten Dateien öffnen und durchgehen
- **Zeitraffer:** Lange Wartezeiten können beschleunigt werden
