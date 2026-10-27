# Personvern i Varsku

Sist oppdatert: 25. oktober 2026

Varsku er en Garmin-app som viser offisielle farevarsler for flom, jordskred og farlig vær der du er.

## Hva som sendes

For å finne varslene sender appen posisjonen din, avrundet til to desimaler (omtrent 1 km), til:

- Kartverkets åpne kommune-API (ws.geonorge.no), for å finne kommunen du er i
- Meteorologisk institutts åpne API (api.met.no), for farevarsler for vær
- NVEs åpne API (api01.nve.no), for snøskredvarselet

Flom- og jordskredvarslene hentes fra NVE med kommunenummeret, ikke med posisjonen.

Forespørslene går fra klokka via Garmin Connect-appen på telefonen. Mottakerne ser også IP-adressen de kommer fra.

På de fleste klokker hentes varslene i bakgrunnen omtrent én gang i timen, med posisjonen fra sist appen var åpen.

## Hva som lagres

Siste posisjon og siste varsler lagres bare på klokka. De slettes når du avinstallerer appen.

## Hva utvikleren får vite

Ingenting. Det finnes ingen server bak appen, og ingen analyse, sporing eller reklame. Det er heller ingen konto eller innlogging.

## Andre

Kartverket, Meteorologisk institutt og NVE mottar forespørslene. Garmin formidler dem via telefonen og håndterer installasjonen i Connect IQ Store. Alle har egne personvernerklæringer.

## Spørsmål

Send en e-post til kristoffer.skaret@gmail.com.

## Forbehold

Appen viser offisielle farevarsler fra NVE og Meteorologisk institutt og er veiledende. Sjekk alltid varsom.no og met.no og gjør egne vurderinger. Appen er ikke tilknyttet NVE, Varsom, Meteorologisk institutt, Yr eller Kartverket.

---

# Privacy in Varsku

Last updated: 25 October 2026

Varsku is a Garmin app that shows official warnings for floods, landslides and dangerous weather where you are.

## What is sent

To find the warnings, the app sends your location, rounded to two decimals (about 1 km), to:

- the Norwegian Mapping Authority's open municipality API (ws.geonorge.no), to find the municipality you are in
- the Norwegian Meteorological Institute's open API (api.met.no), for weather warnings
- NVE's open API (api01.nve.no), for the avalanche forecast

Flood and landslide warnings are fetched from NVE by municipality number, not by location.

The requests go from the watch via the Garmin Connect app on your phone. The recipients also see the IP address they come from.

On most watches the warnings are fetched in the background about once an hour, using the location from the last time the app was open.

## What is stored

Your last location and the last warnings are stored only on the watch. They are deleted when you uninstall the app.

## What the developer learns

Nothing. There is no server behind the app, and no analytics, tracking or ads. There is no account or login either.

## Others

The Norwegian Mapping Authority, the Norwegian Meteorological Institute and NVE receive the requests. Garmin relays them via your phone and handles the installation in the Connect IQ Store. All have their own privacy policies.

## Questions

Send an email to kristoffer.skaret@gmail.com.

## Disclaimer

The app shows official warnings from NVE and the Norwegian Meteorological Institute and is for guidance only. Always check varsom.no and met.no and make your own assessment. The app is not affiliated with NVE, Varsom, the Norwegian Meteorological Institute, Yr or the Norwegian Mapping Authority.
