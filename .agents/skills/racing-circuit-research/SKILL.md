---
name: racing-circuit-research
description: Research, verify, create, or update racing-circuit name entries in the racing-circuit-names repository, including circuit-name etymology, naming history, characteristic track-element names, sources, Wikimedia Commons SVG selection, licensing, accessibility metadata, transparent authorship, Markdown publication, and README indexing. Use when a user asks to add, research, explain, verify, or update a racing circuit in this repository.
---

# Racing Circuit Research

Use this skill for repeatable research and publication of racing-circuit name entries in this repository.

## Read the project rules first

Before researching or changing a circuit, read:

- `../../../docs/methodology.md`
- `../../../docs/source-policy.md`
- `../../../docs/internet-research-playbook.md`
- `../../../docs/circuit-entry-template.md`
- `../../../docs/svg-accessibility-and-licensing.md`
- `../../../AGENTS.md`

Treat these files as authoritative project instructions. Do not replace them with assumptions from this skill.

## Inputs

The usual input is a circuit name, for example:

- `Suzuka`
- `Monza`
- `Nürburgring`
- `Circuit de Spa-Francorchamps`

The user may also ask to update an existing entry or verify one particular claim.

## Workflow

### 1. Resolve the identity of the circuit

Confirm:

- exact circuit;
- city or region;
- country;
- whether the requested name identifies the circuit itself, a venue, a district, a sponsor name, or a historical name.

Do not proceed on an ambiguous same-name place without resolving the ambiguity.

### 2. Execute the internet research playbook

Follow `../../../docs/internet-research-playbook.md` before drafting the entry.

Do not collapse research into one broad query. Run separate research tracks for:

- current official name;
- circuit history;
- linguistic meaning;
- place-name etymology;
- patron;
- sponsor;
- historical names;
- characteristic element names;
- SVG.

Use local-language queries in addition to English, especially for place-name history and etymology.

Do not start writing merely because one plausible article has been found. Use the playbook's completion criteria.

### 3. Verify the current official name

Search current official sources first.

Record separately when applicable:

- official name;
- common name;
- sponsored name;
- historical name.

Treat sponsored and commercial names as time-sensitive.

### 4. Research the name linguistically

Determine:

- source language;
- components of the name, if decomposition is linguistically justified;
- literal meaning;
- natural Polish explanation;
- whether the name should remain untranslated in ordinary use.

Do not infer etymology only from modern spelling or apparent similarity.

### 5. Research the actual etymology

If the circuit is named after a place, research the place name as well.

If it is named after a person, establish who the person was and why the venue bears the name.

If the etymology is uncertain:

- state that explicitly;
- describe supported hypotheses only;
- do not fill gaps with plausible-sounding reconstruction.

### 6. Research naming history

Check for:

- original name;
- renamings;
- patron names;
- sponsor names;
- important historical variants;
- dates of major changes where reliably documented.

Keep naming history separate from unrelated sporting history unless sporting facts are needed to explain the name.

### 7. Check characteristic track-element names

For every circuit, check whether the contemporary or historically relevant layout has established names for characteristic elements.

These may include:

- corners;
- chicanes;
- hairpins;
- straights;
- sequences;
- larger sections;
- other clearly named parts of the racing surface.

This **research check is mandatory**, but publication of a section is conditional.

For each potentially relevant name, distinguish:

1. documented use of the name;
2. status of the name — official, traditional, colloquial, commentary usage, sponsored or historical;
3. documented origin of the name;
4. spelling variants;
5. renaming history;
6. whether the name changed independently of geometry.

Do not treat a numbered turn as a named element merely because it appears on a map.

Do not infer a name's origin from its sound alone.

If a name refers to a person, place, building, organization, event or another circuit, research that referent as needed.

For a current layout, prefer presenting relevant elements in lap order. Turn numbers may be included as secondary orientation if reliably established.

If no established names worth explaining are found, omit the section. That is a valid research result.

### 8. Build a source set

Follow `docs/source-policy.md` and the research playbook.

Aim for a source set that normally includes:

