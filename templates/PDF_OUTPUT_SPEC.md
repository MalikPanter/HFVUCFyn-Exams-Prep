# Kravspecifikation — elevens PDF-pakke

**Dette er et internt designgrundlag. Alle slutprodukter til eleven skal være PDF-filer.** Det **store søgeindeks per fag er det primære produkt**. Læs også [MULTIMEDIA_AND_INDEX_WORKFLOW.md](MULTIMEDIA_AND_INDEX_WORKFLOW.md), som fastlægger rækkefølge, placering og håndtering af billeder, lyd og video.

## Grundprincipper

- **Ingen obligatorisk app, registrering, download af værktøj, JSON, DOCX, HTML eller indeksdatabase.**
- Alle væsentlige oplysninger skal stå inde i PDF-filerne som tekst, så `Ctrl+F` virker **offline**.
- Ét dokument skal kunne læses selvstændigt uden netforbindelse. Kilde-links er supplerende.
- Materialer fra elevens oprindelige filer citeres ved **præcis original filbetegnelse** og dokumenteret side/afsnit, når det kan udledes.
- En henvisning til en fil betyder ikke, at filen medfølger PDF-pakken. Angiv altid, hvis den originale fil også skal downloades separat for at kunne åbnes offline.
- Organisér **referencer virtuelt**, ikke elevens originale mapper og filer. Opret nye supplerende outputfiler i en separat mappe; **rør aldrig originalerne**. Som eneste undtagelse fra placeringen må det nye primære indeks placeres direkte i elevens eksisterende fagmappe, når skriveadgang og brugerens valgte område tillader det.
- Brug tidsstempel og versionsoplysninger i navn/metadata. Overskriv ikke tidligere output.

## Minimumsleverancer

### `00_FIND_ALT_HER_<FAG>_<ÅÅÅÅ-MM-DD-VERSION>.pdf` — FÆLLES SØGEPDF

**Dette er den vigtigste PDF og oprettes TIL SIDST, per fag**, når de andre nye PDF'er allerede er genereret og deres faktiske filnavne/sidetal er kendt. Den må gerne være omfattende, men skal være let at navigere.

- **Placering:** Direkte øverst i elevens eksisterende fagmappe som en helt ny fil (hvis oprettelse i den valgte lagring er mulig), **ikke blandet med de supplerende PDF'er**. Hvis der ikke er fagmapper, brug en ny fagopdelt outputmappe uden at ændre originalerne. Hvis skrivning ikke er mulig, levér index-PDF'en **særskilt i samtalen** til manuel placering.
- **Omfang:** Alle faktisk gennemgåede originale dokumenter, **selvstændige JPG/JPEG/PNG/WEBP-billedfiler**, indlejrede figurer, præsentationer, tilgængelige audio/video + alle nye AI-genererede PDF'er. **Alle fundne originale filer skal med i filoversigten, uanset om indholdet kunne analyseres.** Angiv utilgængelige/ikke-gennemgåede filer som begrænsninger; intet må gemmes bag en falsk påstand om fuldstændighed.
- **Indhold:** En kort startside med `SÅDAN SØGER DU`, indholdsfortegnelse, **alfabetisk emneindeks**, tematisk emneoversigt, oversigt over kildetyper og henvisninger til AI-PDF'er.
- **Hver reference:** Emne og synonymer, **kort beskrivelse af indholdet**, præcis **oprindelig filnavn**, sti/undermappe, kildeformat og verificeret **side/slide/figur/billede/afsnit/tidsstempel**. For AI-genereret PDF: faktisk filnavn og verificeret side.
- **Billedsøgning:** Når et billede/diagram faktisk er visuelt gennemgået, omsæt det til en kort, søgbar tekstlig beskrivelse; gerne en kort billedbeskrivelse og filnavn, eventuelt lovligt genbrugbart miniaturebillede, hvis teknisk muligt. Et fotografi/figur skal kunne findes ved det faglige emne, **selv om billedfilen ikke indeholder tekst**.
- **Video og audio:** Registrér filnavn, kort resumé og faglige hovedpointer **uden fuld transskription som standard**. Inkludér verificerede tidsstempler, når muligt.
- **Status:** Verificeret, delvist analyseret, ikke læst/ikke afspillet. **Angiv antal pr. format og afstem med originalmappens fulde filoversigt**; udeladte filer medfører `delvist færdig`. Fremmede fagfiler må registreres i inventaret, men ikke fejlagtigt bruges som kilde til det valgte fags søgeindeks. Når AI-PDF'er indekseres, skal sider med faktisk forklarende indhold bruges, ikke kun emneord i indholdsfortegnelsen. **Opfind aldrig sidetal, tidsstempler, figurer, resuméer eller kildeindhold.**
- **Offline:** Alt det ovenstående ligger som rigtig, søgbar tekst i PDF'en. Links er kun ekstra hjælp. Hvis et originaldokument ikke medfølger offline, fortæl det, selvom indeks-PDF'en peger på det.

**Illustrativt eksempel — ingen faktisk fil verificeret:**

| Søgeord | Find det her | Originalfil / AI-fil | Præcis placering |
|---|---|---|---|
| Drivhuseffekt; drivhusgasser | Begrebsforklaring og graf | `Noter.pdf` | s. 4, figur 1 |
| Drivhuseffekt | Foto af håndtegnet forklaring | `IMG_0421.jpg` | hele billedet |
| Drivhuseffekt | Videogennemgang (kun hvis analyseret) | `Klima.mp4` | tidspunkt ikke verificeret |
| Drivhuseffekt | Selvstændig letforklaret repetition | `06_OFFLINE_STUDIEKOMPENDIUM_....pdf` | s. 12, hvis kontrolleret |

