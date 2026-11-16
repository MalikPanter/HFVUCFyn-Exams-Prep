# Kravspecifikation — elevens PDF-pakke

**Dette er et internt designgrundlag. Alle slutprodukter til eleven skal være PDF-filer.**

## Grundprincipper

- **Ingen obligatorisk app, registrering, download af værktøj, JSON, DOCX, HTML eller indeksdatabase.**
- Alle væsentlige oplysninger skal stå inde i PDF-filerne som tekst, så `Ctrl+F` virker **offline**.
- Ét dokument skal kunne læses selvstændigt uden netforbindelse. Kilde-links er supplerende.
- Materialer fra elevens oprindelige filer citeres ved **præcis original filbetegnelse** og dokumenteret side/afsnit, når det kan udledes.
- En henvisning til en fil betyder ikke, at filen medfølger PDF-pakken. Angiv altid, hvis den originale fil også skal downloades separat for at kunne åbnes offline.
- Opret nye outputfiler i en separat mappe; **rør aldrig originalerne**.
- Brug tidsstempel og versionsoplysninger i navn/metadata. Overskriv ikke tidligere output.

## Minimumsleverancer

### `00_START_HER_ÅÅÅÅ-MM-DD.pdf`

- Fag, niveau, type (toårigt hf/hf-enkeltfag), dato og kildegrundlag.
- Dækning af tilgængelige originalfiler: fundet/læst/delvist/ikke læst.
- Indholdsfortegnelse for PDF-pakken, læseforslag, begrænsninger.
- **Offline-vejledning**: hvilke filer der skal ligge lokalt, og test af søgning uden internet.
- Disclaimer om at tilladte hjælpemidler varierer efter prøve.

### `01_EMNEINDEKS_ÅÅÅÅ-MM-DD.pdf`

To supplerende registre, begge som ægte, søgbar tekst:

**Alfabetisk:** Emne, variationer og staveformer, konkret oprindelig kildefil, verificeret side/afsnit, kort forklaring.

**Tematisk:** Overemne → underemne → steder i originalmaterialet.

Eksempel (kun illustration):

| Emne | Også søg efter | Original kilde | Placering | Status |
|---|---|---|---|---|
| Drivhuseffekt | drivhusgasser, CO₂, klima | `Naturfag_notater.pdf` | s. 3–5 | **EKSEMPEL — IKKE VERIFICERET** |

**HUSK:** Skriv `Side ikke verificeret`, hvis ingen sikker reference findes. Opfind aldrig henvisninger.

### `02_FILOVERSIGT_ÅÅÅÅ-MM-DD.pdf`

| Oprindeligt filnavn | Placering (hvis kendt) | Format | Læst status | Centrale emner | Fejl/usikkerheder |
|---|---|---|---|---|---|

Rapporten skal tydeligt oplyse, om resultatet dækker en **udvalgt mappe** eller hele den ønskede samling. Enhver begrænsning skal fremgå.

### `03_LAEREPLANSDAEKNING_ÅÅÅÅ-MM-DD.pdf`

- Medtag et selvstændigt **kompetence- og metodeindeks**: faglige mål, konkrete måder at demonstrere dem på og dokumenteret elevmateriale. Et simpelt emneord er ikke nok til at konkludere, at kompetencen er dækket.
- Angiv **præcis** officiel kilde, uddannelsestype, årgang, dato for tjek og evt. uafklaret overgang.
- Registrér hvert relevant krav/emne med kildefiler og status: `dokumenteret`, `delvist dokumenteret`, `ikke fundet i tilgængelige filer` eller `ikke vurderet`.
- `Ikke fundet` betyder aldrig `ikke undervist`.
- Undlad at kalde et **vejledende** emne for et bindende eksamenskrav.

### `04_REPETITIONSNOTER_ÅÅÅÅ-MM-DD.pdf`

- Korte og fagligt præcise forklaringer med selvstændigt skrevne eksempler.
- Marker `AI-genereret opsummering` og skeln fra verificerede originalkilder.
- Hvis relevant: formler, definitioner, eksempler, almindelige misforståelser og henvisninger.
- Undgå at kopiere større ophavsretligt beskyttede passager.

### `05_EKSAMENSOVERSIGT_ÅÅÅÅ-MM-DD.pdf`

