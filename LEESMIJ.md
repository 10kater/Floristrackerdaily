# Floris Barn

Persoonlijk dagelijks observatielogboek voor Floris. Progressive web app (PWA):
werkt op iPhone zonder Mac, zonder App Store, zonder account en zonder server-opslag.
Alle gegevens blijven op je iPhone.

## Bestanden
- index.html — de complete app
- sw.js — maakt de app offline bruikbaar
- manifest.webmanifest, icon-*.png — naam en icoon op het beginscherm

## Online zetten (eenmalig, ca. 10 minuten, gratis)
De bestanden moeten op een https-adres staan, zodat Safari er een echte app van kan maken.
Daar komen alleen deze app-bestanden te staan, nooit je gegevens van Floris.

GitHub Pages (werkt vanaf elke computer of vanuit Safari op de iPhone):
1. Maak een gratis account op github.com.
2. Maak een nieuwe repository, bijvoorbeeld `floris-barn`, zet hem op Public.
3. Kies "uploading an existing file" en upload alle bestanden uit deze map (niet de map zelf).
4. Ga naar Settings > Pages > Branch: `main`, map `/ (root)`, en sla op.
5. Na een minuut staat de app op `https://<jouw-naam>.github.io/floris-barn/`.

## Installeren op de iPhone
1. Open dat adres in Safari.
2. Tik op Deel (vierkant met pijl) > Zet op beginscherm > Voeg toe.
3. Open Floris Barn voortaan via het icoon. Hij opent schermvullend en werkt ook offline.

## Snel openen (in plaats van een widget)
Een webapp kan op de iPhone geen echte widget zijn. Zet het icoon in het dock (de onderste balk met vier apps):
1. Houd een app in het dock ingedrukt > Wijzig beginscherm, en sleep die app omhoog om een plek vrij te maken.
2. Sleep het Floris Barn-icoon naar die lege plek in het dock.
3. Tik rechtsboven op Gereed.
Het dock staat op elke pagina van je beginscherm, dus de dagcheck is altijd één tik weg.

## Herinnering
Aanpassen > Herinnering > "Zet dagelijkse herinnering in Agenda" maakt één terugkerende melding per dag.
Alternatief: Opdrachten-app > Automatisering > Tijdstip 19:30 > Open URL (het adres van de app).

## Weer
Staat standaard aan, vast voor Ouderkerk aan den IJssel. Dagwaarden komen van Open-Meteo (gratis, geen account).
Er gaat nooit informatie over Floris naar buiten.

## Foto's en documenten
Worden lokaal op je iPhone bewaard. Neem ze mee in je back-up via Aanpassen > Gegevens.

## Dierenartsoverzicht
Trends > Dierenartsoverzicht maken > Delen als PDF. Kies daarna Mail of WhatsApp.

## Back-ups
Aanpassen > Gegevens > Back-up maken. Bewaar het bestand in Bestanden of iCloud Drive.
Let op: als je in iOS de websitegegevens van Safari wist, wordt ook de app-data gewist.

## Updates
Nieuwe versie van index.html uploaden naar dezelfde plek. Je gegevens blijven staan.
