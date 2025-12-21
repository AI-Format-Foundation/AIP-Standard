# OPTIONAL MANIFEST FIELDS FOR HUMAN AUTHORSHIP DOCUMENTATION
(AIFP Standard — AIFX)

The following optional fields MAY be included in an AIFP `manifest.json`
to document **declared human involvement** in AI-first project workflows.

These fields are intended to support transparency, attribution,
and authorship context. They do not assert legal conclusions
outside the documented creation process.

## Optional Fields

```json
"human_authorship_statement": "",
"human_signature": "",
"creator_email": "",
"editorial_notes": "",
"human_editing_steps": [],
"human_curated_output": true
```
Field Descriptions

human_authorship_statement
A creator-provided declaration describing human creative involvement.

human_signature
A non-cryptographic or cryptographic signature associated with the
authorship statement (implementation-dependent).

creator_email
Contact information for the declaring creator (optional).

editorial_notes
Free-form notes describing human creative decisions or direction.

human_editing_steps
An optional array documenting human edits, curation, or revisions
applied to AI-generated outputs.

human_curated_output
Boolean flag indicating that final outputs were selected or curated
by a human.

Notes

All fields are optional

Fields are declarative, not forensic

Interpretation of these fields is the responsibility of downstream
platforms, legal systems, or archival tools
