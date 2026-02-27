# Hitster (Fan Demo)

Browserbasiertes Musik-Timeline-Spiel, inspiriert von **Hitster**.

## Features

- Keine Karten nötig
- Eingabe von Spieleranzahl + Namen
- Songtitel bleibt verborgen bis zur Auflösung
- Play-Button für Spotify-Playback (Embed)
- Einordnen in den eigenen Zeitstrahl
- Multiplayer-Session-Code (Host/Join) via PeerJS, spielbar auf mehreren Smartphones
- Gewinner bei 10 korrekt eingeordneten Songs

## Start

Einfach `index.html` im Browser öffnen (oder via GitHub Pages hosten).

### Multiplayer (Session-Code)

1. Ein Gerät klickt **„Multiplayer Session erstellen“** (Host).
2. Der angezeigte Session-Code wird an Mitspieler geteilt.
3. Andere Geräte geben Namen + Code ein und klicken **„Session beitreten“**.
4. Der aktive Spielerzug wird auf allen Geräten synchron dargestellt.

## Regeln (kurz)

1. Jeder Spieler startet mit einem Song auf dem Zeitstrahl.
2. Im Zug wird ein neuer Song gezogen und abgespielt.
3. Der aktive Spieler setzt ihn an eine Position seines Zeitstrahls.
4. Korrekt = Karte bleibt, falsch = Karte weg.
5. Bei 10 korrekten Karten gewinnt der Spieler.

## Quellen / Recherche

Allgemeine Spielidee und Ablauf wurden anhand öffentlich verfügbarer Hitster-Regelbeschreibungen umgesetzt.

## Hinweis

Dieses Projekt ist ein inoffizielles Fan-Remake und steht in keiner offiziellen Verbindung zur Marke Hitster.
