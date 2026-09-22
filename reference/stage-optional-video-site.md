# Stage 7 — Optional: Chapter Video and/or Companion Site

## What it is

Two separate, optional offerings, decided per book, never defaulted. A book can ship with neither, one, or both — but only because the author named which, not because this specialist assumed.

## The two are genuinely different things

Real precedent shows both exist for the same book, built separately, for different purposes:

1. **Chapter video** — per-chapter voiceover + transcript pairs. Real precedent: `GabeYoga-HQ/Detox Book/briefs/chapter-films-audio/` — Gabe's own voiceover audio paired with transcript files per chapter, dispatched to animation-claude as a separate build (`briefs/dispatch-animation-chapter-films.md`). This is a content-production add-on, not a website.
2. **Companion site** — and even this splits into two distinct site *types*, both real, both live for the same book:
   - A **marketing landing tile** — a single page on the offer-site, sized for driving a sale. Real precedent: `the-quiet-ai/offer-site/are-you-actually-hungry/`.
   - A **richer companion app** — its own deployed project with its own architecture, meant to extend the book's content, not just sell it. Real precedent: `GabeYoga-HQ/Detox Book/living-library/` (own Netlify/Cloudflare-Worker project, documented in its own `LIVING-LIBRARY-STACK.md` / `ECOSYSTEM-ARCHITECTURE.md`).

Naming "a companion site" without specifying which of these two is meant is not a complete decision — it's a category, not a scope.

## Mechanics

1. Don't propose stage 7 work until stages 1–6 are underway or complete — this is the one stage where the author is asked to actively decide, not just supply material.
2. Ask explicitly: chapter video, marketing tile, companion app, some combination, or none.
3. Route chapter video work to a video-production worker (not this specialist — out of scope per identity.md).
4. Route site work to whichever worker builds that surface — this specialist scopes the decision, it doesn't build the site or the video itself. Building a standalone site is explicitly out of scope for this specialist's own contract (see `../rules.md` § Never in the parent `specialist-builder` contract).

## Refusal condition

Won't build either offering directly — this stage's job is to get a clear, specific decision from the author and hand it off, not to execute it. Won't accept "a companion site" as a complete answer; ask which type.
