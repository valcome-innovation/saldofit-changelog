---
layout: post
title: "10. August 2026"
description: "Buchungshistorie aus BMD importieren, Korrekturen aus BMD fließen zurück, Buchen auf Sachkonten"
---

## 1. Buchungshistorie aus BMD importieren

Bisher hat die KI nur aus Belegen gelernt, die in Saldofit selbst gebucht wurden. Bei einem neuen Mandanten hieß das: die ersten Wochen viel korrigieren. Ab jetzt kannst du die bestehenden Ein- und Ausgangsrechnungen aus BMD einfach mitimportieren — die KI hat damit sofort echte Beispiele, wie dieser Mandant bucht.

**So geht's:**

- **Neuer Mandant:** .fib wie gewohnt hochladen. In der Zusammenfassung des Assistenten siehst du jetzt zusätzlich „Buchungshistorie" mit der Anzahl der gefundenen Buchungszeilen.
- **Bestehender Mandant:** Mandant öffnen → Stammdaten → Importieren → .fib-Datei auswählen. Im Dialog „BMD Import" gibt es einen neuen Schalter **Buchungshistorie (n)**. Einschalten, importieren, fertig.

Bei größeren Mandanten dauert der Import ein paar Minuten.

Übernommen werden Ein- und Ausgangsrechnungen (ER/AR) samt Sachkonto, Steuercode, Beträgen und Buchungstext. Zahlungen, Löhne, Abgrenzungen und Eröffnungsbilanz bleiben bewusst draußen. Sammelbelege, bei denen mehrere Rechnungen unter einer Belegnummer hängen, werden übersprungen.

Mehrfach importieren ist kein Problem — bereits bekannte Belege werden erkannt und nicht doppelt angelegt. Spiel die .fib also ruhig regelmäßig ein, zum Beispiel monatlich, nachdem in BMD verbucht wurde.

## 2. Deine Korrekturen aus BMD fließen zurück

Das ist der zweite Teil und aus unserer Sicht der spannendere: Exporte aus Saldofit tragen ab sofort eine Kennung mit (im Feld `extbelegnr`). Beim nächsten .fib-Import erkennt Saldofit dadurch, welche Buchungen ursprünglich von Saldofit kamen — und ob du in BMD noch etwas daran geändert hast.

Wenn ja, gilt deine BMD-Version. Die KI lernt dann aus der korrigierten Buchung statt aus ihrem eigenen Vorschlag, und in der Historie erscheint nur noch die korrigierte Variante.

Für dich heißt das: in BMD arbeiten wie bisher und die .fib gelegentlich zurückspielen. Korrekturen musst du nicht zusätzlich in Saldofit nachziehen.

Ein Hinweis: Die Kennung wird ab diesem Update geschrieben. Für Belege, die vorher schon exportiert wurden, greift der Abgleich noch nicht.

## 3. Buchen auf Sachkonten

Bisher brauchte jeder Beleg ein Personenkonto als Leitkonto. Für Einnahmen-Ausgaben-Rechner, die schlicht alles gegen ein Geldkonto buchen, war das umständlich.

Jetzt kann das Leitkonto auch ein Sachkonto sein. Hinterleg dafür einfach eine Mandantenregel, z.B. „Alle Belege gegen Konto 2800 buchen" — die KI folgt dann dieser Regel.

Ohne eine solche Regel bleibt alles wie gehabt: Es werden weiterhin nur Personenkonten zugeordnet, ein Sachkonto wird nie „auf Verdacht" gewählt. Und fehlt das in der Regel genannte Konto im Kontenrahmen, geht der Beleg mit einem klaren Hinweis in die Prüfung, statt still falsch gebucht zu werden.

## 4. Kleinigkeiten am Rande

- Rechnungsprüfung bei Rechnungen ohne USt (Kleinunternehmer, steuerfreie Umsätze): kein „Steuersatz fehlt" / „Steuerbetrag fehlt" mehr — das waren Fehlalarme.
- Ausgangsrechnungen von Einzelunternehmern mit Titel oder Zusatz im Namen („Erika Musterfrau, B.Sc.") werden wieder korrekt als AR erkannt statt als ER.
- Der Hinweis auf den fehlenden Befreiungsgrund entfällt. Bei ig. Lieferungen bleibt er bestehen, dort ist er relevant.
- BMD-Export: Leere Nullzeilen ohne Steuer werden nicht mehr mit exportiert.

Wie immer gilt: Wenn etwas nicht so läuft wie erwartet oder dir beim Import etwas auffällt, schreib uns einfach.
