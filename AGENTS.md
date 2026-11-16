# AI-agent instructions — HFVUC Fyn Exams Prep

This is a **public research/documentation repository** for private, student-controlled HF exam prep. The student experience is ChatGPT + their preferred storage, with **searchable offline PDF outputs**. This repo must **never** store student documents or operate a private data-collection service.

## Research mission

Research and document the official requirements for **every relevant HF subject and level**, including:
- **Toårigt hf**, with mandatory subjects, NF and KS as their own exam frameworks.
- **Hf-enkeltfag** and differences from the two-year HF curriculum.
- **Valgfag** (levels/language variants) and references to other official curricula where applicable.
- **Skriftlige, mundtlige, interne, eksterne and praktiske delprøver**.
- **Bedømmelseskriterier, faglige mål, prøveformer, tilladte hjælpemidler**, and teaching-description relevance.

Work can be divided across independent research tracks (see GitHub issues), but **no background agent is currently implied to be running** merely because this file exists.

## Source priority

1. Official [toårigt hf](https://uvm.dk/uddannelse-til-unge/gymnasiale-uddannelser/fag-og-laereplaner/hf-laereplaner/) curricula.
2. Official [hf-enkeltfag](https://uvm.dk/uddannelse-til-unge/gymnasiale-uddannelser/fag-og-laereplaner/hf-e-laereplaner/) curricula.
3. Official [valgfag](https://uvm.dk/uddannelse-til-unge/gymnasiale-uddannelser/fag-og-laereplaner/valgfag-laereplaner/) curricula.
4. Official [exam rules](https://uvm.dk/uddannelse-til-unge/gymnasiale-uddannelser/proever-og-eksamen/generelle-regler-om-proever-og-eksamen/) and [help-aids overview](https://uvm.dk/uddannelse-til-unge/gymnasiale-uddannelser/proever-og-eksamen/afholdelse-af-proever/hjaelpemidler-til-gymnasiale-proever/).
5. Official [censor information](https://uvm.dk/uddannelse-til-unge/gymnasiale-uddannelser/proever-og-eksamen/censor-og-bedoemmelse-af-proever/) and [teaching-description guidance](https://uvm.dk/media/l3qp5ayr/260304-vejledning-til-studieplan-og-undervisningsbeskrivelser-paa-de-gymnasiale-uddannelser.pdf).
6. School-specific practical [HF & VUC FYN exam information](https://www.vucfyn.dk/studieinfo/eksamen/hf-eksamen/).

Only treat a source as **verified** after actually opening and checking it. Link to the original official document. Do not paste full copyrighted documents into the repository.

## Required per-subject output

Create or improve `subjects/<slug>-<level>/README.md` or a specific combined-faggruppe profile, using [SUBJECT_TEMPLATE.md](templates/SUBJECT_TEMPLATE.md).

For **each** variant, document:
- Fag, niveau, track (toårigt hf, hf-enkeltfag, valgfag), effective curriculum **year** and whether its applicability to a student cohort is verified or unknown.
- Official curriculum link, guidance link, date of your verification.
- **Faglige mål**, identified by section.
- **Prøveform** and distinct written/oral/practical/internal/external exam components.
- **Bedømmelseskriterier** with exact official section. Give a student-friendly explanation, not a made-up scoring rubric.
- Special requirements (e.g. experiments, sources, group presentation, digital tools) only as directly supported.
- Allowed exam materials, checked against the **latest applicable** official help-aids overview.
- What to collect from a student's private material (e.g. exercises, experiments, books, **undervisningsbeskrivelse**).
- Unresolved questions, validity/transition restrictions, source URLs and a clear research status.

Mark `SOURCE-VERIFIED EXAMPLE — NOT VERIFIED FOR A SPECIFIC STUDENT` if the curriculum is read but applicability to the student's cohort is unknown.

## Hard safety and quality rules

- **Never read, modify, publish, delete, rename, move, or copy private student files into this public repo.**
- Never modify original student documents or previous PDF reports. Student PDF outputs are new and timestamped.
- Do not invent page numbers, exam questions, exam durations, censor preferences, tools, grades, or missing material.
- **Mere topic coverage is not equivalent to ability to meet a learning goal.** Analyze skills, methods and criteria.
- **HF-e courses are not automatically the same as the two-year HF faggruppe components.**
- Never assume the newest curriculum automatically applies to an older cohort.
- **Censor's focus is not free speculation**: distinguish binding criteria, non-binding guidance and practice suggestions.
- Keep classroom descriptions separate from overall legal curriculum requirements.
- If an official source is inaccessible or not current, flag `NOT VERIFIED` and leave a useful link.
- Public repository files may be Markdown; the **student-facing generated package stays PDF-only**.
- **Primary UX:** one searchable `00_FIND_ALT_HER_<SUBJECT>_<date-version>.pdf` at top of each subject area, with supporting PDF outputs in a new `AI-Generated/<run>/` subfolder. If no storage write, deliver download PDFs and advise manual placement.
- **Strict phase order:** inventory/analyze the explicitly shared folder including embedded images, photos, audio and video when supported → virtually organize references by subject/topic → produce supporting offline PDF summaries → **produce the primary searchable index LAST**, including every actually created PDF and verified page.
- **Media:** index visible diagrams and pictures using a textual subject description, actual source filename and verified location. Audio/video should yield concise factual study summaries, **not a full verbatim transcript by default**. Never hallucinate watched/listened media or timestamps; mark unsupported files as not analyzed.
- Virtual organization never moves or renames source materials. Creating new files, including one new index in a subject root if allowed, does not authorize modification of original files.
- Do not modify README onboarding flow in a way that requires any particular cloud service, website or app.

## Definition of done

A profile is **complete for a specific curriculum version**, not necessarily every possible cohort, only when official 2.1/4.2/4.3 (or equivalent) have been independently checked and cited, exceptions documented, and all exam components distinguished.

Update [RESEARCH_STATUS_2026-11-16.md](exam-guidelines/RESEARCH_STATUS_2026-11-16.md) or add a newer dated status document with exact completed profiles, open questions and audit trail. Do not change the status of a topic to `complete` because a folder exists.
