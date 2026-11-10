# KI verantwortlich nutzen (DR-Lernpfad SPA, K8)

Querschnitts-Lernpfad für die SPA am BBZ Rendsburg-Eckernförde – gebaut mit dem Lernpfad-Baukasten.

- **Web-Version:** https://dclausen01.github.io/dr-spa-ki/
- **Moodle-Kurs (Moodle 5):** `moodle/dr-spa-ki_moodle5.mbz` · Klickanleitung `moodle/ANLEITUNG_moodle5.md`
- **Quelle:** `kurs.yaml`, `module/`, `seiten/`, `quellen.yaml` – nur hier ändern.
- **Erzeugt:** `docs/` (GitHub Pages) und `moodle/` – nicht von Hand ändern, sondern neu bauen:

```
python3 <baukasten>/skripte/alles.py dr-spa-ki
rm -rf docs && cp -r ausgabe/web docs && touch docs/.nojekyll
cp ausgabe/moodle/*.mbz ausgabe/moodle/ANLEITUNG_moodle5.md moodle/
```