- current official circuit or operator source;
- official, archival, governmental, academic, historical, or linguistic source for etymology;
- official racing-series source when useful;
- sources for characteristic element names if such a section is warranted;
- reputable secondary sources only when needed to fill a gap.

Before writing, make sure each key claim can be mapped to an appropriate source.

For characteristic element names, do not confuse evidence that a name is used with evidence explaining why it has that name.

Do not use Wikipedia as the sole authority for key etymological or historical claims when stronger sources exist.

### 9. Find a circuit SVG

Prefer Wikimedia Commons files with clear provenance and licensing.

Verify on the individual file page:

- exact file identity;
- circuit layout represented;
- author;
- source;
- license;
- whether modification is allowed.

Prefer `own work` or similarly clear provenance.

Reject a file if its claimed license is inconsistent with an apparently copied proprietary source.

### 10. Store and make the SVG accessible

Store one primary SVG as:

`assets/circuits/<slug>.svg`

Do not create a second wrapper SVG or separate accessibility-only copy.

Preserve the visual geometry unless a deliberate visual change is required and justified.

Add accessibility metadata to the root SVG according to project rules, normally:

- `role="img"`;
- `aria-labelledby`;
- `<title>`;
- `<desc>`.

The `desc` should describe the actual diagram, not merely repeat the filename.

Record the modification when the license requires change indication.

### 11. Create or update the Markdown entry

Use:

`circuits/<slug>.md`

Follow `docs/circuit-entry-template.md`.

Place the circuit image high in the entry, normally immediately after basic information.

If characteristic element names were found and meet the source standard, add:

```markdown
## Nazwy charakterystycznych elementów toru
```

Prefer headings and short prose blocks rather than a table. For a modern layout, use lap order by default.

Do not create this section only to list turn numbers.

### 12. Add transparent authorship information

Treat the following as the default editorial attribution for this project:

```text
Redakcja: Mikołaj Rotnicki.
```

Record AI support according to the actual tool used. For work performed with ChatGPT, use:

```text
Wsparcie badawcze i redakcyjne: ChatGPT (OpenAI).
```

Do not automatically name ChatGPT if another AI system performed the work. Adapt or remove the AI-support line to reflect the actual workflow.

This attribution applies to the editorial/research work only. Keep authorship and licensing of external assets such as SVG files separate.

### 13. Update the README index

Add the circuit to `## Opracowane tory` in `README.md`.

Use a descriptive Markdown link to the circuit file.

### 14. Final verification

Before declaring the task complete, check all of the following:

- the correct circuit was researched;
- the internet research playbook was followed;
- current and historical facts were searched separately where needed;
- local-language searching was used where useful;
- the current official name was verified;
- common, geographical, historical, and sponsor names are distinguished;
- literal translation is distinguished from Polish explanation;
- etymology is sourced and not guessed;
- source locations have not been mixed up;
- characteristic element names were checked;
- if a characteristic-elements section exists, each included name has established use and the text distinguishes use from origin;
- no numbered-only elements were converted into invented names;
- uncertainty and spelling variants are preserved where relevant;
- key claims are supported by appropriate sources;
- SVG provenance and license are clear;
- SVG attribution includes modification information when required;
- Markdown has meaningful alt text;
- SVG has `role`, `aria-labelledby`, `title`, and `desc` when an SVG is used;
- SVG is embedded directly in the circuit entry when an appropriate SVG exists;
- editorial attribution is present and AI support reflects the actual workflow;
- README index is updated;
- last-update date is correct.

## Output to the user

After repository changes, summarize concisely:

- the core etymological conclusion;
- any important uncertainty;
- whether characteristic element names were found and published;
- which files were added or updated;
- whether the SVG and accessibility metadata were added;
- whether the editorial attribution was applied.

Do not bury an unresolved source problem behind a polished summary.

## Safety against hallucinated research

If external research is unavailable, do not fabricate current names, etymologies, characteristic element names, source citations, licenses, authors, or dates. Work only from verified material or clearly report the limitation.
