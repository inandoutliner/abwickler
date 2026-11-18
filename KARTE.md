# Inhaltskarte

Automatisch erzeugt mit `werkstatt/werkzeuge/karte.py`. Stand: 578769c, 2026-11-18: Abwickler 3031 (Stand aus APPs)

Vorgehen: Abschnitt hier finden → `grep -n "<Titel>" index.html` → nur diesen Bereich lesen.

## `index.html` – Abwickler 3031
6160 Zeilen, 711 KB.

**Datenblöcke – nie komplett ausgeben** (z. B. `cut -c1-200` oder `awk 'length<3000'`):

- Zeile 1738: 13 KB – `g: {" ":[189,[]],"!":[158,[[158,331,158,110],[158,32,142,16…`
- Zeile 1740: 23 KB – `g: {" ":[189,[]],"!":[158,[[142,331,126,299,142,110,158,299…`
- Zeile 1742: 21 KB – `g: {" ":[189,[]],"!":[173,[[176,331,160,315,129,126],[176,3…`
- Zeile 1744: 22 KB – `g: {"0":[251,[[123,9,153,16,185,47,199,81,205,118,208,170,2…`
- Zeile 1746: 14 KB – `g: {"0":[381,[[65,268,65,30,93,3,342,3,372,32,372,274,347,2…`
- Zeile 1748: 19 KB – `g: {"0":[281,[[188,164,174,255,139,310,94,328,49,310,14,255…`
- Zeile 1750: 40 KB – `g: {"0":[315,[[189,331,142,315,110,268,95,189,95,142,110,63…`
- Zeile 1752: 15 KB – `g: {" ":[12,[]],"!":[7,[[3.5,21,3.5,7],[3.5,2,2.5,1,3.5,0,4…`
- Zeile 1754: 21 KB – `g: {" ":[12,[]],"!":[12,[[8.5,21,7.5,20,5.5,8],[8.5,20,5.5,…`
- Zeile 1756: 15 KB – `g: {" ":[12,[]],"!":[12,[[8.5,21,7.5,20,5.5,8],[8.5,20,5.5,…`
- Zeile 5007: 30 KB – `const MOTIVE = [{"id":"h-astrology-2","t":"Himmel","n":"Son…`
- Zeile 5010: 35 KB – `const QUOTES = {"woolf": {"name": "Virginia Woolf", "quotes…`

**Bedien-Bereiche (HTML)**

- 394: `<nav>` Schritte
- 407: `<section>` Eingabe
- 409: `<section>` 1
- 535: `<section>` 2
- 553: `<section>` jointBox
- 650: `<section>` 3
- 652: `<section>` pickBox
- 684: `<section>` feetBox
- 699: `<section>` winPickBox
- 723: `<section>` pickStrutsBox
- 773: `<section>` 4
- 877: `<section>` 5
- 974: `<section>` 6
- 1145: `<section>` 7
- 1227: `<section>` Ergebnis

**Abschnitte im Code** (Suchbegriff = Titel)

| Zeile | Abschnitt | Funktionen |
|---|---|---|
| 232–1861 | 3029: ruhigere Werkbank. Abschnitte statt Kästen, ein Raster (4/8 px)… | Mesh (1262), Unfold (1860) |
| 1861–1916 | single-stroke font (4 x 6 grid, y down) | text, textW |
| 1916–1941 | single-line fonts for inscription and title (fonts.js); 'plain' is th… | shapeLine, partName |
| 1941–1994 | vector helpers | sub, cross, dot, len, d2, ekey, bez, hull, area2, shrink, overlap, inTri … +6 |
| 1994–2122 | flat pen patterns (after Plotter Friend): polylines around the origin… | pattern2D, clipInOut, clipOutside, inset, insetE, norm |
| 2122–4377 | main | unfold (2123), chainSegs (4358) |
| 4377–4467 | layers | layered |
| 4467–6160 | hold 'core': a square column through every layer, four wings pushed i… | orientPart (4770), nest (4794), toSVG (4892), $ (5014), cornerGrid (5021), status (5032), freshWord (5074), drawSample (5078), num (5085), sliceAt (5088), lidRing (5109), shape (5135), slug (5153), cleanTitle (5156), setTitle (5157), showWord (5158), ovId (5162), getOv (5163) … +44 |
