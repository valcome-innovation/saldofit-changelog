---
layout: post
title: "2. September 2026"
description: "Überarbeitete Buchungsdetailseite, korrekte Buchung berichtigter Rechnungen, weniger Fehlalarme und viele kleine UI-Verbesserungen."
---

## 1. Fehlerbehebungen

- BMD-Export: Die Saldofit-Kennung (`sal:<id>`) wird nicht mehr in `extbelegnr` geschrieben, sondern in `belegdokidext`, die externe Belegnummer bleibt damit frei
- Berichtigte Rechnungen werden nicht mehr als Gutschrift gebucht, nur ein echter Storno-Vermerk dreht die Buchungsrichtung
- Gleiche Prüfhinweise erscheinen im Verlauf nur noch als ein Eintrag statt mehrfach
- Kein „Steuersatz unsicher"-Fehlalarm mehr bei Ausgangsrechnungen mit Reverse Charge (§ 19)
- Belege ohne Buchungszeilen können nicht mehr akzeptiert werden
- Periodenstatistik und Export-Liste aktualisieren sich nach einem BMD-Export sofort

## 2. Allgemeine User-Interface-Verbesserungen

- Überarbeitete Buchungsdetailseite: zweigeteilte Ansicht mit Buchungstabelle oben und Verlauf unten, neue Leiste mit KI-Konfidenz und Akzeptieren-Button (schafft Platz für den geplanten KI-Chat direkt am Beleg)
- Erklärende Tooltips auf Spaltenköpfen
- Einheitliche Status- und Warnhinweise in allen Listen
- `Esc` nimmt den Fokus aus dem Eingabefeld, danach lassen sich wieder alle Shortcuts verwenden
