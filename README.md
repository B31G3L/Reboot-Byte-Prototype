# Reboot BYTE – Prototyp

Spielbarer Prototyp für die Taktgeber-Geschichte: alle sechs Roboter (BYTE, OKTA, HEXA, PIXA, ASKI, CHROMA) mit allen Sonder-LEDs und Regeln, 41 Rätsel.

Spielen: https://b31g3l.github.io/Reboot-Byte-Prototype/

Alles steckt in einer Datei (`index.html`), ohne Build-Schritt. Spielstand und Sterne liegen nur im Browser (localStorage).

## Binär-Sudoku

Zweiter Prototyp: ein Binär-Sudoku als Roguelite im Reboot-BYTE-Look.

- **Nachtschicht:** acht Etagen bis zum Hauptrechner, Akku als Leben (falsches Bit = Kurzschluss), Bits für Tipps und Module, Störungen mit Flüchen
- **Roboter werden freigeschaltet** (Etage 3, 3 Störungen, Etage 6, erster Sieg, Sieg mit 2 Robotern). Beim Aufwachen gibt es eine kurze Einführung, danach tauchen ihre Hinweis-Arten (Hex, Oktal, ASCII, Geheimbilder, Farben) in den Schichten auf.
- **Werkstatt:** Ersatzteile aus jeder Schicht für dauerhafte Upgrades, dazu Spannungsstufen nach dem ersten Sieg
- **Album:** Geheimbilder und Nachrichten, die man unterwegs findet
- Tagesschicht mit festem Seed, Schalter „Alles freischalten (Test)“

Spielen: https://b31g3l.github.io/Reboot-Byte-Prototype/binaer-sudoku/

Liegt in `binaer-sudoku/index.html`, ohne Build-Schritt.
