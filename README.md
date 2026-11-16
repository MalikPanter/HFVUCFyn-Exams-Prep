# HFVUC Fyn Exams Prep

**Gratis, åbent og lager-uafhængigt eksamensforberedelsessystem til HF-elever.**

Dette er **ikke** en app, en uploadportal eller et sted, hvor elever skal dele private skolefiler. GitHub indeholder offentlige instruktioner og verificerbare kilder. Eleven beholder sine noter og opgaver i sin foretrukne løsning: fx en lokal mappe, Google Drive, OneDrive, Dropbox eller filer, der deles direkte med ChatGPT.

> **Mål:** Hjælp eleven med at finde viden i sine egne dokumenter, se hvilke emner der er dækket, og få en søgbar **PDF-pakke til offline brug**. Originale elevfiler må aldrig ændres.

## Sådan kommer du i gang (elev)

1. Find den mappe eller de filer, du vil have hjælp til. Du behøver **ikke** flytte eller omdøbe dem. Brug gerne din eksisterende cloudtjeneste eller en lokal mappe.
2. Åbn [MASTER_PROMPT.md](MASTER_PROMPT.md), kopier hele prompten, og indsæt den i en ny ChatGPT-samtale.
3. Giv ChatGPT adgang til **netop de filer**, du selv vælger, via understøttet forbindelse eller filupload. Angiv fag, niveau og om du følger toårigt hf eller hf-enkeltfag, hvis det ikke fremgår.
4. ChatGPT undersøger de tilgængelige filer, viser en oversigt og markerer tydeligt filer, den **ikke** kunne læse.
5. Du får en **PDF-pakke**: startguide, emneindeks, filoversigt, overblik over eventuelle mangler og supplerende noter efter behov. PDF-filerne gemmes i en *ny* outputmappe, hvis din valgte tjeneste understøtter det. Ellers leveres de til dig i samtalen, så du selv kan gemme dem dér, hvor du vil.
6. **Download PDF-pakken til din egen computer**, og afprøv den helt uden internet. Hvis eksamensreglerne tillader det, kan relevante offline materialer være nyttige til prøven. Tjek altid reglerne for din konkrete prøve.

**Du skal ikke sende dine noter til GitHub.** Del aldrig adgangskoder, CPR-numre, private oplysninger om andre eller andres ophavsretligt beskyttede dokumenter offentligt.

## Hvad systemet gør

- Læser **kun** filer, du udtrykkeligt har gjort tilgængelige.
- Opretter et søgbart emneindeks med kildefil, side/afsnit, alternative søgeord og eventuelle usikkerheder.
- Opretter en filoversigt, også med fejl og filer, der ikke kunne læses.
- Sammenholder, hvor det er muligt, dit materiale med **den relevante** officielle læreplan og prøvevejledning.
- Angiver **»ikke fundet i de tilgængelige filer«**, ikke »du har ikke lært det«, når materiale mangler.
- Skriver nye, tydeligt mærkede supplerende noter i PDF-form, hvor det giver mening.
- **Ændrer aldrig** dine originale filer: ingen sletning, flytning, omdøbning, omskrivning eller overskrivning.
- Producerer en separat, tidsstemplet PDF-pakke ved opdateringer.

## Hvad systemet ikke lover

- At ChatGPT kan åbne alle lagertjenester, private mapper, scannede billeder eller store dokumenter automatisk. Understøttelse og adgang afhænger af din ChatGPT-opsætning. Utilgængelige filer rapporteres som sådanne.
- At din PDF-pakke dækker alt pensum, før de relevante læreplaner er kontrolleret.
- At AI-genererede svar eller digitale hjælpemidler må bruges under en prøve. **Forberedelse og prøvesituationen er to forskellige ting.** Se [eksamensregler](exam-guidelines/README.md).

## Repository-struktur

```text
HFVUCFyn-Exams-Prep/
├── README.md                 # Elevens startside
├── MASTER_PROMPT.md          # Kopiér og indsæt i ChatGPT
├── PRIVACY_AND_COPYRIGHT.md  # Datahåndtering og deling
├── CONTRIBUTING.md           # Sådan hjælper du projektet
├── exam-guidelines/
│   ├── README.md             # Prøve- og hjælpemiddelregler
│   └── OFFICIAL_SOURCES.md   # Verificerbare officielle kilder
├── subjects/
│   ├── README.md             # Fag og niveauer
│   └── ...                   # Gradvis udbygning
└── templates/
    ├── SUBJECT_TEMPLATE.md   # Skabelon til et fags offentlige mappe
    └── PDF_OUTPUT_SPEC.md    # Formatkrav til elevens PDF-pakke
```

Elevens personlige mappe ligger **uden for dette offentlige repository** og kan have enhver struktur. Eventuelle navne som `AI-Generated` er eksempler, ikke krav.

## Status

**Version 0.1 — grundstruktur.** Systemet bygger på instruktioner og ChatGPT's reelle adgang til elevens filer, ikke på en installeret eller automatiseret app. Første test skal validere hele processen i et konkret fag og med forskellige lagringsmetoder.

## Kilder og ansvar

Dette er et uafhængigt elevprojekt — **ikke** en officiel tjeneste fra HF & VUC FYN, STUK eller Børne- og Undervisningsministeriet. Regler og læreplaner ændrer sig. Kontrollér dem altid hos [skolen](https://www.vucfyn.dk/studieinfo/eksamen/hf-eksamen/) og [ministeriet](https://uvm.dk/uddannelse-til-unge/gymnasiale-uddannelser/fag-og-laereplaner/hf-laereplaner/).

Har du rettelser, en lovligt delbar kilde eller en idé, så læs [CONTRIBUTING.md](CONTRIBUTING.md).
