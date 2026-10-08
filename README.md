# Kassenabrechnung – Einlass & Verzehr

Kleine Web-App zum Abrechnen der Einlass- und Verzehrkasse über drei Schichten
(19:00–21:00, 21:00–23:00, 23:00–01:00). Läuft komplett im Browser, auch auf dem Handy.

## Funktionen
- Einlassbänder und Verzehrkarten: Start, Ende, Rückgaben
- Geld zählen per Schein (5–500 €) und Münze (2 €, 1 €, 0,50 €) mit +/− Tasten, plus sonstiges Kleingeld
- Helfer-Namen pro Schicht für Einlass- und Verzehrkasse
- Notizfeld pro Schicht
- Automatisch: verkaufte Stückzahl, Gewinn, Verlust, Soll-Betrag und Kassendifferenz
- Übersicht über alle Schichten mit Gesamtsumme
- Export als PDF und als Excel-Datei (.xlsx, mit zweitem Blatt „Geldzählung“), funktioniert ohne Internet-Bibliotheken
- KrAS-Logo in der App, im PDF und in der Excel-Datei
- Eingaben werden automatisch auf dem Gerät gespeichert

## Auf GitHub Pages veröffentlichen
1. Auf GitHub ein neues Repository anlegen (z. B. `kassenabrechnung`).
2. `index.html` und `README.md` hochladen („Add file“ → „Upload files“ → „Commit changes“).
3. Im Repository: **Settings → Pages** → bei „Source“ *Deploy from a branch* wählen,
   Branch `main` und Ordner `/ (root)` → **Save**.
4. Nach ca. 1 Minute ist die App erreichbar unter
   `https://<dein-benutzername>.github.io/kassenabrechnung/`

Tipp: Die Seite am Handy über „Zum Home-Bildschirm“ hinzufügen, dann öffnet sie sich wie eine App.

## Hinweis
Die Daten liegen nur im Browser des jeweiligen Geräts. Wer an einem anderen Handy zählt,
sieht diese Eingaben nicht. Vor „Neuen Abend starten“ am besten als CSV exportieren.
