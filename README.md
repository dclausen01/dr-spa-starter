# Startklar für den Digitalen Raum (DR-Starter SPA)

Lernpfad für die DR-Starterphase der SPA-Unterstufe am BBZ Rendsburg-Eckernförde – gebaut mit dem Lernpfad-Baukasten.

- **Web-Version:** https://dclausen01.github.io/dr-spa-starter/
- **Moodle-Kurs (Moodle 5):** [`moodle/dr-spa-starter_moodle5.mbz`](moodle/dr-spa-starter_moodle5.mbz) · Klickanleitung: [`moodle/ANLEITUNG_moodle5.md`](moodle/ANLEITUNG_moodle5.md)
- **Quelle:** `kurs.yaml`, `module/`, `seiten/`, `quellen.yaml` – nur hier ändern.
- **Erzeugt:** `docs/` (Web-Version für GitHub Pages) – nicht von Hand ändern, sondern neu bauen:

```
python3 <baukasten>/skripte/alles.py dr-spa-starter
rm -rf docs && cp -r ausgabe/web docs && touch docs/.nojekyll
cp ausgabe/moodle/*.mbz ausgabe/moodle/ANLEITUNG_moodle5.md moodle/
```

Bezug: DR-Konzept SPA, Materialpool (DR-Starterpaket), DR-Pass, Ablaufplan Starterphase.
