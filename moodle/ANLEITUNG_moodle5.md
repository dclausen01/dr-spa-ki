# KI verantwortlich nutzen – Moodle-Kurs von Hand einrichten

Normalerweise geht es schneller mit der Kurssicherung:
**Kurs › Mehr › Wiederverwendung › Wiederherstellen** → `dr-spa-ki_moodle5.mbz` hochladen → „In diesen Kurs, Inhalte hinzufügen“ → durchklicken. Diese Anleitung ist die Rückfallebene, falls Wiederherstellen nicht erlaubt ist.

## Vorbereitung

- Kurs › Einstellungen › **Abschlussverfolgung: Ja**
- Kursformat: Themen (Moodle 5: Unterabschnitte müssen von der Moodle-Administration aktiviert sein)

## Einstellungen für jedes Lernpaket

Aktivität **Lernpaket** (SCORM) anlegen, ZIP aus `lernpakete/` hochladen, dann:

- Darstellung: **Anzeige des Pakets: Aktuelles Fenster** · Breite 100 % · Höhe 500
- Darstellung: **Kursstruktur anzeigen: Deaktiviert** · **Navigation anzeigen: Nein** · **Struktur-Seite überspringen: Immer** · Versuchsstatus anzeigen: Nein
- Bewertung: Höchstbewertung 100, Bewertungsmethode: Höchste Bewertung
- Versuchsverwaltung: Beherrschungswert überschreibt Status: Ja
- Aktivitätsabschluss: **Bedingungen erfüllt** → **Status erforderlich: Abgeschlossen** (nur „abgeschlossen“ anhaken)
- Ausnahme Startseite und Einstufungstests: **kein Aktivitätsabschluss**; die Startseite außerdem Bewertung 0.

## Abschnitt „Allgemeines“ (ganz oben)

- Lernpaket **🧭 Mein Lernpfad – hier geht's los** – `lernpakete/dr-spa-ki_start_scorm2004.zip`
- Lernpaket **🎯 Einstufungstest: direkt zu Im Beruf** – `lernpakete/dr-spa-ki_einstufung-im-beruf_scorm2004.zip`

## Abschnitt „🌱 Verstehen und Anwenden“

- Lernpaket **V1 · Wie funktioniert generative KI?** – `lernpakete/dr-spa-ki_v1_scorm2004.zip`
- Lernpaket **V2 · KI-Ampel und Kennzeichnung** – `lernpakete/dr-spa-ki_v2_scorm2004.zip` – Voraussetzung: „V1 · Wie funktioniert generative KI?“ abgeschlossen
- Lernpaket **V3 · Gut fragen, kritisch prüfen** – `lernpakete/dr-spa-ki_v3_scorm2004.zip` – Voraussetzung: „V2 · KI-Ampel und Kennzeichnung“ abgeschlossen
- Unterabschnitt **★ Meilenstein: KI-Antwort prüfen** – Voraussetzung: „V3 · Gut fragen, kritisch prüfen“ abgeschlossen
  - Lernpaket **★ Meilenstein: KI-Antwort prüfen – Auftrag & Checkliste** – `lernpakete/dr-spa-ki_vm_scorm2004.zip`
  - Aufgabe **📤 Meilenstein: KI-Prüfung abgeben** – Dateiabgabe, höchstens 1 Datei(en), Dateitypen .pdf,.docx,.odt, 100 Punkte, Abschluss: „Abgabe erforderlich“
    Beschreibung: Laden Sie Ihre Prüfung (berichtigte Antwort + KI-Protokoll, ca. eine Seite) hoch. Dateiname zum Beispiel `2026-11-20 KI-Pruefung_Nachname,Vorname.pdf`.
    Bewertungsmethode **Bewertungsraster** mit diesen Kriterien:
    - Fehler finden: nicht erreicht (0 P.) · erreicht: mindestens drei Fehler oder Schwächen benannt (2 P.) · besonders gut: alle Fehler gefunden und nach Art geordnet (Fakt, Fachlichkeit, Bias …) (3 P.)
    - Berichtigen: nicht erreicht (0 P.) · erreicht: Fehler mit einer verlässlichen Quelle berichtigt (2 P.) · besonders gut: Berichtigung präzise und mit vollständiger Quellenangabe (3 P.)
    - KI-Protokoll: nicht erreicht (0 P.) · erreicht: Prompt, Antwort und eigene Änderungen festgehalten (2 P.) · besonders gut: Entscheidungen (übernehmen/ändern/verwerfen) begründet (3 P.)
    - Reflexion: nicht erreicht (0 P.) · erreicht: ein Satz zu Nutzen und Grenzen der KI bei dieser Aufgabe (2 P.) · besonders gut: Übertrag auf den Beruf (3 P.)

