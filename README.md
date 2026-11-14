# Gastro-Radar Daten

Diese Datei `radar.json` schreibt der wöchentliche Gastro-Radar-Agent (Montags, und bei jedem manuellen Lauf).
Die Gastro-Offensive-App lädt sie einmal pro Woche. Bitte nichts von Hand ändern – der nächste Lauf überschreibt die Datei.

Format:

- `kw`: Kalenderwoche, z. B. "KW 46 / 2026"
- `stand`: Zeitpunkt der Erstellung (ISO-Format)
- `top3`: die drei wichtigsten Betriebe für einen Vertriebsanruf (`name`, `grund`)
- `leads`: alle Betriebe mit `name`, `ort`, `teilgebiet`, `art`, `kategorie` (neu | gv | bald), `datum`, `potenzial` (hoch | mittel | gering), `notiz`, `quelle` (URL oder null), `adresse`
