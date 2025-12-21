# COPYRIGHT & HUMAN AUTHORSHIP GUIDANCE
(AIFP Standard — AI First Exchange / AIFX)

This document provides **non-authoritative guidance** on documenting
human creative involvement in AI-assisted projects using AIFX formats.

It does not constitute legal advice and does not guarantee copyright
eligibility under any jurisdiction.

---

## 1. Human Creative Contribution (General Guidance)

In many jurisdictions, copyright protection for AI-assisted works
depends on the presence of **meaningful human creative contribution**.

Such contribution may include, but is not limited to:
- Designing the overall concept, narrative, or creative direction
- Writing prompts, scripts, instructions, or scene breakdowns
- Selecting, arranging, sequencing, or curating AI-generated outputs
- Editing or refining assets such as audio, video, images, or text
- Making expressive decisions that shape the final work

Purely autonomous generation or assembly without human creative
direction may not qualify for copyright protection under current law.

> Interpretation of copyright eligibility is determined by applicable
> legal authorities and courts, not by AIFX.

---

## 2. How AIFP Supports Documentation

The **AI First Project Format (AIFP)** supports structured documentation
of declared human involvement through metadata, provenance records,
and workflow history.

An AIFP project may include:
- Declared creator identity (name, handle, optional contact details)
- Human-authored prompts, scripts, and editorial notes
- Timeline and sequencing metadata
- Documented editing or curation steps
- Provenance records for imported assets
- Timestamps and declared toolchains

These records are intended to support **transparency and context**
regarding the creative process.

---

## 3. Optional Manifest Fields

Creators MAY include the following optional fields in `manifest.json`
to document declared human involvement:

```json
"human_authorship_statement": "",
"human_signature": "",
"creator_email": "",
"editorial_notes": "",
"human_editing_steps": [],
"human_curated_output": true
```
These fields are declarative and do not independently establish
legal authorship or ownership.

4. Ownership Considerations

Where applicable, copyright may belong to the human author(s)
who contributed meaningful creative decisions to a project.

AI-generated outputs that are unedited, uncurated, or produced
without human creative direction may not be eligible for copyright
protection on their own.

AIFX does not determine ownership and does not resolve disputes.

5. Licensing

Creators may include licensing information within an AIFP container,
such as:

legal/license.txt

license.json

other clearly identified licensing files

Creators and users are responsible for ensuring compliance with
applicable laws, licenses, and contractual obligations.

Notes

This document is informational only

Legal interpretations vary by jurisdiction

AIFX standards support documentation, not adjudication
