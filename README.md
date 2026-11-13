# U-Boot Abenteuer – PWA (Version V4)

## Inhalt dieses Ordners
| Datei | Wofür |
|---|---|
| `index.html` | das Spiel |
| `three.min.js` | 3D-Bibliothek (lokal, damit das Spiel offline läuft) |
| `manifest.webmanifest` | App-Name, Symbol, Querformat |
| `sw.js` | Service Worker für den Offline-Betrieb |
| `icon-192.png`, `icon-512.png`, `icon-maskable-512.png` | App-Symbole |

## Veröffentlichen über GitHub Pages
1. Auf github.com ein neues Repository anlegen, zum Beispiel **NoppiCode/UBootAbenteuer** (öffentlich).
2. **Add file → Upload files** und **alle Dateien aus diesem Ordner** hochladen (nicht den Ordner selbst), dann **Commit changes**.
3. **Settings → Pages**: unter *Source* „Deploy from a branch“ wählen, Branch **main** und Ordner **/(root)**, dann **Save**.
4. Nach 1–2 Minuten läuft das Spiel unter `https://noppicode.github.io/UBootAbenteuer/`.

## Auf dem Android-Handy installieren
1. Die Adresse in **Chrome** öffnen.
2. Im Hafen oben rechts auf **„App installieren“** tippen. Falls der Knopf fehlt: Chrome-Menü (⋮) → **App installieren** bzw. **Zum Startbildschirm hinzufügen**.
3. Danach startet das Spiel wie eine App, im Vollbild und auch ohne Internet.

## Ein Update hochladen
- Die geänderte `index.html` (und ggf. andere Dateien) wieder per **Upload files** hochladen.
- In `sw.js` die Zeile `const CACHE = 'uboot-v4';` hochzählen (z. B. `uboot-v5`), damit die Handys die neue Version laden.
- Danach die App einmal schließen und neu öffnen.

Der Spielstand bleibt beim Update erhalten.
