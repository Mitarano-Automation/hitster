# Hitster (Fan Demo)

Browserbasiertes Musik-Timeline-Spiel, inspiriert von **Hitster**.

## Features

- Lokales Spiel für 1–6 Spieler (inkl. Solo-Modus)
- Songtitel und Jahr bleiben bis zur Bestätigung verborgen
- Audio-Preview (Play/Pause + Seek)
- Fokus-Layout für den Zug:
  - links die **Platzierungs-Timeline** für den aktiven Zug
  - rechts eine **kompakte Spielerübersicht** (Name + Kartenanzahl)
  - aktive Person ist in der Übersicht klar markiert
- Verbesserte Platzierungs-UI:
  - Einfügepunkte klar zwischen den Timeline-Karten
  - ausgewählter Einfügepunkt ist ein **einheitliches Control** inkl. "Aktueller Song"-Status
  - große, mobile-freundliche Tap-Flächen ohne horizontales Slot-Gefummel
- Robuste, browser-sichere Preview-Suche:
  - Preview-Suche nutzt iTunes Search API (CORS-kompatibel für reine Browser-Clients)
  - mehrere Suchvarianten + Treffer-Scoring (Artist/Title + Releasejahr-Nähe)
  - falls kein Preview gefunden wird, läuft der Zug deterministisch ohne Audio weiter (kein Deadlock)
- Gewinner bei 10 korrekt eingeordneten Songs
- Keine Song-Wiederholungen innerhalb eines laufenden Spiels (pro gestarteter Runde eindeutig)

## Start

Einfach `index.html` im Browser öffnen (oder statisch hosten).

## Regeln (kurz)

1. Jeder Spieler startet mit einem Song auf dem Zeitstrahl.
2. Im Zug wird ein neuer Song gezogen und abgespielt.
3. Der aktive Spieler wählt den Einfügepunkt im eigenen Zeitstrahl.
4. Korrekt = Karte bleibt, falsch = Karte wird nicht hinzugefügt.
5. Bei 10 korrekt eingeordneten Songs gewinnt der Spieler.

## Hinweis

Dieses Projekt ist ein inoffizielles Fan-Remake und steht in keiner offiziellen Verbindung zur Marke Hitster.
