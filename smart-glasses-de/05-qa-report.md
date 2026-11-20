# Taktblick – QA-Bericht

Geprüft wurden der [Browserprototyp](04-prototype/index.html), die [Strategie](02-strategy.md) und die [Marketingtexte](03-copywriting.md). Die Befunde beruhen auf der Quellcodeprüfung und einem ergänzenden Chromium-Test mit Playwright.

## 🔴 Muss behoben werden

Keine blockierenden Befunde.

## 🟡 Empfohlene Verbesserungen

- Die vier Vorteilskarten verwenden Überschriften der Ebene 3 direkt nach der Hauptüberschrift der Ebene 1. Da der Abschnitt bereits einen zugänglichen Namen hat, könnten die Kartentitel auf Ebene 2 liegen. Dabei die bestehenden Schriftgrößen lokal beibehalten.
- Bei deaktiviertem JavaScript bleibt das erste Beispiel sichtbar, die drei Szenario-Schaltflächen reagieren jedoch nicht. Ein kurzer Hinweis im Demoabschnitt könnte in diesem Fall erklären, wie sich die übrigen Beispiele öffnen lassen.

## 🟢 Bestanden

- Das Dokument setzt die Seitensprache auf Deutsch und verwendet semantische Bereiche für Kopf, Hauptinhalt und Fuß. Die geprüften HTML-Elemente sind geschlossen.
- Kernbotschaft, vier Vorteilskarten, Handlungsaufforderung und alle drei Beispieltexte entsprechen der Textvorlage. Die Seite kennzeichnet Taktblick als Konzept und erklärt direkt bei der Demo, dass die Hinweise fiktiv sind.
- „Demo ansehen“ verweist auf die vorhandene Demo-Sektion. Drei native Schaltflächen setzen laut Skript jeweils den sichtbaren Hinweis sowie genau einen aktiven Zustand. Der Anzeigetext ist als Status für assistive Technik ausgezeichnet. CSS definiert sichtbare Fokusmarkierungen.
- Das Layout sieht einspaltige Ansichten für schmale Displays, umbrechende Schaltflächen und eine anpassbare Anzeigefläche vor.
- Im Quellcode sind keine externen Ressourcen, Tracker, Formularübermittlungen oder Netzwerkanfragen vorgesehen. Die Demo enthält keine Preis- oder Lieferzusage.

## Praktischer Browsertest

Der Chromium-Test mit Playwright bestand bei Ansichtsbreiten von 320, 390 und 1.440 Pixeln. Geprüft wurden der Sprung zur Demo, der Wechsel aller drei Szenarien per Eingabetaste und der jeweils gesetzte Auswahlzustand. Es traten weder horizontaler Seitenüberlauf noch Browserfehler oder HTTP-Anfragen auf.

## Freigabe

Als lokal nutzbare Konzeptdemo freigegeben. Die Freigabe bezieht sich auf den Browserprototyp.
