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

- Aktuelt verificerede prøveformer, regler, officielle referencer og gyldighed.
- Separat afsnit: `Skal bekræftes med skolen`, hvis noget er uklart.
- **Ingen** generalisering om, at PDF'er altid må anvendes under prøven.

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
