# Attrisjon og erosjon

Chairside journalstøtte for norske tannleger som skal dokumentere
patologisk tap av tannsubstans (attrisjon/erosjon) opp mot HELFO
innslagspunkt 9.

Nettversjon: https://marval1990.github.io/Attrisjon-erosjon/

## Bruk

Åpne `index.html`. Det er alt. Én fil, ingen avhengigheter, ingen CDN,
ingen byggesteg. Verktøyet fungerer offline ved å dobbeltklikke filen.

Arbeidsflyten er: kryss av det som passer, skriv resten, kopier
journalteksten. Hurtigvalgene blir til ferdige journalsetninger, og
journalteksten nederst oppdateres fortløpende.

## Innhold

1. **Funn og vurdering**
   - Alder, behandler og årsak
   - Anamnese og etiologiske faktorer (hurtigvalg)
   - Kliniske funn og symptomer (hurtigvalg + fritekst)
   - **Smith & Knight · tannkart** (valgfritt, kollapsbart): odontogram
     18–28 / 48–38 med fire flater per tann, score 0–4, flervalg for
     mange tenner samtidig, manglende tenner, angre
   - Samlet vurdering delt i funksjon, estetikk og tannhelse (hurtigvalg),
     skadeomfang i forhold til alder, samlet alvorlighet og fritekst
   - Basisdokumentasjon (foto, røntgen, skann/modeller) og bekreftelse på
     at alvorlighet er dokumentert før behandlingsstart
2. **Behandlingsplan**
   - Tannkart for planlagte tenner, med hurtigvalg for kjeve, front og alle
   - Materialvalg (kompositt / kroner / kroner kan vurderes på sikt). Kroner er
     unntaket og får egne hurtigvalg for begrunnelse (rotfylt og svekket tann,
     for lite gjenværende tannsubstans, gjentatte chippinger av kompositt, osv.)
   - Tiltak som hurtigvalg (bittheving i mm, Dahls prinsipp, støttekroner,
     etappevis behandling, okklusjonskontroll, bittskinne) + fritekst
   - Sykdomsaktivitet og langtidsprognose
   - Forebygging og oppfølging som hurtigvalg + kontrollintervall + fritekst
   - Andre behandlingssituasjoner (erstatning av tapt tann, slitasje av
     protetisk materiale)
3. **Journaltekst**
   - Ren tekst klar til å limes inn i journalsystemet. Tomme felt utelates.
     Teksten kan redigeres direkte i feltet; da slutter skjemaet å overskrive
     den, og «Generer på nytt fra skjemaet» henter ny tekst ved behov.
   - Format: «Med overskrifter» eller «Kompakt» (én linje per avsnitt).
     Topptekst med dato, pasientnummer og behandler kan slås av.
   - **Dokumentasjonssjekk**: viser om punktene rundskrivet spør etter er
     fylt ut (alder, årsak, funn, funksjon/estetikk, skadeomfang mot alder,
     dokumentasjon før oppstart, plan med tenner og materiale,
     kronebegrunnelse ved kroner, aktivitet/prognose, oppfølging). Klikk på
     et punkt for å hoppe til feltet. Dette er en utfyllingskontroll, ikke
     en vurdering av stønadsrett.
   - Kopier, last ned som tekstfil, vis rapport eller skriv ut.

Sticky bunnlinje viser dokumentasjonssjekken og har en egen «Kopier
journaltekst»-knapp, slik at teksten kan kopieres uansett hvor på siden
du er.

## Mobil

Under 800 px legges seksjonene under hverandre, hurtigvalgene får større
trykkflate, og tannkartet vises kjeve for kjeve.

## Personvern

Ingen data lagres eller sendes. Ingenting skrives til nettleserens lagring,
og verktøyet gjør ingen nettverkskall. Bruk kun pasientnummer, aldri navn
eller fødselsnummer.

## Design

CSS-en bygger på [perioberegning](https://github.com/Marval1990/perioberegning)
slik at de to verktøyene framstår som samme produkt: samme fargevariabler
(primærfarge `#1e6e5b`, alvorlighetsskalaen `--s1` til `--s4`), radius,
fontstack, header, nummererte seksjoner og print-CSS.

## Avgrensning

Verktøyet er dokumentasjonsstøtte, ikke en garanti for stønadsrett. Det
inneholder ingen takster, refusjonsbeløp eller pasientbetaling. HELFO
forhåndsgodkjenner ikke kasus; vurderingen gjøres etterskuddsvis, og
bevisbyrden ligger hos behandlende tannlege. Dokumentasjonssjekken er
verktøyets kontroll av at feltene er utfylt, ikke en godkjenning.
