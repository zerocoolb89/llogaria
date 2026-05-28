# Kontabiliteti — Buchhaltungs-Apps (PWA)

Zwei Browser-Apps in einem Paket:
- **index.html** — Startseite (verlinkt beide Apps)
- **kontabiliteti-plote.html** — Vollversion (Dashboard, TVSH, Buxhet, Mjete, Saldo)
- **llogaria-thjeshte.html** — einfache Version (Të ardhura, Shpenzime, Saldo)
- manifest.webmanifest, sw.js, icon-*.png — für PWA/Offline/Installation

## Auf GitHub Pages veröffentlichen (Weboberfläche)
1. github.com → Konto erstellen (kostenlos).
2. "+" → "New repository" → Name z. B. `buchhaltung` → **Public** → "Create repository".
3. "Add file" → "Upload files" → **alle Dateien aus diesem Ordner** reinziehen → "Commit changes".
4. "Settings" → "Pages" → Source: "Deploy from a branch" → Branch `main`, Ordner `/ (root)` → "Save".
5. Nach ~1–2 Min. ist die App live unter: `https://DEINNAME.github.io/buchhaltung/`

## Nutzen
- iPhone/iPad (Safari): URL öffnen → Teilen → "Zum Home-Bildschirm".
- Mac/Windows (Chrome/Edge): "Installieren" in der Adressleiste.
- Daten werden lokal im Browser gespeichert. Regelmässig **Backup** (Button in der App) machen — die Daten synchronisieren sich nicht automatisch zwischen Geräten.

Hinweis: Kein revisionssicheres Buchhaltungssystem; für offizielle Steuererklärungen zertifizierte Software verwenden.
