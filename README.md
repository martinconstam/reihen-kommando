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

4 Tracks von [Eric Matyas (soundimage.org)](https://soundimage.org/), royalty-free mit Attribution:

- Track 1: *When Machines Dream*
- Track 2: *Urban Sci-Fi Heroes*
- Track 3: *Cyber City of Light*
- Track 4: *Cosmic Switchboard*
