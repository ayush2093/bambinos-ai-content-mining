# Bambinos.live AI Content Mining Prototype

## Purpose
A lightweight, human-in-the-loop workflow that turns timestamped WebVTT transcripts into ranked ad-moment candidates and editor-ready briefs.

## What is included
- `prompts/moment_mining_system_prompt.md` — versioned system prompt
- `prompts/user_prompt_template.md` — run instructions
- `sample_outputs/candidate_briefs.md` — four provisional transcript-grounded briefs
- `sample_outputs/review_sheet_template.csv` — editor review schema
- `workflow/sop.md` — operational workflow and QA gates
- `workflow/unit_economics.md` — assumptions and formulas

## Important limitations
The four sample outputs were derived from the supplied WebVTT transcript files only. The video recordings were not available in this working session. Therefore, timestamps and transcript excerpts are candidate search anchors, not verified final edit points. A human must verify the source video, audio, context, visual action, consent, and compliance before editing or publishing.

No raw child transcript or recording is included in this repository. Do not commit recordings, identifiable transcripts, child names, school names, contact information, or other personal data to a public repository.

## Suggested run
1. Open the source class recording and its WebVTT transcript in the approved internal environment.
2. Paste one transcript at a time into the approved LLM with `prompts/moment_mining_system_prompt.md` as the system prompt and `prompts/user_prompt_template.md` as the user prompt.
3. Export the structured candidate rows to the review sheet.
4. Editor checks the source recording around every candidate timestamp and records a decision.
5. Only approved, consent-cleared clips may proceed to production.

## Repository is a prototype specification
This repo contains the prompts, schema, example outputs and SOP. It is not a deployed production automation. Make/n8n integration is intentionally a phase-two step after the manual pilot validates the process.
