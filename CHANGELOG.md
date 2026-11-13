# U-Boot Abenteuer – Changelog

Kinder-Handyspiel (FSK 6) mit Three.js, als HTML-Datei, später als PWA.

---

## V4 – 12.11.2026

### Deine Wünsche
- **Läden im Querformat:** Lackiererei und Werkstatt sind jetzt auch quer gut bedienbar. Links ist das Raster, rechts die Details mit dem Kaufen-Knopf.
- **Bestenliste mit Namen:** Nach einem Tauchgang in den Top 10 kann man seinen Namen eintragen. Der letzte Name wird vorgeschlagen.
- **Geisterboot (in den Einstellungen einschaltbar):** Die eigene Rekordfahrt pro Welt fährt als durchsichtiges Boot mit dem Schild „REKORD“ mit. Wer schneller ist, bekommt „Rekord geknackt!“.

### 6 Welten mit Missionen
- Korallenriff, Seetangwald, Schiffswrack-Friedhof, Eismeer, Leuchtende Tiefsee (immer dunkel) und Versunkenes Atlantis.
- Jede Welt hat eigene Wasserfarbe, Boden, Deko und typische Begegnungen.
- Jede Welt hat 3 Missionen. Die erste geschaffte Mission schaltet die nächste Welt frei. Belohnungen: 100/150/200 Münzen und 2/3/5 Diamanten.
- Neuer Bildschirm **„Wähle deine Welt“** beim Tauchen. Während der Fahrt zeigt eine Anzeige den Fortschritt der aktuellen Mission.

### Neue Funde
- **Fische im Netz** retten (+1 Diamant, zählt fürs Aquarium).
- **Schatztruhen** im Schiffswrack-Friedhof (+20 Münzen, +2 Diamanten).
- **Schatzkarten-Teile:** Mit 6 Teilen öffnet sich die Schatzkammer (+500 Münzen, +20 Diamanten).

### Neue Tiere und Erlebnisse
- Blauwal (zieht über dich hinweg, wirft Schatten, singt), Mantarochen, freundlicher Hai, Seepferdchen, Clownfische in Anemonen, Pinguine, Robben.
- **Strömungen**, die das Boot zur Seite schieben.
- **Tunnel** mit Leuchtkristallen, in denen die Scheinwerfer angehen.
- **Wetter:** Regen (Tropfen auf der Oberfläche) und Gewitter (Blitz und Donner).
- **Meeresleuchten:** Nachts glitzert das Wasser hinter dem Boot.

### Logbuch (neu im Hafen)
- **Bestenliste:** Top 10 mit Name, Strecke, Welt und Münzen.
- **Meeres-Lexikon:** 14 Tiere mit 3D-Bild und einem kindgerechten Fakt. Unentdeckte Tiere erscheinen als Schattenriss.
- **Pokale:** 17 Abzeichen, zum Beispiel „Schildkrötenfreund“, „Fischretter“ und „Ausweich-Ass“.
- **Schatzkarte:** zeigt die gesammelten Teile.

### Sonstiges
- **Aquarium im Hafen:** Gerettete Fische schwimmen um die Plattform.
- **Tutorial** beim ersten Tauchgang mit Fipsi, dem Fisch.
- **Vibration** bei Treffern, Diamanten und Missionen (abschaltbar).
- **PWA-Paket:** offline spielbar, mit App-Symbol und dem Knopf „App installieren“.

---

## V3 – 12.11.2026

### Neue Begegnungen unterwegs
- **Querverkehr:** Andere U-Boote in verschiedenen Farben kreuzen den Weg. Ausweichen, sonst kostet es ein Leben.
- **Schiffe an der Wasseroberfläche:** Sie fahren oben vorbei, von unten sieht man den Rumpf mit Schraube.
- **Angelschiff:** Es senkt eine Angelschnur mit Haken und Köder ab. Nicht an der Schnur hängen bleiben!
- **Netzschiff:** Ein Netz reicht von der Oberfläche bis zum Boden. Nur an einer Seite ist eine Lücke, durch die man ausweichen kann.
- **Eisberg:** Er ragt von der Oberfläche tief ins Wasser. Man muss darunter durchtauchen.
- **Delfine:** Eine Gruppe von 3 Delfinen schwimmt in Wellenbewegungen vorbei.
- **Oktopus:** Er stößt eine Tintenwolke aus, wenn man näher kommt, und flitzt davon. Wer durch die Tinte fährt, sieht kurz fast nichts. Den Oktopus selbst darf man nicht berühren.
- **Thunfische:** Ein Schwarm huscht blitzschnell quer durchs Bild.
- **Schildkröte:** Sie schwimmt langsam vorbei, manchmal taucht sie zum Luftholen an die Oberfläche. Ganz nah dran gibt es ein „Hallo Schildkröte!“.

