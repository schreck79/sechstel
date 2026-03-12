Dienstplan Formular-Generator (BVG / TV-N Berlin)

Dieses Tool ermöglicht es Fahrpersonal im ÖPNV, Dienstpläne im PDF-Format hochzuladen und automatisch einen "Antrag auf Anrechnung von Verspätungen auf die unbezahlte Lenkzeitunterbrechung" zu erstellen.

Features

Intelligente PDF-Analyse: Extrahiert automatisch Linie, Kurs, Soll-Ankunft und Pausenzeiten.

Automatisches Filtering: Es werden nur Wendezeiten übernommen, die tatsächlich unbezahlte Pausenbestandteile (KK-Minuten) enthalten.

Original-Layout: Das erzeugte Web-Formular entspricht dem offiziellen BVG-Antragsformular.

Druckoptimiert: Ein spezielles Druck-Stylesheet sorgt für ein sauberes A4-Ergebnis.

Installation / Nutzung auf GitHub

Erstelle ein neues Repository auf GitHub.

Lade die Datei index.html in dieses Repository hoch.

Gehe zu den Settings des Repositories -> Pages.

Wähle den main Branch als Quelle aus und speichere.

Nach wenigen Minuten ist deine Web-App unter https://DEIN-NUTZERNAME.github.io/REPOT-NAME/ erreichbar.

Technische Details

Frontend: HTML5, CSS3 (Tailwind CSS), JavaScript.

PDF-Parsing: PDF.js von Mozilla.

KI-Logik: Google Gemini API (Modell: gemini-2.5-flash-preview-09-2025).

API Hinweis

Die App nutzt die Gemini API zur Strukturierung der PDF-Daten. In dieser Version wird der API-Schlüssel über die Umgebung bereitgestellt. Für eine private Nutzung außerhalb dieser Umgebung muss ein eigener API-Key in der index.html unter const apiKey = "..." eingetragen werden.