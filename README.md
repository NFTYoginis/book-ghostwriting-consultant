# Book-Ghostwriting Consultant

A folder-based ICM specialist that walks a non-technical person with real lived material through the process of turning what they know into a finished manuscript — without ever inventing what they haven't told it.

This formalizes a process already run six times internally (the operator's own books), most recently and most fully documented on the real production trail of *"Are You Actually Hungry?"* It is not a theory of how ghostwriting should work — it's a repeat of how it already worked.

## What it produces

An example from a real book: the "still needed" list kept while drafting *Are You Actually Hungry?* (`STORY-LIST-MASTER.md`, a working file). Where a chapter has an argument but no captured scene, the gap is listed, not filled. Two entries, quoted as written:

> **The guiding truth (pinned):** Claude can always write prose; it can never invent 30 years of Gabe. The prose is done. The 30 years is the gap.

> 3. **MEDIUM — The Health-door person: came for one symptom, left with something else.** *(live placeholder ch02:64 · Story Bank #9 ◐)* — the chapter *names* the pattern ("almost every time, something else happens that you didn't come for") and then drops a placeholder exactly where the human face should be. One real person (or honestly, one composite-flagged-as-such) who walked in for the bloating and walked out having heard the marriage / the job. **Honesty-frame note:** must stay within "people he met / watched pass through centers," never "client I supervised."

The companion anecdote list carries a status key: each item is ✅ captured, ◐ partial (theme captured, still wants one specific story) or ○ open. The refusal that produces this list is in [`examples.md`](examples.md).

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

## Where this fits

The book-production shelf, numbered as in the catalog. The skill in this repo is in bold.

1. **Book Ghostwriting** (this repo)
2. [Publishing Preparation](https://github.com/NFTYoginis/publishing-preparation-skill)
3. [Title & Positioning](https://github.com/NFTYoginis/title-and-positioning-skill)
4. [Book-to-Content Repurposing](https://github.com/NFTYoginis/book-to-content-repurposing-skill)
5. [Fact, Claim & Evidence Verification](https://github.com/NFTYoginis/fact-claim-verification-skill)
6. [Book Launch & Funnel Strategy](https://github.com/NFTYoginis/book-launch-funnel-strategy-skill)
7. [Book Format & Interior-Image Integrity](https://github.com/NFTYoginis/book-format-integrity-skill)

Next: [Publishing Preparation](https://github.com/NFTYoginis/publishing-preparation-skill). All seven: [Book Production Skills](https://github.com/NFTYoginis/book-production-skills).

## License

MIT — see `LICENSE`.

---

Built by Gabe at The Quiet Ai. The Quiet Scribe Suite (early access) carries your context from one AI tool to the next: [thequietscribe.com](https://thequietscribe.com)
