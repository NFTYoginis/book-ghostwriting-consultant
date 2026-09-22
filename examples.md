# Examples

Two worked examples, each showing a canonical input → canonical output for a stage of the process. Both are modeled on the real production trail of "Are You Actually Hungry?" (`GabeYoga-HQ/Detox Book/`) — the internal proof case named in the build brief — with material lightly generalized so this file works as a template for a different author's book, not a private transcript.

---

## Example 1 — Capture → Extraction (stages 1–2)

**Input (verbatim capture — a fragment of a transcribed voice note):**

> "...and people ask me why I keep doing it every year, and honestly the first time I did a ten-day fast I had no idea what I was doing, I just kept going, three days, five days, seven days, ten days. And what nobody tells you is what happens around other people. You stop eating and suddenly you're a mirror — not because you're fasting, but because everyone around you starts looking at their own relationship with food. That was the real surprise. Not the hunger. The mirror."

**Output — Material Index entry (`reference/templates/MATERIAL-INDEX-template.md` shape):**

```
### Signature section candidate: "The Mirror Effect"
Source: [transcript file], [timestamp/line ref]
Summary: When the author stops eating, other people get uncomfortable — not
because of the fast itself, but because the author has become a mirror for
their own relationship to food.
Chapter-worthy: yes — author names it as "the real surprise."
Still needed: a specific instance (a dinner, a specific person's reaction) —
the transcript names the pattern but not yet a concrete scene.
```

**Output — Story Bank entry:**

```
Story: The Mirror
One-line: Others react to the author's fast as a mirror for their own eating,
not as commentary on the fast itself.
Status: partial — pattern captured, no scene yet. Do not draft a scene from
this alone; route back to capture for a specific instance.
```

Notice what did *not* happen: no chapter was written, no scene was invented to fill the gap. The pattern is real (extracted from the author's own words); the missing scene is flagged, not fabricated. This is the refusal gate from `rules.md` operating at the extraction stage, not just the drafting stage — modeled directly on the real `Gabe-Material-Index.md`'s "Story-hungry: the first-fast scene in full" annotations.

---

## Example 2 — Versioned Outline with the refusal gate active (stage 3)

**Input:** a material index with six extracted sections, one of which (a chapter candidate on "learning the terrain") has two authors'-words quotes flagged PROTECTED and no material yet for a proposed closing chapter.

**Output — Outline entry (`reference/templates/OUTLINE-template.md` shape):**

```
## v1 — 2026-XX-XX
Reason for this version: initial pass from extraction; nothing drafted yet.

PART I
1. [Chapter title] — status: ready (material index §2, §4)
2. [Chapter title] — status: needs-material — no scene captured yet for the
   closing beat; DO NOT draft from the pattern alone, per refusal gate.

De-dup ledger: none yet (v1).

PROTECTED LINES (do not sand down in any revision pass):
- "[verbatim author quote #1]" — source: [transcript ref]
- "[verbatim author quote #2]" — source: [transcript ref]

Still needed from the author:
- A specific scene for the closing chapter (status: needs-material above)
```

**Refusal in action.** If asked at this point to "just write the closing chapter, you can infer roughly what happens" — the correct response is the exact refusal language from `rules.md`: *"That's not something you've told me yet — it goes on the still-needed list, not into the draft."* The chapter stays marked needs-material until a capture session actually produces the scene. This mirrors the real `OUTLINE.md`'s discipline of marking chapters ✅ drafted / ✍️ ready / ◐ needs-an-anecdote, and never silently promoting a ◐ to ✅ without new captured material — the real trail's v3→v5 history shows every promotion tied to a specific new capture session, never to inference.
