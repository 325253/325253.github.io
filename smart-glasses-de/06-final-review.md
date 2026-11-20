# Taktblick – Abschlussbericht für den deutschen Markt

20. November 2026 · Entscheidungsgrundlage für einen Konzepttest

## Kurzfazit

Taktblick ist das Konzept einer Displaybrille für Menschen, die zu Fuß und mit dem ÖPNV pendeln. Sie soll ausgewählte Hinweise zu Umstieg, Wegpunkt und Termin zeigen. Die Fassung ist ohne Kamera und Mikrofon geplant. Die deutschsprachige Browserdemo ist für einen betreuten Konzepttest bereit. Ob die Anzeige am Auge im Alltag besser funktioniert als der Blick aufs Smartphone oder die Smartwatch, bleibt die zentrale Produktfrage. [Browserdemo öffnen](04-prototype/index.html)

## Ergebnisse im Überblick

| Phase | Ergebnis | Stand |
| --- | --- | --- |
| Recherche | [Marktstudie](01-research.md) | Deutsches Befragungssignal, Wettbewerber und Markteintrittshürden dokumentiert |
| Strategie | [Positionierung und Markteintritt](02-strategy.md) | Zielgruppe, Testschwellen, Vertrieb und Preishypothesen festgelegt |
| Vermarktung | [Marketingtexte](03-copywriting.md) | Deutschsprachige Landingpage und Präsentationspunkte ausgearbeitet |
| Entwicklung | [Interaktive Browserdemo](04-prototype/index.html) | Drei fiktive Hinweise lassen sich lokal ausprobieren |
| Qualitätssicherung | [QA-Bericht](05-qa-report.md) | Für die lokale Nutzung freigegeben. Chromium-Test bei 320, 390 und 1.440 Pixeln bestanden |

## Was trägt

- **Der Einstieg ist konkret.** Die Marktstudie unterscheidet Kurzinfos im Blickfeld von Kamera-Aufnahmen, virtuellen Bildschirmen und Fernwartung. Die Strategie konzentriert sich auf den Umstieg, weil er einen wiederkehrenden Anlass mit einer beobachtbaren Aufgabe bietet. [Marktstudie](01-research.md) · [Strategie](02-strategy.md)
- **Text und Demo setzen die Positionierung um.** „Dein nächster Schritt im Blick.“ führt über „Demo ansehen“ zu den drei Beispielhinweisen. Die Demo kennzeichnet diese direkt am Bedienelement als fiktiv. Der Verzicht auf Kamera und Mikrofon erscheint als Designziel. [Marketingtexte](03-copywriting.md) · [Browserdemo](04-prototype/index.html)
- **Der Prototyp funktioniert im geprüften Umfang.** Der CTA führt zur Demo, alle Szenarien lassen sich per Eingabetaste umschalten und der Auswahlzustand aktualisiert sich. Im Chromium-Test gab es bei drei Ansichtsbreiten keinen horizontalen Überlauf, keine Seitenfehler und keine HTTP-Anfragen. [QA-Bericht](05-qa-report.md)

## Was die Entscheidung noch offenlässt

- **Nachfrage und Preis.** Die Bitkom-Befragung misst bisherige Nutzung einschließlich Tests und geäußertes Interesse. Für die Pendelzielgruppe fehlen Daten zu Häufigkeit, Kaufbereitschaft und Vertriebskosten. Die angesetzten 399 € und 499 € sind interne Testpreise. [Marktstudie](01-research.md) · [Strategie](02-strategy.md)
- **Vorteil gegenüber vorhandenen Geräten.** Even G2 bietet bereits ein Display ohne Kamera. Taktblick muss den Wert der ausgewählten Pendelhinweise im direkten Vergleich mit dem gewohnten Gerät zeigen. Passform, Lesbarkeit mit Sehstärke und visuelle Ablenkung erfordern eine physische Erprobung. [Marktstudie](01-research.md) · [Strategie](02-strategy.md)
- **Produktreife.** Die Browserdemo zeigt nur die Abrufansicht. Die Auswahl am gekoppelten Smartphone, Datenflüsse und Löschmöglichkeiten sind im Produktkonzept noch auszugestalten. Die QA nennt als optionale Verbesserungen die Überschriftenhierarchie und einen Hinweis bei deaktiviertem JavaScript. [Strategie](02-strategy.md) · [QA-Bericht](05-qa-report.md)

## Priorisierte nächste Schritte

1. **Verständlichkeit und Nutzen testen.** Zwölf regelmäßige ÖPNV-Pendelnde in zwei deutschen Städten rekrutieren, darunter Personen mit Korrekturbrille. Im betreuten Browsertermin alle drei Hinweise erklären lassen und die simulierte Umsteigeaufgabe mit dem gewohnten Gerät vergleichen. Aufgabenzeit, Fehlinterpretationen und Präferenz erfassen. Als interne Schwellen gelten mindestens 9 von 12 mit korrektem Verständnis aller Beispiele und mindestens 7 von 12 mit Präferenz für die simulierte Anzeige. Bei sicherheitsrelevanten Fehlinterpretationen den Aufbau überarbeiten und erneut prüfen. [Strategie](02-strategy.md)
2. **Anprobe und Preis vorbereiten.** Drei Optik-Fachgeschäfte zu Anprobe, Korrekturgläsern und Service befragen. Für die nächste Phase mindestens zwei Partner für betreute Anproben gewinnen. 399 € und 499 € inkl. MwSt. in wechselnder Reihenfolge testen und mit freiwilligen Folgeterminen abgleichen. [Strategie](02-strategy.md)
3. **Hardwarepilot an Nachweise knüpfen.** Datenflüsse, technische Konformität, Passform, Lesbarkeit und Ablenkung klären. Physische Tests im Stand oder auf einem kontrollierten Parcours ansetzen. Über den Pilotumfang anhand der Ergebnisse sowie der erwarteten Stück-, Retouren- und Servicekosten entscheiden. [Marktstudie](01-research.md) · [Strategie](02-strategy.md)
