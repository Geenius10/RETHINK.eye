# EyeTrainer Adaptive v1

Komplett neu aufgebaute App.

Grundprinzip:
- Startscreen: nur EYETRAINER, PLAY.TRAIN. und Play.
- 6 Übungen pro Session.
- Session-Composer wählt gezielt 6 Bereiche statt rein zufällig zu mischen.
- Übergänge zwischen Übungen immer manuell.
- Kein Scrollen, kein Pinch-to-Zoom, keine externen Abhängigkeiten.
- Messbare Übungen passen ihre Schwierigkeit innerhalb der Session an.

Session-Struktur:
1. Augenbewegung: Sakkaden oder Smooth Pursuit
2. Stabilisation/Fokus: Fixierung + Kopfbewegung oder Nah-Fern
3. Wahrnehmung: Alphabet oder Peripherie
4. Reaktion: Reaction Tap
5. Inhibition/Kognition: Go/No-Go oder Stroop
6. Komplexe visuelle Aufgabe: Mentale Rotation, Visual Search, MOT oder Motion Prediction

Adaptive Parameter:
- Reaction Tap: Zielgröße + Pause
- Go/No-Go: einfache Regeln -> kombinierte Regeln + kürzere Antwortfenster
- Stroop: höherer Konfliktanteil + Regelwechsel
- Mentale Rotation: stärkere räumliche Rotation + kürzere Übergänge
- Visual Search: größere Raster + ähnliche Distraktoren
- MOT: mehr Objekte/Ziele + längere/schnellere Bewegung
- Motion Prediction: kürzer sichtbare Bahn + strengere Fehlertoleranz

Feedback:
- richtig = kurzer grüner Vollbild-Flash
- falsch = kurzer roter Vollbild-Flash
- Ergebnisse zeigen Accuracy/Reaktionszeit/Level, wenn messbar.
- Abschluss bleibt minimal: TRAINING COMPLETE + Gesamtwerte.

Motion Prediction:
- Bewegung: Kugel läuft links -> rechts und verschwindet hinter einer Blende.
- Linie: gestrichelter sichtbarer Bahnabschnitt endet früh.
- Statisch: unbewegte Bahn endet früh.
- Bei allen Varianten wird die Endhöhe frei auf einer senkrechten Ziellinie gewählt.
- Danach werden eigener Punkt, korrekter Punkt und vollständige Fortsetzung eingeblendet.

Fixierung + Kopf:
- exakt 8 mögliche Fixationspunkte.
- 4 davon pro Übung.
- Kopfbewegung immer geometrisch zur Gegenseite.
