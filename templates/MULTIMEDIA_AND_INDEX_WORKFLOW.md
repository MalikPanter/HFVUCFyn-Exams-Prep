# Arbejdsgang: én søgbar PDF som indgang til alle elevens materialer

**Projektstandard fra 16. november 2026.** Gælder alle HF-fag og kan bruges uanset lagringsudbyder, **hvis eleven har delt de relevante filer, og ChatGPT har de nødvendige værktøjer til at læse filtypen**.

## 1. Den vigtigste fil er et søgeindeks

For **hvert fag** laver ChatGPT en stor, **søgbar PDF** med en titel, der sorterer øverst:

`00_FIND_ALT_HER_<FAG>_<DATO-OG-VERSION>.pdf`

Indekset er **første og vigtigste åbning**: tryk `Ctrl+F` eller `Cmd+F`, søg et ord, og få præcis information om, hvor emnet optræder.

Det må **gerne være langt**; fuldstændig, verificerbar dækning og hurtig navigation er vigtigere end få sider. Men lav en kort guide/indholdsfortegnelse på side 1 og alfabetisk + tematisk emneoversigt med sidetal/bogmærker.

Indekset dækker:
- Elevens originale filer: PDF, Word, PowerPoint, noter, billeder, fotos, scannede tegninger, audio, video og andre faktisk læsbare filtyper.
- Indhold i **billeder/diagrammer**, også når der ikke er søgbar tekst i billedet.
- **Nye AI-skabte PDF'er fra samme kørsel**: repetitionsnoter, selvstændigt kompendium, pensumtjek og eksamensoversigt.
- Alternative søgeord, almindelige stavevarianter, beslægtede begreber **uden at blande fagligt forskellige begreber sammen**.

Hver søgepost skal have **emne, kort forklaring, kildetype, originalt filnavn, mappe/sti og præcis placering** (bekræftet side, slide, figur, billede, afsnit eller tid i video/lyd), evt. AI-PDF og side. Markér alt usikkert som ikke verificeret.

**Eksempel (kun illustration, ingen faktisk elevfil verificeret):**

| Søg efter | Hvad findes | Fil | Placering |
|---|---|---|---|
| Drivhuseffekten / drivhusgasser | Forklaring + figur | `Naturgeografi_notater.pdf` | s. 8 og figur 2 |
| Drivhuseffekten / CO₂ | Foto af tegning om atmosfæren | `IMG_0421.jpg` | hele billedet |
| Drivhuseffekten | Videoforklaring om gasser og varme | `Klimavideo.mp4` | 02:14–04:08 **kun hvis faktisk verificeret** |
| Drivhuseffekten | Enkel AI-forklaring | `06_OFFLINE_STUDIEKOMPENDIUM_....pdf` | s. 12 |

Hvis originale medier ikke er hentet til elevens offline-computer, er en filhenvisning **ikke en offline kopi** af mediet. Skriv det tydeligt i søge-PDF'en.

## 2. Arbejd i denne rækkefølge

**Fase A — Inventar, adgang og analyse (ingen produktion endnu)**
1. Registrér hele **det delte område**, inklusive undermapper og alle medietyper.
2. Kontrollér, hvilke filer der kan åbnes helt, delvist eller slet ikke, og registrér præcis original sti og navn.
3. Læs dokumenter, undersøg billeder, og analyser lyd/video **kun når den konkrete funktion er tilgængelig**. Gæt ikke ud fra filnavn eller thumbnail.
4. Registrér undervisningsbeskrivelse, aktuelle fag-/niveauoplysninger og officielle bedømmelseskriterier, når de faktisk er dokumenteret.

**Fase B — Virtuel organisering (stadig ingen PDF-produktion)**
1. Sortér **referencer** i fag → emner → underemner → filer → præcise sidetal, slides, figurer eller tidsstempler.
2. Find relaterede emner, billeder, klip og mangler. Lav et internt indeksudkast og en plan for supplerende noter.
3. **Flyt, omdøb eller reorganisér aldrig originale filer**. »Organisering« er her en **virtuel katalogisering** og eventuelt nye outputmapper, ikke ændring af elevens materiale.
4. Hold separate fag adskilt. Hvis en fil rummer flere fag, må den refereres under flere fag, men skal forblive urørt.

**Fase C — Generér supplerende PDF'er**
1. Skriv først nye separate PDF'er for mangler, faglige mål/bedømmelseskriterier, repetitionsnoter, offline-kompendium mv., på **det valgte fags undervisningssprog**.
2. Lav **enkle, forståelige forklaringer** og markér tydeligt egne AI-skabte eksempler.
3. Gem dem i en ny `AI-Generated/<kørsel>/`-mappe ved det respektive fag, **hvis** brugeren har givet adgang til netop den placering, og lagringsværktøjet understøtter det. Ellers leveres downloadbare PDF'er til brugeren.
4. Efter produktionen: kontrollér de faktiske PDF-filenames og sidetal. Man må ikke referere til en fremtidig ikke-eksisterende fil.

