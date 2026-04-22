# Geographie-Projekt: 05 Transport maritimer Welthandel

**Autoren:** Jean, Marc, Vijulan

---

## 🚀 GitHub Pages einrichten

1. Diesen Ordner als **GitHub-Repository** hochladen
2. Im Repository → **Settings → Pages**
3. Source: **Deploy from a branch** → `main` / `root`
4. Nach 1–2 Minuten ist die Seite live unter:  
   `https://DEIN-USERNAME.github.io/REPO-NAME/`

---

## 📄 PDFs hinzufügen

1. Lege deine PDF-Dateien in den Ordner **`pdfs/`**
2. Öffne die Datei **`pdfs/pdfs.json`** und trage die Dateinamen ein:

```json
[
  "Mein-Dokument.pdf",
  "Anderes-Dokument.pdf",
  "Noch-ein-Dokument.pdf"
]
```

3. Committe und pushe → die Karten erscheinen **automatisch** auf der Startseite.

---

## 📁 Ordnerstruktur

```
/
├── index.html          ← Hauptseite
├── README.md
└── pdfs/
    ├── pdfs.json       ← Liste der PDFs (manuell pflegen)
    ├── Dokument1.pdf
    └── Dokument2.pdf
```

---

## ⚠️ Hinweis zu VesselFinder

VesselFinder (`vesselfinder.com`) wird als iFrame eingebettet.  
Falls die Seite den iFrame blockiert (X-Frame-Options), öffnet sie sich in einem neuen Tab.  
Dies liegt an den Sicherheitseinstellungen von VesselFinder und kann nicht umgangen werden.