- **For hver konkret prøve**: Skriv hvilken fag-/niveau-/uddannelses- og læreplansårgang der er undersøgt, og om dens gyldighed er verificeret for elevens termin.
- **Hvad bliver du bedømt på?** Forklar punkt 2.1 og 4.3 i den gældende læreplan i elevsprog og henvis til officielt dokument og præcist punkt. Skeln mellem bedømmelseskriterier og generelle tips.
- Forklar **hvad eleven kan gøre i praksis** for at demonstrere kriterierne, men mærk AI-eksempler som vejledende, ikke som autentiske prøveopgaver.
- Særligt ved faggrupper skal interne, eksterne og enkeltfaglige prøver holdes adskilt; ved sprogfag skal mundtlige og skriftlige kriterier holdes adskilt; ved praktiske fag medtages begge præstationsformer.
- Aktuelt verificerede prøveformer, regler, officielle referencer og gyldighed.
- Separat afsnit: `Skal bekræftes med skolen`, hvis noget er uklart.
- **Ingen** generalisering om, at PDF'er altid må anvendes under prøven.

### `06_OFFLINE_STUDIEKOMPENDIUM_ÅÅÅÅ-MM-DD.pdf`

- **Vægt fagets dokumenterede kompetencer og bedømmelseskriterier**, ikke bare en generisk emneliste; include praktiske metoder, tekstanalyse, kilder, regnebegrundelser eller forsøgsdata efter faget.
- Ét selvstændigt søgbart hæfte med korte, selvstændigt formulerede forklaringer af de emner, som reelt kunne udledes af elevens dokumenter og verificerede læreplanskrav.
- Skal fungere som **offline repetition uden adgang til originalfilerne**. Medtag nødvendige forklaringer, definitioner, regneeksempler og tydeligt mærkede supplerende noter.
- Skal tydeligt vise dokumenteret/ikke dokumenteret indhold og må ikke foregive at være en komplet gengivelse af enhver originalfil.
- Genudgiv ikke hele beskyttede lærebøger, beskyttede billeder eller længere beskyttede tekster. Hvis eleven lovligt selv ejer rettigheder til egne noter, kan vedkommende særskilt bede om en ny PDF-eksportkopi; originalen må stadig ikke ændres.

## Sprog og læsbarhed (obligatorisk)

**PDF'erne skal kunne forstås af en almindelig HF-elev uden at kende emnet i forvejen.** Gør dem lette at skimme, men komplette nok til en faglig forklaring.

- **Brug fagets undervisningssprog**: fx dansk for historie/matematik og engelsk for Engelsk B, medmindre eleven oplyser noget andet. Oversæt ikke fagudtryk forkert for at gøre dem lettere.
- Skriv korte sætninger og afsnit. Ét centralt budskab ad gangen.
- Definér vigtige fagord første gang, de bruges. Tilføj en kort ordliste ved behov.
- Brug et **konkret eksempel** til hvert kompliceret emne, når det kan gøres fagligt korrekt.
- Forklar mellemled, så eleven kan forstå **hvordan** og **hvorfor** – ikke bare huske en definition.
- Foretræk meningsfulde overskrifter, små underafsnit, punktopstillinger og tydelige sider frem for store tekstblokke.
- Eksempel på emneside: `Kort forklaret` → `Fagord` → `Sådan hænger det sammen` → `Eksempel` → `Kilde i mine noter`.
- For matematik: vis mellemregninger og forklar regneregler. For naturfag: forklar årsager, processer og konsekvenser. For sprogfag: vis korte sætninger på fagets sprog.
- Forenkling må **ikke** udelade nødvendige faglige præciseringer eller fremstille gæt som fakta.
- Gør det tydeligt, hvad der er fra kilder, og hvad AI selv har formuleret.

## Formatering

- A4, fornuftige margener, tydelige overskrifter, læselig størrelse og sidetal.
- Kopiérbar/søgbar tekst (ikke bare rasterbilleder). Brug OCR eller transskription kun hvis teknisk muligt og nøjagtigheden kan kontrolleres.
- Dansk og korrekte danske tegn. For fag med anden undervisningssprog: bevar relevante fagtermer.
- Tydelige henvisninger og statusmarkeringer; farve alene må ikke bære betydningen.
- Klikbare PDF-bogmærker eller indholdsfortegnelse, hvis værktøjet understøtter det.
- Tjek PDF'en ved at åbne den og søge efter mindst tre emner samt prøve at læse den uden netadgang.

## Versionering uden at ændre originaler

Forslag: `AI-Generated/2026-11-16-01/`, derefter `2026-11-16-02/`. Datoen i eksemplet er **ikke** et krav. Brug ny mappe eller unikke, nye filnavne ved hver kørsel.

Hvis ChatGPT ikke har adgang til at gemme i brugerens foretrukne lagring, leveres PDF'erne som **downloadbare filer i samtalen**, uden at kræve en ny udbyder.