**Fase D — Byg den store søge-PDF TIL SIDST**
1. Lav `00_FIND_ALT_HER_<FAG>_<DATO-OG-VERSION>.pdf` med **samtlige verificerede originalkilder og de nye PDF'er**.
2. Placér den **direkte øverst i elevens eksisterende fagmappe**, når det er muligt at **oprette en ny fil uden at ændre andre filer**, fx `HF/2 year/Historie/00_FIND_ALT_HER_HISTORIE_2026-11-16_01.pdf`.
3. Hvis elevens filer ikke ligger opdelt i fagmapper, eller der kun er direkte uploads: lav én tydeligt mærket **fagvis pakke** (en ny fag-undermappe i det autoriserede outputområde, ikke en ændring af originalernes placering), eller aflever den klart navngivne PDF i samtalen med instruktion om manuel placering.
4. Andre PDF'er bliver i `AI-Generated/<kørsel>/` — **ikke i samme øverste mappe** som hovedindekset. Aldrig automatisk overskrivning, sletning, flytning af ældre PDF'er eller originalfiler.
5. Ved gentagne kørsler: en **ny dato/version**, så eleven kan vælge nyeste indeks. Forklar eksplicit, hvordan nyeste identificeres, hvis gamle indexfiler også ligger samme sted.

Dette løser nødvendigheden af først at lave de øvrige PDF'er og **derefter** få dem med i indekset.

## 3. Billeder, fotos, scannede sider og diagrammer

- Se **billedets faktiske indhold** med et egnet værktøj, når det er tilgængeligt (også indlejrede billeder i PDF'er/præsentationer).
- Beskriv kort: `Figur af drivhuseffekten med solindstråling og varmestråling`, og registrér `IMG_0421.jpg` eller `Kapitel.pdf, side 8, figur 2`.
- Tilføj tekstbeskrivelsen og alternative relevante fagord i søge-PDF'en, så **billedet bliver søgbart via tekst**, selv om selve JPEG/PNG-filen ikke indeholder søgbar tekst.
- Angiv tydeligt, om beskrivelsen faktisk er baseret på visuelt gennemsyn, tekst omkring billedet eller en begrænset delvis analyse. **Gæt ikke indhold ud fra filnavnet.**
- En lille illustration eller thumbnail **kan** medtages i den private indeks-PDF, hvis teknisk muligt og tilladt. **Filnavn, beskrivelse og præcis reference er vigtigere**. Kopiér ikke ophavsretligt beskyttede illustrationer uden nødvendig ret.

## 4. Lyd og video: forklar indholdet i stedet for at lave ordret transskription

- **Ingen fuld ord-for-ord-transskription som standard**, og ingen lang gengivelse af undervisningsvideoen. Formålet er et godt **søgbart offline-resumé**.
- Hvis lyd/video faktisk kan åbnes/analyseres, så beskriv: **emne**, **hovedpointer**, **fagord**, **processer**, **konkrete eksempler**, og **hvad der er relevant at forstå** i forhold til fagets dokumenterede mål.
- Ved videofiler: medtag fagligt vigtige **visuelle elementer**, fx demonstrationer, grafer, forsøg, tegninger og ændringer i billedet, hvis disse faktisk kan ses.
- Angiv præcise tidsstempler/sekvenser **kun hvis de er kontrolleret**. Ellers skriv `tidspunkt ikke verificeret`.
- Generér korte, letforståelige **selvstændige PDF-forklaringer** af relevante emner til offline brug. De er ikke en påstået fuldstændig kopi af originalmediet og må ikke fremstilles som sådan.
- **Hvis filtypen ikke kan afspilles eller forstås:** registrér filnavn, format og status `indhold ikke analyseret` — **ingen opdigtet opsummering**. Bed evt. om brugerens eget resumé eller et andet tilgængeligt grundlag, uden at kræve en bestemt tjeneste.
- Der kan stå personfølsomme oplysninger i optagelser. Undlad at genudgive eller distribuere andres stemmer/ansigter og personoplysninger i PDF'er.

## 5. Offline og eksamensregler

- Det primære indeks og supplerende PDF'er skal have **ægte søgbar tekst**, åbnes uden net og bruges uden eksterne links som nødvendigt indhold.
- En videofil kan være upraktisk eller ikke tilladt ved eksamen; et udarbejdet PDF-resumé er **heller ikke automatisk tilladt**. Kontroller **reglerne for det enkelte fag og den konkrete prøve**.
- Indekset må hjælpe eleven med at finde videofilen, men offline-PDF'en skal også have en **kort selvstændig beskrivelse** af læringsindholdet.
- Det er ikke et krav, at alle medier kan omsættes til fuldstændig information. Dokumentér udeladelser og usikkerhed.

## 6. Validering af hovedindekset

- [ ] Én separat **00_FIND_ALT_HER** PDF per fag, nem at finde.
- [ ] En elev kan søge `drivhuseffekten`, `CO₂` og et alternativt fagudtryk med `Ctrl+F`.
- [ ] Søgning viser verificeret **filnavn + mappe + præcist sted**, også for billeder, lyd og video.
- [ ] Alle andre faktisk genererede PDF'er har en post i indeks-PDF'en og et korrekt sidetal eller afsnit.
- [ ] Ingen fiktive medietidsstempler, sideovergange eller kilder.
- [ ] Alle kilder, herunder utilgængelige, får ærlig status.
- [ ] PDF'en kan bruges **offline**, og det er tydeligt om originalfilen også skal downloades.
- [ ] Alle faser er fulgt i rækkefølge; **index genereres sidst**.
- [ ] Ingen eksisterende fil er flyttet, omdøbt, redigeret, slettet eller overskrevet.

Dette dokument supplerer [PDF_OUTPUT_SPEC.md](PDF_OUTPUT_SPEC.md) og [MASTER_PROMPT.md](../MASTER_PROMPT.md).
