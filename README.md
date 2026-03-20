# IRONLOG

Persönlicher Gym-Tracker — läuft komplett im Browser, keine Installation nötig.

## Live-App aufrufen

**https://DEIN-USERNAME.github.io/ironlog**

*(URL nach dem Einrichten von GitHub Pages verfügbar)*

---

## Einmalige Einrichtung auf GitHub

### Schritt 1 — Repository erstellen
1. GitHub.com öffnen → **+ New repository**
2. Name: `ironlog`
3. Visibility: **Public** *(für GitHub Pages kostenlos)*
4. **Create repository** klicken

### Schritt 2 — Dateien hochladen
1. Im neuen Repo auf **"uploading an existing file"** klicken
2. `index.html` und `README.md` hochziehen
3. **Commit changes** klicken

### Schritt 3 — GitHub Pages aktivieren
1. Im Repo auf **Settings** → linke Spalte: **Pages**
2. Under "Branch": `main` auswählen, Ordner: `/ (root)`
3. **Save** klicken
4. Nach 1–2 Minuten ist die App live unter:
   `https://DEIN-USERNAME.github.io/ironlog`

---

## Updates pushen (nach Änderungen)

Wenn du die App aktualisiert hast:

1. Auf GitHub.com ins Repo gehen
2. Auf `index.html` klicken → **Bleistift-Icon** (Edit)
3. Inhalt ersetzen → **Commit changes**
4. Nach ~1 Minute laden alle Nutzer beim nächsten Öffnen automatisch die neue Version

**Oder per Git (schneller):**
```bash
git add index.html
git commit -m "Update"
git push
```

---

## Hinweis für Nutzer

Jeder Nutzer hat seine **eigenen Daten** lokal im Browser gespeichert.  
Updates (neue Features) kommen automatisch beim nächsten Öffnen.  
Die Trainingsdaten bleiben dabei erhalten.

---

## Als PWA installieren (Handy-Homescreen)

**Android (Chrome):**
1. App im Browser öffnen
2. Drei-Punkte-Menü → **"Zum Startbildschirm hinzufügen"**
3. Funktioniert dann wie eine native App

**iPhone (Safari):**
1. App in Safari öffnen
2. Teilen-Icon → **"Zum Home-Bildschirm"**
