# Gespann-Navi (Prototyp)

Web-App für Auto + Wohnwagen. Öffnen: `index.html` im Browser (Chrome, Edge, Safari) doppelklicken.

## Was sie kann
- **Mein Gespann:** Höhe, Breite, Länge, Gewicht, Tempo (Landstraße 80 / Autobahn 100), Kraftstoff, Verbrauch, Tankgröße. Wird im Browser gespeichert.
- **3 Routen:** Kürzeste, Schnellste, Spritsparend. Alle werden mit LKW-Routing (Valhalla) berechnet, das Durchfahrtshöhen, -breiten, Längen- und Gewichtsbeschränkungen aus OpenStreetMap beachtet und kleine/unbefestigte Straßen meidet.
- **Realistische Fahrzeit:** pro Straßenabschnitt mit deinem Tempo und den Gespann-Tempolimits des jeweiligen Landes (z. B. Italien/Schweiz 80 auf der Autobahn).
- **Sprit:** Verbrauch je Abschnitt (Tempo, Ortsdurchfahrten, Höhenmeter) und Kosten mit Landes-Durchschnittspreisen.
- **Maut:** Streckenmaut (FR, IT, ES, PT, HR, PL …), Vignetten (AT, CH inkl. Anhänger, SI, CZ, SK, HU …) und Sondermautstrecken in Österreich als Schätzung.
- **Tankplan:** berechnet, wo du tanken musst, und sucht Tankstellen bis X km neben der Route. Live-Preise: Frankreich automatisch, Deutschland mit kostenlosem Tankerkönig-Key.

## Datenquellen (alle kostenlos, ohne Anmeldung)
Valhalla (FOSSGIS-Server), Photon (Ortssuche), Overpass (Tankstellen), OpenStreetMap-Karten, prix-carburants.gouv.fr, optional Tankerkönig.
Die öffentlichen Server sind für Tests gedacht, nicht für viele Nutzer.

## Grenzen des Prototyps
- Maut-, Tempo- und Preiswerte sind Richtwerte (Stand Ende 2026), bitte vor der Fahrt prüfen.
- Engstellen werden nur erkannt, wenn sie in OpenStreetMap eingetragen sind.
- Keine Sprachnavigation während der Fahrt; die Route ist zur Planung gedacht.
