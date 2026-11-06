# SOP: Transcript-to-Ad Candidate Review

## Intake
1. Confirm recording and timestamped WebVTT transcript are available in the approved internal storage.
2. Assign a non-identifying session ID; do not expose child names in public artifacts.
3. Confirm access is limited to staff who need the material.

## AI mining
1. Run the versioned system prompt and user template on one transcript.
2. Save the prompt version, model/version, run date and raw candidate output.
3. Limit output to 0–5 candidates; zero is a valid result.
4. Reject outputs with invented quotes/timestamps or any hard-exclusion content.

## Human verification
For each candidate:
1. Open video 3 seconds before start and watch at least 5 seconds past end.
2. Verify exact words, speaker, context, camera/screen visual and audio clarity.
3. Confirm the cut makes sense as a standalone 10–20 second moment.
4. Check for child names, school/location identifiers, notifications, sensitive disclosures and distress.
5. Confirm documented guardian consent and internal approval for marketing use.
6. Record Accept, Reject or Needs context with a reason code.

## Edit and release
1. Editor creates the cut and captions. Captions must not exaggerate or rewrite the child’s words.
2. Second reviewer checks context, caption accuracy, branding, aspect ratio and audio.
3. Owner verifies consent and compliance; only then set Approved for publishing.
4. Attach campaign ID and record downstream results.

## Rejection reason codes
R1 transcript/audio mismatch; R2 visual missing or camera off; R3 weak hook; R4 teacher monologue; R5 context missing; R6 child privacy/consent; R7 distress/embarrassment; R8 factual or cultural issue; R9 audio/video quality; R10 low learning value; R11 other.

## Weekly learning loop
Review 10 accepted and 10 rejected candidates weekly. Update the prompt only when a pattern is observed, version each change, and compare acceptance rate and review time before/after. Do not optimize by increasing the number of candidates alone.
