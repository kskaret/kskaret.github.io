# Personvern i Skredfare

Sist oppdatert: 25. oktober 2026

Skredfare er en Garmin-app som henter snøskredvarselet fra NVE for området du er i.

## Hva som sendes

For å finne riktig varslingsregion sender appen posisjonen din til NVEs åpne API (api01.nve.no). Posisjonen rundes av til to desimaler først, altså omtrent 1 km.

Forespørselen går fra klokka via Garmin Connect-appen på telefonen. NVE ser også IP-adressen den kommer fra.

Har du valgt varslingsregioner i appens meny, hentes varselet for dem fra NVE med regionnummeret. Da sendes ikke posisjonen.

Når du åpner detaljsiden, henter appen resten av varselet fra NVE. Da sendes bare nummeret på varslingsregionen, ikke posisjonen.

## Hva som lagres

Siste posisjon, regionene du har valgt og siste varsel lagres bare på klokka. Det slettes når du avinstallerer appen.

## Hva utvikleren får vite

Ingenting. Det finnes ingen server bak appen, og ingen analyse, sporing eller reklame. Det er heller ingen konto eller innlogging.

## Andre

NVE mottar forespørselen. Garmin formidler den via telefonen og håndterer kjøpet i Connect IQ Store. Begge har egne personvernerklæringer.

## Spørsmål

Send en epost til kristoffer.skaret@gmail.com.

## Forbehold

Appen viser NVEs offisielle skredvarsel og er veiledende. Sjekk alltid varsom.no og gjør egne vurderinger. Appen er ikke tilknyttet NVE eller Varsom.

---

# Privacy in Skredfare

Last updated: 25 October 2026

Skredfare is a Garmin app that fetches the avalanche forecast from NVE (the Norwegian Water Resources and Energy Directorate) for the area you are in.

## What is sent

To find the right forecast region, the app sends your location to NVE's open API (api01.nve.no). The location is rounded to two decimals first, which is about 1 km.

The request goes from the watch via the Garmin Connect app on your phone. NVE also sees the IP address it comes from.

If you choose forecast regions in the app menu, their forecasts are fetched from NVE by region number. Your location is not sent then.

When you open the detail page, the app fetches the rest of the forecast from NVE. Only the number of the forecast region is sent then, not your location.

## What is stored

Your last location, the regions you have chosen and the last forecast are stored only on the watch. They are deleted when you uninstall the app.

## What the developer learns

Nothing. There is no server behind the app, and no analytics, tracking or ads. There is no account or login either.

## Others

NVE receives the request. Garmin relays it via your phone and handles the purchase in the Connect IQ Store. Both have their own privacy policies.

## Questions

Send an email to kristoffer.skaret@gmail.com.

## Disclaimer

The app shows NVE's official avalanche forecast and is for guidance only. Always check varsom.no and make your own assessment. The app is not affiliated with NVE or Varsom.
