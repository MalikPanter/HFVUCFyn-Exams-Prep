# Pilot-test og kvalitetskontrol (før offentlig lancering)

**Status: Testplan, ikke bestået test.** Ingen private elevfiler bruges i dette repository.

## Test 1 — Lageruafhængighed

Gentag med (a) en valgt cloudmappe, hvis forbindelse er understøttet, (b) direkte upload og (c) et udvalg af lokale filer, som eleven deler manuelt.

- [ ] Masterprompten kræver ikke Google Drive, bestemt udbyder eller en ny app.
- [ ] Den spørger kun efter relevante filer og minimal kontekst.
- [ ] Den siger ærligt, når en lagertjeneste eller sti ikke kan åbnes.
- [ ] Den opretter **ikke** filer uden for det valgte outputområde.
- [ ] Den ændrer **ikke** elevens originalfiler.

## Test 2 — Kildetroværdighed

Brug et syntetisk eksempel med:
- Én søgbar PDF med tre emner og kendte sidetal.
- Én DOCX eller tekstfil.
- Én billedbaseret/scannet fil med vanskeligt læsbar tekst.
- Én utilgængelig, stor eller passwordbeskyttet fil.

Kontrollér:

- [ ] Filer opregnes med rigtige navne og tilgængelighedsstatus.
- [ ] Sidetal bruges kun, når de kan verificeres.
- [ ] Delvist læste filer er markeret som delvist læste.
- [ ] Systemet siger `ikke fundet i tilgængelige filer` frem for `ikke lært`.
- [ ] Læreplanens **uddannelsestype og årgang** er verificeret.

## Test 2b — Billeder, lyd og video

Brug et **syntetisk** datasæt, der indeholder en billedfil med relevant naturfagsdiagram, en PDF med indlejret figur, en kort lydoptagelse og en kort video samt en fil, der ikke kan afspilles.

- [ ] Billeder og figurer undersøges, hvor de tilgængelige værktøjer gør det muligt, og kan findes via **søgbare fagord** i indeks-PDF'en.
- [ ] Der findes konkret **originalfilnavn**, sti og bekræftet side/figur/slide for et billede.
- [ ] Video-/lydresuméer forklarer de **vigtige faglige pointer**, uden fuld ordret transskription som standard.
- [ ] Tidsstempler findes kun, hvis de faktisk er kontrolleret.
- [ ] Utilgængelige medier markeres ærligt som **ikke analyseret**, uden opdigtede resuméer.
- [ ] Det er tydeligt, at en video-/lydfil og PDF-resumé ikke automatisk er tilladte hjælpemidler ved eksamen.

## Test 3 — PDF-pakken

- [ ] PDF'er genereres som **reelle PDF-filer** og ikke kun tekst med endelsen `.pdf`.
- [ ] Hver PDF åbner uden login og uden netforbindelse.
- [ ] Én ny, tydeligt navngivet `00_FIND_ALT_HER_<FAG>_...` PDF **pr. fag** er den primære indgang (øverst i fagmappen, når dette kan lade sig gøre).
- [ ] De øvrige PDF'er ligger i en ny `AI-Generated/<kørsel>/`-undermappe eller leveres separat til download, ikke løst blandt originale dokumenter.
- [ ] Generering sker i rækkefølgen **inventar/analyse → virtuel organisering → supplerende PDF'er → samlet søge-PDF sidst**.
- [ ] Det sidste indeks indeholder **både originaler, billeder, medier og faktisk genererede PDF'er**.
- [ ] `Ctrl+F` finder relevante emner i indholdet, ikke kun i titel.
- [ ] Oversigtens originalfilnavne og sidetal stemmer med input.
- [ ] PDF'er kan læses uafhængigt af cloudlinks; eventuel manglende originalfil er tydeligt nævnt.
- [ ] Tydelig adskillelse af faktiske kilder og AI-genereret supplerende indhold.
- [ ] Skolens specifikke eksamensregler indgår kun som verificerede oplysninger.

## Test 3b — Sprog og enkel formidling

- [ ] Hver PDF er skrevet på **fagets faktiske undervisningssprog**, ikke ukritisk på dansk.
- [ ] Svære fagord forklares korrekt første gang, de bruges.
- [ ] Forklaringer er korte, overskuelige og indeholder **hvorfor/hvordan** og konkrete eksempler.
- [ ] Eleven kan forstå en kompleks forklaring uden at kende emnet i forvejen.
- [ ] Det faglige indhold er ikke blevet så forenklet, at det er forkert eller misvisende.

## Test 4 — Beskyttelse og opdatering

- [ ] Ingen originale filer overskrevet, redigeret, slettet, omdøbt eller flyttet.
- [ ] Output ligger i ny separat mappe eller leveres i samtalen til download.
- [ ] En senere opdatering får nyt versions-/tidsstempel og ændrer ikke tidligere filer; hvis flere indeks eksisterer, fremgår det, hvilket der er nyest.
- [ ] Utilgængelige kilder kan **ikke** maskeres som fuldt analyseret.

## Testrapport

Registrér dato, testansvarlig, lagringsform, fag, hvilke filer der blev tilgået, hvilke checks bestod/fejlede og observerede tekniske begrænsninger. Del aldrig private testdokumenter offentligt.

**Første pilot:** Et fag med et lille sæt selvskabte testnoter. Derefter større materialemængder og forskellige understøttede lagre.
