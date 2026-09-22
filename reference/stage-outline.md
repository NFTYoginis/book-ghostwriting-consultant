# Stage 3 — Versioned Outline

## What it is

A living, dated, status-keyed outline — not a locked table of contents. Every revision states what changed and why. Four disciplines make this stage work, all four required, none optional:

1. **Status keys per chapter** — drafted / ready / needs-material (real precedent uses ✅ / ✍️ / ◐).
2. **De-dup ledger** — a running note of what superseded what, so material never doubles across outline versions.
3. **PROTECTED-LINES list** — verbatim author phrases flagged as load-bearing, which no later revision pass may rewrite or cut.
4. **Still-needed list** — a running, visible list of what the outline is missing from the author, never silently filled with invented material.

## Real precedent

`GabeYoga-HQ/Detox Book/OUTLINE.md` — versioned v3 → v3.1 → v4 → v5, each version dated and reasoned. Examples of real reasons a version changed:
- v4: "operator directive — Part II is the heart" — a structural re-architecture after reading the first drafts, with Part III (the science) explicitly frozen until Part II was fully drafted.
- v5: "add + split the densest" — two dense chapters split, one new short chapter added, with an explicit note on why ("it's ok to have short chapters that have space").

The de-dup ledger in the real file reads: *"Ch5's full Mirror section → trimmed to a pointer to Ch7 · Ch8 supersedes old 'No Universal Diet' + 'Doesn't Speak One Language' · do not re-draft science material into Part II."* That's the exact shape to reproduce for a new book — specific supersessions, not a general "keep things consistent" note.

The real PROTECTED-LINES entry: three verbatim author lines flagged with *"Flag these so content-claude never sands them down."* Each entry names the exact phrase and why it matters (in that case: "the philosophical center").

## Mechanics

1. Build the first outline version only after extraction is complete (material index + story bank exist).
2. Assign a status to every chapter candidate based on what material actually supports it — not on how central the topic feels.
3. When revising, write the new version *above* the old one (or link to it), state the date and the reason, and update the de-dup ledger for anything that moved or got superseded.
4. Add to PROTECTED-LINES as the author flags lines during any stage — this list can grow at any point in the process, not just during outlining.
5. Keep the still-needed list current. A chapter can't be promoted from needs-material to ready without a specific new capture session producing the missing piece (see `examples.md` Example 2).

## Refusal condition

Won't outline before extraction is done. Won't promote a chapter's status without a traceable new capture. Won't silently drop a still-needed item — it's either fulfilled by new material or it stays on the list.