### `01_START_HER_ÅÅÅÅ-MM-DD.pdf`

- Fag, niveau, type (toårigt hf/hf-enkeltfag), dato og kildegrundlag.
- **Kort produktions-/slutstatus** til offline læsning: faktisk analyserede/delvist analyserede/ikke læste filer, oversigt over faktisk oprettede PDF'er med filnavne og placering, begrænsninger, nye versioner og næste trin. Dette skal stemme med den **obligatoriske slutrapport i ChatGPT**, ikke erstatte den.
- Dækning af tilgængelige originalfiler: fundet/læst/delvist/ikke læst.
- Indholdsfortegnelse for PDF-pakken, læseforslag, begrænsninger.
- **Offline-vejledning**: hvilke filer der skal ligge lokalt, og test af søgning uden internet.
- Disclaimer om at tilladte hjælpemidler varierer efter prøve.

**Denne og de andre supplerende PDF'er ligger i en ny `AI-Generated/<kørsel>/`-undermappe.**

### `02_FILOVERSIGT_ÅÅÅÅ-MM-DD.pdf`

**Obligatorisk:** Medtag alle originalfiler fra den valgte mappe, også billedfiler og filer uden analyserbart indhold. Angiv præcise tal per filtype, afstem totalen med kildeinventaret og markér tværfaglige/off-topic-filer særskilt.

| Oprindeligt filnavn | Placering (hvis kendt) | Format | Læst status | Centrale emner | Fejl/usikkerheder |
|---|---|---|---|---|---|

Rapporten skal tydeligt oplyse, om resultatet dækker en **udvalgt mappe** eller hele den ønskede samling. Enhver begrænsning skal fremgå.

### `03_LAEREPLANSDAEKNING_ÅÅÅÅ-MM-DD.pdf`

- Hvis der ligger en faktisk **undervisningsbeskrivelse** i det valgte materiale, så tilføj en sektion med holdets gennemgåede forløb og match med elevens dokumenter. Hvis den ikke kunne findes, sig det uden at forveksle fravær af noter med fravær af undervisning.
- Medtag et selvstændigt **kompetence- og metodeindeks**: faglige mål, konkrete måder at demonstrere dem på og dokumenteret elevmateriale. Et simpelt emneord er ikke nok til at konkludere, at kompetencen er dækket.
- Angiv **præcis** officiel kilde, uddannelsestype, årgang, dato for tjek og evt. uafklaret overgang.
- Registrér hvert relevant krav/emne med kildefiler og status: `dokumenteret`, `delvist dokumenteret`, `ikke fundet i tilgængelige filer` eller `ikke vurderet`.
- `Ikke fundet` betyder aldrig `ikke undervist`.
- Undlad at kalde et **vejledende** emne for et bindende eksamenskrav.

### `04_REPETITIONSNOTER_ÅÅÅÅ-MM-DD.pdf`

- Korte og fagligt præcise forklaringer med selvstændigt skrevne eksempler.
- Medtag fagligt nyttige resuméer fra **faktisk analyserede** video- og lydoptagelser, og forklar indholdet på elevens niveau. Medtag ikke ordret transskription som standard. Brug tydelig kildehenvisning og status, hvis mediet kun er delvist gennemgået.
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

- **Vægt fagets dokumenterede kompetencer og bedømmelseskriterier**, ikke bare en generisk emneliste; medtag praktiske metoder, tekstanalyse, kilder, regnebegrundelser eller forsøgsdata efter faget.
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
- Kopiérbar/søgbar tekst (ikke bare rasterbilleder). Hvis et billede eller en scannet figur faktisk kan analyseres visuelt, så skriv **søgbare billedbeskrivelser**. Anvend evt. OCR til tekst i et billede med kvalitetskontrol. **Fuld lyd-/videotransskription er ikke standard**; skriv korte faglige resuméer og relevante hovedpointer, når mediet kan gennemgås.
- Dansk og korrekte danske tegn. For fag med anden undervisningssprog: bevar relevante fagtermer.
- Tydelige henvisninger og statusmarkeringer; farve alene må ikke bære betydningen. Undgå meget tætte sider med kun små filnavne: brug læsbar skrift og tydelige emneoverskrifter, selv ved store indeks.
- Klikbare PDF-bogmærker eller indholdsfortegnelse, hvis værktøjet understøtter det.
- Tjek PDF'en ved at åbne den og søge efter mindst tre emner samt prøve at læse den uden netadgang.

## Versionering uden at ændre originaler

Forslag: `Historie/AI-Generated/2026-11-16-01/`, derefter `2026-11-16-02/`, til **supplerende** PDF'er, mens `Historie/00_FIND_ALT_HER_HISTORIE_2026-11-16-01.pdf` ligger synligt i fagmappen. Datoen er et eksempel. Brug nye mapper og unikke filnavne ved hver kørsel; aldrig overskrivning eller automatisk arkivering/flytning af ældre filer. Hvis der ligger flere tidligere indeksfiler, skal eleven kunne identificere den nyeste version.

Hvis ChatGPT ikke har adgang til at gemme i brugerens foretrukne lagring, leveres PDF'erne som **downloadbare filer i samtalen**, uden at kræve en ny udbyder.
