# Reihen-Kommando

Ein Weltall-Shooter zum Üben der Multiplikations-Reihen (1er bis 10er).
Single-HTML-Datei, keine Dependencies, keine Installation.

## Spielen

Einfach `index.html` im Browser öffnen – oder online:
**https://minecraft.constam.ch/reihen/**

## Gameplay

- Reihen 1-10 auswählbar (1er, 2er, ..., 10er)
- Schwierigkeit: Kadett / Pilot / Captain
- Asteroiden mit Multiplikationsaufgaben (`7 × 4`) fallen von oben
- Antwort tippen + Enter → Laser feuert, Asteroid explodiert
- 3 Leben, Combo-Multiplikator bis 5×
- Alle 10 richtigen Antworten = Level-Up
- High-Score in `localStorage`
- Am Ende: Statistik welche Reihen am meisten Fehler hatten

## Steuerung

- **Ziffern + Enter**: Antwort abschicken
- **Escape**: Pause
- **🔊 / 🔇**: Sound ein/aus (oben rechts)

## Tech

- HTML, CSS, JS – alles in einer Datei
- Canvas 2D für Grafik
- Web Audio API für SFX (synthetisiert)
- 4 royalty-free Musik-Tracks als MP3 (HTML Audio)
- localStorage für High-Score und Mute-Setting

## Musik-Credits

4 Tracks von [Kevin MacLeod (incompetech.com)](https://incompetech.com/), lizenziert unter [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/):

- Track 1: *8bit Dungeon Boss*
- Track 2: *8bit Dungeon Level*
- Track 3: *Bit Quest*
- Track 4: *Bit Shift*