## Abschnitt „🚀 Im Beruf“

Voraussetzung am Abschnitt (Einschränkung: Aktivitätsabschluss bzw. Bewertung, verknüpft mit „mindestens eine“): „📤 Meilenstein: KI-Prüfung abgeben“ abgeschlossen **oder** „🎯 Einstufungstest: direkt zu Im Beruf“ mit mindestens 80 % bewertet.

- Lernpaket **B1 · Was nie in die KI gehört** – `lernpakete/dr-spa-ki_b1_scorm2004.zip`
- Unterabschnitt **B2 · KI-Texte prüfen: der Elternbrief** – Voraussetzung: „B1 · Was nie in die KI gehört“ abgeschlossen
  - Lernpaket **B2 · KI-Texte prüfen: der Elternbrief** – `lernpakete/dr-spa-ki_b2_scorm2004.zip`
  - Aufgabe **📤 Zwischenabgabe: korrigierter Elternbrief** – Dateiabgabe, höchstens 1 Datei(en), Dateitypen .pdf,.docx,.odt, 10 Punkte, Abschluss: „Abgabe erforderlich“
    Beschreibung: Laden Sie Ihren überarbeiteten Elternbrief hoch. Markieren Sie Ihre wichtigsten Änderungen oder listen Sie sie kurz darunter auf.
- Lernpaket **B3 · KI in Kita, OGS und Grundschule** – `lernpakete/dr-spa-ki_b3_scorm2004.zip` – Voraussetzung: „B2 · KI-Texte prüfen: der Elternbrief“ abgeschlossen
- Unterabschnitt **★ Meilenstein: Einsatz oder Verzicht?** – Voraussetzung: „B3 · KI in Kita, OGS und Grundschule“ abgeschlossen
  - Lernpaket **★ Meilenstein: Einsatz oder Verzicht? – Auftrag & Checkliste** – `lernpakete/dr-spa-ki_bm_scorm2004.zip`
  - Aufgabe **📤 Meilenstein: Entscheidung abgeben** – Dateiabgabe, höchstens 1 Datei(en), Dateitypen .pdf,.docx,.odt, 100 Punkte, Abschluss: „Abgabe erforderlich“
    Beschreibung: Laden Sie Ihre begründete Entscheidung hoch (ca. 1–2 Seiten). Dateiname zum Beispiel `2026-11-27 KI-Entscheidung_Nachname,Vorname.pdf`.
    Bewertungsmethode **Bewertungsraster** mit diesen Kriterien:
    - Situation: nicht erreicht (0 P.) · erreicht: Situation, Ziel und Beteiligte richtig beschrieben (2 P.) · besonders gut: Interessen von Kindern, Eltern und Team ausdrücklich berücksichtigt (3 P.)
    - Abwägung: nicht erreicht (0 P.) · erreicht: mindestens zwei Chancen und zwei Risiken benannt (2 P.) · besonders gut: gewichtet und mit Inhalten aus dem Lernpfad begründet (3 P.)
    - Entscheidung: nicht erreicht (0 P.) · erreicht: klare Entscheidung (Einsatz, Teil-Einsatz oder Verzicht) mit Begründung (2 P.) · besonders gut: Alternative ohne KI bzw. mit anderer KI-Nutzung mitgedacht (3 P.)
    - Regeln: nicht erreicht (0 P.) · erreicht: Regeln zu Datenschutz, Prüfung und Kennzeichnung festgelegt (2 P.) · besonders gut: Regeln konkret und im Alltag umsetzbar (3 P.)
    - Haltung: nicht erreicht (0 P.) · erreicht: Bezug zur eigenen Rolle als Fachkraft (2 P.) · besonders gut: Bezug zu Bildungsleitlinien oder KI-Kompetenzmodell (3 P.)

