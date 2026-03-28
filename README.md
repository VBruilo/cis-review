# CIS Exam Review — TU München

Visuelle Aufschlüsselung aller Rechenaufgaben aus den CIS-Übungen und der Klausur 2026.

## 🚀 Deployment auf GitHub Pages (3 Minuten)

### Schritt 1: Repository erstellen
1. Gehe zu [github.com/new](https://github.com/new)
2. Name: `cis-review` (oder was du willst)
3. **Public** auswählen (nötig für GitHub Pages bei Free-Tier)
4. "Create repository" klicken

### Schritt 2: Dateien hochladen
1. Auf der leeren Repo-Seite klicke **"uploading an existing file"**
2. Ziehe den **gesamten Inhalt** dieses Ordners rein:
   - `index.html`
   - `pages/` (ganzer Ordner mit allen HTML-Dateien)
3. Commit Message: `Initial upload`
4. "Commit changes" klicken

### Schritt 3: GitHub Pages aktivieren
1. Im Repo → **Settings** → **Pages** (links in der Sidebar)
2. Under "Source": **Deploy from a branch**
3. Branch: **main**, Folder: **/ (root)**
4. "Save" klicken
5. Warte 1–2 Minuten

### Schritt 4: Fertig! 🎉
Deine Seite ist live unter:
```
https://DEIN-USERNAME.github.io/cis-review/
```

## 📁 Dateistruktur
```
cis-review/
├── index.html          ← Landing Page mit Sidebar-Navigation
├── pages/
│   ├── ex4.html        ← Exercise 4: TCO & Object Store
│   ├── ex7.html        ← Exercise 7: S3 vs S3 Express vs Hetzner
│   ├── ex8.html        ← Exercise 8: LLM Training & Deployment
│   ├── netflix.html    ← Netflix Transcoding Pipeline
│   ├── ex11.html       ← Exercise 11: Storage Deep Dive
│   ├── ex12.html       ← Exercise 12: Database Infrastructure
│   ├── endterm.html    ← CIS 2026 Endterm Breakdown
│   └── mapping.html    ← Klausur ↔ Übungen Mapping
└── README.md
```

## 📱 Features
- **Responsive**: Funktioniert auf Desktop, Tablet und Handy
- **Sidebar-Navigation**: Schnell zwischen allen Übungen wechseln
- **Tab-System**: Jede Übung hat eigene Tabs für verschiedene Aufgabenteile
- **Offline-fähig**: Alles ist self-contained HTML — kein Server nötig
- **Keine Dependencies**: Nur HTML/CSS/JS, keine Build-Tools
