---
layout: post
title: "7. Oktober 2026"
description: "KI-Chat direkt am Beleg, KI-Regeln im Klientenprofil, bessere Unterstützung für Kleinunternehmer und weitere Verbesserungen."
---

## 1. KI-Chat am Beleg

Ab sofort kannst du direkt am Beleg mit der KI chatten. Schreib ihr einfach in eigenen Worten, was du wissen oder ändern willst. Ein paar Beispiele, wofür sich der Chat anbietet:

### Fragen zum Beleg

Du willst wissen, warum die KI so gebucht hat? Frag einfach nach.

- _„Warum hast du auf 7380 gebucht?“_
- _„Warum wurde keine Vorsteuer gezogen?“_
- _„Ist das eine Reverse-Charge-Rechnung?“_

<img width="740" height="556" alt="simplescreenrecorder-2026-10-05_15 12 24" src="https://github.com/user-attachments/assets/d6613b97-d7b3-4bc6-bff7-b30576d9bb73" />

### Änderungen am Beleg

Schreib der KI, was anders sein soll. Sie macht daraus einen Änderungsvorschlag und zeigt genau, was sich ändert. Mit **Übernehmen** (`Strg+Enter`) wird die Änderung in den Beleg übernommen, mit **Ablehnen** (`Esc`) verworfen. Ohne deine Bestätigung ändert die KI nichts.

- _„Buch das bitte auf 7390 statt 7380.“_
- _„Teil die Rechnung auf: 50 € auf 7380, den Rest auf 7600.“_
- _„Das Leistungsdatum ist der 30.09.2026.“_
- _„Leg für diesen Lieferanten ein neues Personenkonto an.“_
- _„Die Prüfung zum Steuersatz passt, bitte als erledigt markieren.“_

<img width="740" height="618" alt="simplescreenrecorder-2026-10-05_15 08 41" src="https://github.com/user-attachments/assets/97412c88-b492-47a2-b42f-65bfb4b70bf2" />

Passt deine Anweisung nicht zum Beleg, zum Beispiel ein Erlöskonto auf einer Eingangsrechnung, fragt die KI einmal nach, bevor sie etwas vorschlägt.

### Anweisungen für die Zukunft

Soll etwas nicht nur für diesen Beleg gelten, sondern immer? Dann sag das der KI. Sie legt daraus eine KI-Regel für den Klienten an, die ab dann bei allen Belegen berücksichtigt wird. Ist unklar, ob du nur diesen Beleg oder alle meinst, fragt sie nach.

- _„Rechnungen von A1 bitte immer auf 7380 buchen.“_
- _„Amazon-Rechnungen sind bei diesem Klienten immer Büromaterial.“_
- _„Bei Tankrechnungen gehört immer das Kfz-Kennzeichen in den Buchungstext.“_

<img width="740" height="556" alt="simplescreenrecorder-2026-10-05_15 16 16" src="https://github.com/user-attachments/assets/ae505081-9231-493c-81f7-7a9f51f2baf8" />

## 2. KI-Regeln im Profil

Im Profil des Klienten (links in der Navigation unter „Profil“) gibt es neben der Beschreibung jetzt **KI-Regeln**. Eine Regel ist eine konkrete Anweisung, an die sich die KI halten soll.

Die KI berücksichtigt die Regeln in jedem Schritt, beim Auslesen, bei der Prüfung und beim Verbuchen. In der Begründung zum Buchungsvorschlag siehst du, welche Regel angewendet wurde.

Regeln legst du selbst an („Regel hinzufügen“), über den Chat am Beleg oder mit dem KI-Assistenten rechts im Profil. Jede Regel hat eine Nummer (#R1, #R2 …) und zeigt, wer sie wann angelegt oder geändert hat. Über den Änderungsverlauf lassen sich frühere Versionen wiederherstellen.

<img width="920" height="492" alt="simplescreenrecorder-2026-10-05_15 19 14" style="margin-top: 32px; margin-bottom: 24px" src="https://github.com/user-attachments/assets/1886fbc5-b23b-4e74-a4f1-cdda8e29a470" />

**Tipp:** Bei bestehenden Klienten, bei denen die Regeln noch direkt im Profiltext stehen, kannst du einfach die KI die Arbeit machen lassen:

**_„Bitte aus dem Profil alle Regeln als eigenständige KI-Regeln anlegen“_**

Danach kurz durchsehen, übernehmen und speichern.

## 3. Unterstützung für Kleinunternehmer

Die KI berücksichtigt jetzt beim Verbuchen, wenn ein Klient Kleinunternehmer ist. Das heißt, sie kann Eingangsrechnungen mit dem Bruttobetrag und ohne Steuercode buchen.

<img width="720" height="422" alt="image" src="https://github.com/user-attachments/assets/791e2f02-f6bb-4de6-8d6b-227f6d3a34dd" />

Außerdem erkennt die KI den Klienten auf seinen eigenen Belegen jetzt besser, auch ohne UID-Nummer. Eingangs- und Ausgangsrechnungen werden dadurch zuverlässiger auseinandergehalten.

## 4. Weitere Verbesserungen

- Adresse und Land des Lieferanten werden zuverlässiger ausgelesen.
- Die Stammdaten des Klienten (z. B. Rechtsform, UID, Umsatzsteuer) werden jetzt in allen Verarbeitungsschritten besser berücksichtigt.
- Steuercodes sind in der Auswahlliste nach Nummer sortiert.
- Nach einem Wechsel des Steuercodes wurde der Bruttobetrag teilweise falsch angezeigt, das ist behoben.
