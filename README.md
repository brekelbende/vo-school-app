# Middelbare scholen Utrecht vergelijken

E�n statische HTML-pagina om de middelbare scholen in Utrecht te vergelijken op niveau, richting, onderwijsaanpak, fietstijd vanaf je eigen adres en examenresultaten.

Live: https://vo.wurq.nl

## Privacy

Er is geen server en er wordt niets opgeslagen buiten je eigen browser (localStorage). Je adres gaat alleen eenmalig naar de PDOK Locatieserver om er coördinaten van te maken. Via "Opslaan als bestand" kun je je keuzes exporteren als JSON.

Werkt de app niet goed (bijvoorbeeld door oude opgeslagen gegevens)? Met "Alles wissen" onderaan de pagina, of door `?reset` achter het adres te zetten, wis je alle keuzes in deze browser en begin je opnieuw.

## Bronnen

- Examencijfers: DUO Open Onderwijsdata, geslaagden, gezakten en examencijfers 2024-2025 (CC-BY 4.0)
- Schoollijst: Scholen op de kaart en De VO Gids
- Websites van de scholen: eigen opzoekwerk (november 2026)
- Adressen scholen: Google Maps; eigen adres: PDOK Locatieserver
- Open dagen: websites van de scholen, aangevuld met de Open Dagen Planner van De VO Gids (november 2026)

Niveaus en kenmerken zijn een startpunt, geen officiële registratie.

## Bijwerken examencijfers

Download het nieuwe bestand "Geslaagden, gezakten en examencijfers" bij DUO en laad het in de app, of vervang `EMBED_EXAM` in `index.html`.
