# Stage 5 — Named Revision Passes

## What it is

At minimum two dated, versioned, whole-manuscript passes, run only after a complete first-pass draft exists:

1. **Rhythm / read-aloud pass** — audits recurring phrases and refrains across the whole manuscript for cadence: rung too often (noise), not enough (missed opportunity), or musical (leave it).
2. **Stand-out / cut-flat-material pass** — identifies material that isn't earning its place, for the author to decide whether to cut.

Both passes are diagnostic-only on first run. No chapter edits happen in the same pass that identifies them — the pass produces a findings file; edits happen afterward, as their own step, only once the author has seen the findings.

## Real precedent

`GabeYoga-HQ/Detox Book/manuscript/_BELL-PASS.md` — the rhythm pass. Its own header states the discipline explicitly: *"diagnostic only — NO chapter edits made (per operator: 'only after the four would I touch chapter content again')."* It tracks each recurring phrase ("the body has a language," "'not now' is information," etc.) across every chapter, verdicts each as musical or over-rung, and flags exactly one real trim out of fourteen tracked refrains — most of the manuscript's repetition was working as intended, not noise.

`manuscript/_STANDOUT-PASS.md` — the cut-flat-material pass, run alongside it.

## Mechanics

1. Only run a pass once a complete first-pass manuscript exists — a partial manuscript can't be rhythm-audited, because the same phrase's cadence depends on its full arc.
2. For the rhythm pass: grep or otherwise track every recurring phrase/image across every chapter, verdict each as musical / over-rung / under-rung, and note the specific location of any recommended trim (chapter + line, not just "somewhere in here").
3. For the stand-out pass: identify material that reads as flat or filler against the manuscript's own established voice, with the same location specificity.
4. Watch for build-artifact contamination — the real Bell Pass caught its own raw counts being inflated by developer/editor comments left in draft files, and explicitly discounted them before reaching a verdict. Apply the same discipline: don't let editorial scaffolding pollute a rhythm count against reader-facing text.
5. Present findings to the author before making any edit. Edits are a separate, later step.

## Refusal condition

Won't run a pass on an incomplete manuscript. Won't make silent edits inside a diagnostic pass — findings and edits are separate artifacts, always.
