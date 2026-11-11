# Froschvolley

Ein kleines Arcade-Volleyballspiel für den Browser – eine einzige HTML-Datei, ohne Abhängigkeiten.

## Starten

Es gibt zwei Versionen, jeweils eine einzelne Datei:

- `index.html` – fürs Smartphone, Hochformat, Steuerung per Finger
- `desktop.html` – für den Browser am Rechner, Querformat, Steuerung per Tastatur

Datei im Browser öffnen (oder z. B. über GitHub Pages ausliefern).

## Regeln

- Der Ball darf auf der eigenen Seite nicht den Boden berühren.
- Höchstens 3 Berührungen pro Seite.
- Jeder Ballwechsel gibt einen Punkt; gewonnen hat, wer zuerst 15 Punkte mit 2 Vorsprung erreicht.

## Steuerung am Smartphone (`index.html`)

Das Spiel ist für Smartphones im Hochformat gebaut und füllt den ganzen Bildschirm.

- **Finger ziehen** – der Frosch läuft zum Finger (am besten unten auf dem Sand, dann verdeckt der Daumen nichts)
- **Nach oben wischen** – springen
- **Mit einem zweiten Finger tippen** – ebenfalls springen

Im 2-Spieler-Modus teilen sich beide ein Handy: Jeder steuert mit dem Finger auf seiner Bildschirmhälfte.

## Steuerung am Rechner (`desktop.html`)

- 1 Spieler: `←`/`→` laufen, `↑` springen (alternativ `A`/`D`/`W`)
- 2 Spieler: Grün `A`/`D`/`W`, Orange `←`/`→`/`↑`
- `P` Pause, `M` Ton

Modi: 1 Spieler gegen den Computer (drei Schwierigkeitsstufen), 2 Spieler, Demo (Computer gegen Computer).
