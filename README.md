# Haugaland Bygg og Malerservice AS — nettside (demo/designforslag)

Énsides nettside laget som salgspresentasjon til Haugaland Bygg og Malerservice AS
(maler-, snekker- og byggtjenester på Haugalandet).

## Innhold
- `index.html` — hele nettsiden (HTML + CSS + litt JS, alt i én fil)
- `assets/img/` — bedriftens egne bilder (hentet fra Facebook-sida, beskåret og nettoptimalisert)

## Identitet
Farger og motiv er hentet fra **firmabilen** (sølvgrå Mercedes Vito) og **HBM-logoen**:
- Marineblå `#0E2A45`, signalblå `#1E73B7`, lys himmelblå `#54A8E0`, sølvgrå og hvitt
- «Pixel»-stripa fra bilen er brukt som gjennomgående grafisk detalj

## Ekte data brukt
- Org.nr **933 868 095**, Imslandgata 8, 5521 Haugesund
- Etablert 2024, 5 ansatte, daglig leder Yanko Yankov
- Telefon **455 03 539** (fra firmabil/skilt/Facebook)
- Tjenester og prosjekttyper er basert på bedriftens egne Facebook-innlegg

## ⚠️ Plassholdere som må erstattes før publisering
- **E-post `post@haugalandbms.no`** er en plassholder (bedriften har ingen registrert e-post/nettside ennå)
- **Kontaktskjemaet** er en demo — det sender ingenting. Kobles til f.eks. Formspree/e-post ved lansering
- Sted-taggene på prosjektkortene (Kopervik/Haugesund/Karmøy) er antatt ut fra innleggene — bør bekreftes

## Vise siden lokalt
Åpne `index.html` i nettleser, eller kjør en enkel server:
```bash
npx serve .
```

## Publisere (GitHub Pages)
Legg filene i et repo og slå på Pages (branch `main`, mappe `/root`).
Siden er statisk og trenger ingen bygg.
