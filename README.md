# Excel Jump

Ein kleines Jump'n'Run-Spiel für den HKBe-Unterricht (KBS Liestal). Die Lernenden laufen durch zwei Level und lösen an jedem Posten Aufgaben aus einer Excel-Übungsdatei. Erst wenn alle Antworten stimmen, öffnet sich das Tor zum nächsten Abschnitt.

## Inhalt

| Datei | Zweck |
|---|---|
| `index.html` | Das ganze Spiel (HTML, CSS und JavaScript in einer Datei) |
| `uebungen/HKBe_Excel_Funktionen_Uebungen.xlsx` | Übungsdatei für Level 1 (mit Erklärungen) |
| `uebungen/HKBe_Excel_Funktionen_Teil2.xlsx` | Übungsdatei für Level 2 (ohne Hilfen) |

## Spielen

- Steuerung: Pfeiltasten oder A/D zum Laufen, Leertaste, W oder ↑ zum Springen, E oder Enter öffnet einen Posten.
- Wer in eine Lücke fällt, Stacheln oder einen Fehlerwert berührt, beginnt am Start des aktuellen Levels. Gelöste Posten bleiben gelöst.
- Level 1 ist gleichbleibend einfach, in Level 2 wird es von Posten zu Posten schwieriger.

## Hinweise

- Die Lösungen sind im Code verschlüsselt, damit sie nicht direkt lesbar sind. Ganz verhindern lässt sich das Auslesen bei einem reinen Browserspiel aber nicht.
- Die Lösungsdateien gehören nicht in dieses Repository.
- Die Lernenden geben nur einen Spielnamen ein, es werden keine Daten gespeichert oder verschickt.