### Wasseroberfläche und Nacht
- Die Wasseroberfläche ist von unten sichtbar und bewegt sich.
- Die Lichtstrahlen kommen jetzt von der Oberfläche.
- Nachts scheint der **Mond** durch die Oberfläche, die Lichtstrahlen werden silberblau.

### Radar
- Ab Stufe 2 zeigt das Radar auch Querverkehr, Angelhaken, Eisberg, Oktopus und die Netzwand (als rote Linie).
- Stufe 3 warnt zusätzlich vor allen neuen Gefahren.

### Sonstiges
- Versionsanzeige „V3“ im Hafen und in den Einstellungen.

---

## V2 – 12.11.2026

### Diamanten
- Alle Sonderfunde geben jetzt **Diamanten** statt Münzen: Perle 1, Müll 1 (plus Umwelt-Stern), Flaschenpost 2, Leuchtperle 3.
- Diamanten werden im Spiel, im Hafen, im Laden und in der Auswertung angezeigt.
- **Diamant-Boote:** Kristallwal (40), Muschel-Palast (80), Diamant-Hai (150).
- **Diamant-Anpassungen:**
  - Farben: Diamant-Glitzer, Polarlicht, Galaxie, Lava
  - Muster: Kristalle, Sternbilder, Drachenschuppen
  - Aufkleber: Diamant, Komet, Planet, Einhorn
  - Schrauben: Kristall, Regenbogen
  - Licht: Sternenlicht, Disco
  - Musik: Diamanten-Glitzer
- Test-Knopf „+100 Testdiamanten“ in den Einstellungen.

### Grafik
- Neue Einstellung **Grafik: Niedrig / Mittel / Hoch**
  - Niedrig: glatte Flächen, einfache Schärfe, weniger Deko
  - Mittel: realistische Texturen (Standard)
  - Hoch: Kiesel-Mosaik-Texturen, volle Schärfe
- Alle Texturen erzeugt das Spiel selbst, es werden keine Bilder von externen Seiten geladen.
- Die Lichtflecken am Meeresboden laufen jetzt als eigene Ebene.

### Ansicht
- Neue **Verfolger-Ansicht** (3D von hinten): Das Boot legt sich in die Kurven, die Steuerung liegt halbtransparent über dem Bild.
- Umschaltbar im Hafen (Zahnrad) und im Pause-Menü: Cockpit / Verfolger.
- Die Drohnen-Ansicht wurde getestet und wieder entfernt (nicht gut spielbar).

### Kleinigkeiten
- Das Einstellungsfenster ist im Querformat kompakter und scrollbar.

---

## V1 – 12.11.2026

- 3D-Unterwasserwelt mit Three.js, Fahrt in Ich-Perspektive (Cockpit).
- Münzen, Sonderfunde (Perle, Flaschenpost, Müll, Leuchtperle), Hindernisse (Quallen, Kugelfische, Felssäulen), 3+ Leben.
- Netz (lädt sich mit Münzen auf), Turbo, Steuerknüppel und Tastatur-Steuerung.
- Tag-Nacht-Wechsel mit Scheinwerfern; je tiefer, desto dunkler.
- Hafen mit drehbarem 3D-Boot.
- Werkstatt: Motor, Ruder, Panzerung, Turbo-Tank, Münzmagnet, Netz-Größe, Netz-Ladung, Radar (3 Stufen).
- Lackiererei: 6 Boote, 19 Farben, 12 Muster, 18 Aufkleber, 8 Schrauben, 6 Lichtfarben, 8 Musikstücke (im Spiel erzeugt).
- Spielstand wird im Browser gespeichert. Test-Knopf „+1000 Testmünzen“.

---

## Geplant für V5
- Spezialausrüstung: Greifarm, Sonar-Ping, Schutzblase, Blasen-Kanone
- Sichtbare Boot-Stufen nach vielen Upgrades
- Begleiter (Fisch, Delfin, Mini-Oktopus, Seepferdchen)
- Boss-Begegnung: Riesenkrake
- Fotomodus
