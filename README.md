# Book-Ghostwriting Consultant

A folder-based ICM specialist that walks a non-technical person with real lived material through the process of turning what they know into a finished manuscript — without ever inventing what they haven't told it.

This formalizes a process already run six times internally (the operator's own books), most recently and most fully documented on the real production trail of *"Are You Actually Hungry?"* It is not a theory of how ghostwriting should work — it's a repeat of how it already worked.

## What this is

Seven stages, run in order, each with a defined input, output, and refusal condition:

1. **Capture** — record the person talking, transcribe verbatim.
2. **Extraction** — sort raw talk into a material index + story bank, before any structure.
3. **Versioned outline** — status-keyed, dated, reasoned, with a de-dup ledger and a PROTECTED-LINES list.
4. **Chapter draft loop** — one file per chapter, drafted only from material the outline marks ready.
5. **Named revision passes** — minimum two: rhythm/read-aloud, and stand-out/cut-flat-material.
6. **Cover** — code-rendered (HTML/JS), stays editable.
7. **Optional, per book** — chapter video and/or companion site (two different things — name which).

Full detail per stage: `reference/`. Reusable starter shapes for a new book: `reference/templates/`.

## Setup

1. Load this folder into a Claude Project, or point a Claude Code session at it — `SKILL.md` lets Claude Code auto-discover and trigger it from a natural request (e.g. "I have transcripts from a conversation, start extraction"); it routes to `identity.md` → `rules.md`, then to the one `reference/stage-*.md` file the active stage needs.
2. Working from the raw files directly (no `SKILL.md` support): read `identity.md` → `rules.md` → `examples.md` in that order, then open only the `reference/` file for the stage you're actually running — same cold-start discipline this specialist itself follows.
3. Start a real capture session (stage 1) with the author before asking for anything else. There is no useful output before real captured material exists.

## First-run prompts

- *"I have [transcripts / voice notes] from a conversation with [author]. Start extraction."*
- *"Here's my material index and story bank. Build the first outline version."*
- *"Chapter [N] is marked ready in the outline — draft it."*
- *"The manuscript is complete. Run the rhythm pass."*

## What this specialist does and doesn't do

See `identity.md` and `rules.md` for the full contract. In short: it never fills a material gap with invented content — a gap goes on the "still needed" list, not into a draft — and it carries an industry-professional voice, not any specific brand's voice.

## License

MIT — see `LICENSE`.
