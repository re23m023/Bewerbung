# Bewerbungskette offline auf dem iPhone

Die App läuft komplett auf deinem iPhone, auch ohne Internet. Damit Safari sie als App installieren kann, muss sie einmal im Internet liegen. Am einfachsten und kostenlos geht das mit GitHub Pages.

## 1. Auf GitHub hochladen (am Computer, ca. 5 Minuten)

1. Auf github.com einloggen und oben rechts auf **+** › **New repository** klicken.
2. Name: `bewerbungskette`, Sichtbarkeit **Public**, dann **Create repository**.
3. Auf der leeren Seite auf **uploading an existing file** klicken.
4. Alle Dateien aus diesem Ordner hineinziehen (nicht den Ordner selbst): `index.html`, `sw.js`, `manifest.webmanifest`, die drei `icon-…png`. Unten **Commit changes**.
5. Im Repository auf **Settings** › **Pages**. Bei *Source* **Deploy from a branch** wählen, Branch **main**, Ordner **/ (root)**, dann **Save**.
6. Nach ein bis zwei Minuten steht oben die Adresse, etwa `https://DEINNAME.github.io/bewerbungskette/`.

Öffentlich ist dabei nur der Programmcode. Deine Bewerbungen und deine Kette liegen ausschließlich auf deinem iPhone.

## 2. Auf dem iPhone installieren

1. Die Adresse in **Safari** öffnen.
2. Auf **Teilen** tippen und **Zum Home-Bildschirm** wählen.
3. Die App **einmal mit Internet** vom Home-Bildschirm öffnen. Ab dann funktioniert sie auch offline.

## Gut zu wissen

- **Die Daten liegen nur auf diesem iPhone.** Wenn du das App-Symbol löschst, sind sie weg. Lade deshalb ab und zu unter *Woche › Einstellungen* eine **Sicherung** herunter und speichere sie in der Dateien-App.
- **Auf ein neues Gerät umziehen:** Sicherung herunterladen, auf dem neuen Gerät die App installieren und die Sicherung laden.
- **Updates:** Wenn du eine neue Version der Dateien auf GitHub hochlädst, holt sich die App sie beim nächsten Öffnen mit Internet. Erhöhe dafür in `sw.js` die Versionsnummer in der ersten Zeile, etwa auf `bewerbungskette-v2`.
