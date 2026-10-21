# Reticula Atelier

Web-Vorläufer der iPhone-App **KaleidoTangle** von Ulrike Günther.

- Webseite: https://uligausd.github.io/Reticula-Atelier/
- Nachfolger im App Store: https://apps.apple.com/app/kaleidotangle/id6820617420

## Geplante Abschaltung – Stand 21.10.2026

Ulrike möchte die Webseite künftig abschalten, da KaleidoTangle als native
kostenlose iPhone-App verfügbar ist. Ein Abschaltdatum ist noch nicht festgelegt.
Bis dahin bleiben die bisherigen Webseitenfunktionen verfügbar.

Über die gesamte Seitenbreite steht oberhalb von Menü und Arbeitsbereich ein
roter Hinweis mit weißer Schrift und hervorgehobenem App-Store-Knopf auf die baldige
Abschaltung mit einem Link zum App Store. Titel, Erklärung und Linkbeschriftung
wechseln mit der vorhandenen Sprachwahl DE / EN / ES. Der Hinweis nennt ausdrücklich
das iPhone; eine Android-Version wird nicht angekündigt. Ohne JavaScript ist der
deutsche Hinweis bereits im HTML enthalten.

## Technik und Veröffentlichung

Die Webseite besteht aus `index.html`; es gibt keinen Paketmanager, lokalen Build
oder automatisierte Tests. Bestehende externe Ressourcen werden unverändert genutzt.
GitHub Pages veröffentlicht den Hauptordner des Branches `main` automatisch.
Der Quelltext enthält außerdem eine ältere Netlify-Adresse in den Metadaten;
eine eventuell noch aktive Netlify-Veröffentlichung wurde nicht geprüft.

Prüfung am 21.10.2026: JavaScript-Syntax mit `node --check` erfolgreich,
alle drei Übersetzungen und eindeutige HTML-IDs geprüft, Git-Diff geprüft.
App-Store-Link liefert nach Weiterleitung HTTP 200.
Eine lokale Browser-Vorschau über `file:` wurde vom Browserwerkzeug blockiert.
GitHub Pages hat Commit `ca41a6f` erfolgreich veröffentlicht. Die öffentliche Seite
wurde im Browser geprüft: Hinweis auf Deutsch, Englisch und Spanisch durch
Bedienen der Sprachwahl bestätigt. Sichtprüfung bei 1280 × 720 und 390 × 844:
Hinweis und App-Store-Link vollständig sichtbar. Die bisherigen
Bildbearbeitungsfunktionen wurden nicht erneut vollständig getestet.

## Spätere Abschaltung

Noch nichts löschen oder deaktivieren. Abschalttermin und tatsächliche Abschaltung
werden von Ulrike gesondert beauftragt. Vor dem Entfernen prüfen, ob außer GitHub
Pages noch eine Netlify-Veröffentlichung existiert, und die gewünschte Aufbewahrung
des Quellcodes klären.

## Deutlicherer Hinweis (21.10.2026)

Auf Ulrikes Wunsch wurde der Hinweis aus der linken Menüleiste herausgenommen
und als rotes Banner über Menü und Arbeitsbereich gesetzt. Auf schmalen Geräten
stehen Text und Knopf untereinander; der verbleibende Platz wird weiterhin
zwischen Einstellungen und Vorschau aufgeteilt. GitHub Pages hat die Überarbeitung (`b81cc92`) erfolgreich veröffentlicht.
Die öffentliche Seite wurde bei 1280 × 720 und 390 × 844 visuell geprüft;
der rote Hinweis und der App-Store-Knopf sind vollständig sichtbar.
Alle drei Sprachen wurden über die Sprachknöpfe geprüft. JavaScript-Syntax
und Git-Diff sind ebenfalls geprüft.

## Sprachwahl und offizielles App-Store-Badge (21.10.2026)

Direkt im roten Banner stehen zusätzlich die ausgeschriebenen Sprachknöpfe
Deutsch / English / Español. Sie schalten die gesamte Webseite um und markieren
die gewählte Sprache. Die bisherigen DE-/EN-/ES-Knöpfe bleiben erhalten.
Der bisherige Textknopf ist durch Apples offizielles schwarzes Download-Badge
ersetzt. Das Badge wechselt ebenfalls zwischen Deutsch, Englisch und Spanisch.
Die unveränderten SVG-Dateien liegen in `assets/app-store-{de,en,es}.svg`.
Quelle: `https://toolbox.marketingtools.apple.com/api/v2/badges/download-on-the-app-store/black/`
mit den Sprachen `de-de`, `en-us`, `es-es`.
Richtlinien: https://developer.apple.com/app-store/marketing/guidelines/
Darstellung: 48 Pixel hoch, unverzerrt, mit mindestens 12 Pixel Freiraum.
JavaScript-Syntax, SVG-Dateien und Git-Diff geprüft. Öffentlich veröffentlicht
und im Browser bei 1280 × 720 und 390 × 844 geprüft: Sprachknöpfe sichtbar,
Umschaltung in alle drei Sprachen funktioniert, lokalisierte Badge-Dateien
werden erfolgreich geladen. Deutsches Badge auf beiden Größen visuell bestätigt.
