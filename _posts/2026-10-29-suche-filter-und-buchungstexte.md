---
layout: post
title: "29. Oktober 2026"
description: "Suche und Filter in allen Belegtabellen, Belege mit offenen Prüfungen gesammelt verbuchen, eigener Buchungstext je Buchungszeile, Kontoeinstellungen und weitere Verbesserungen."
---

## 1. Belege schneller finden und verbuchen

Über den Tabellen in Erfassung, Belegen und Buchungsjournal gibt es jetzt ein Suchfeld und einen Filter. Belege mit offenen Prüfungen lassen sich außerdem gesammelt verbuchen.

### Suche und Filter

`Strg+K` öffnet die Suche, `F` den Filter. Treffer werden in der Tabelle hervorgehoben, gefiltert wird je nach Spalte nach Text, Datum, Betrag oder Status. Aktive Filter stehen als Chips über der Tabelle, die gefilterte Ansicht lässt sich als Link weitergeben. Auch Sach- und Personenkonten im Klientenprofil lassen sich jetzt durchsuchen.

<img width="700" height="490" alt="simplescreenrecorder-2026-10-29_17 50 12" src="https://github.com/user-attachments/assets/89159d4b-552c-4d77-bff9-10d8b0df06ee" />

### Belege mit offenen Prüfungen gesammelt verbuchen

In der Erfassung gibt es bei der Mehrfachauswahl jetzt **Verbuchen** für Belege, die auf eine Prüfung warten. Die offenen Prüfungen gelten dabei als erledigt.

Am einzelnen Beleg heißt „Prüfung abschließen“ jetzt ebenfalls **Verbuchen** und bucht direkt. Bei offenen Prüfungen listet ein Dialog die Punkte, `Enter` bestätigt.

<img width="740" alt="simplescreenrecorder-2026-10-29_17 54 07" src="https://github.com/user-attachments/assets/39252c93-d80b-4111-a372-1788a988bb72" />

## 2. Konto und Passwort selbst verwalten

Im Benutzermenü rechts oben gibt es jetzt **Einstellungen**. Dort lassen sich der eigene Name und das Passwort ändern und alle Geräte auf einmal abmelden.

<img width="740" alt="Screenshot from 2026-10-29 17-57-35" src="https://github.com/user-attachments/assets/12f2b210-3060-4b08-8c24-297252855f31" />

Passwort vergessen? Auf der Anmeldeseite lässt sich ein Link zum Zurücksetzen per E-Mail anfordern. Neue Benutzer werden per E-Mail eingeladen und legen beim ersten Öffnen Name und Passwort selbst fest, Admins müssen kein Passwort mehr weitergeben.

Nach diesem Update ist einmalig eine neue Anmeldung nötig.

## 3. Eigener Buchungstext je Buchungszeile

Bucht ein Beleg auf mehrere Zeilen, bekommt jede Zeile jetzt einen eigenen Buchungstext. Der Text lässt sich in der Buchungstabelle direkt bearbeiten oder über den KI-Chat ändern.

<img width="740" alt="Screenshot from 2026-10-29 17-59-55" src="https://github.com/user-attachments/assets/42f7fb74-7d25-431f-b3cf-4dda7db011d6" />

## 4. Weitere Verbesserungen

- Das Klientenprofil unter „Stammdaten“ ist neu gegliedert in Allgemein, Stammdaten und Periodendaten. Änderungen werden über die Leiste unten gespeichert.
- Neben dem Anzeigenamen gibt es jetzt den **Firmenwortlaut**. Die KI erkennt den Klienten auf Belegen anhand des Firmenwortlauts, der Anzeigename bleibt frei wählbar. Beim BMD-Import wird er mit übernommen.
- „Periode ändern“ heißt bei der Mehrfachauswahl jetzt „Verschieben“. Die Leiste ist kompakter, die Buttons erklären sich per Tooltip.
- Wird die Seitenzuweisung eines Belegs geändert, aktualisiert sich die Vorschau sofort.
