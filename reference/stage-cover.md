# Stage 6 — Cover

## What it is

A code-rendered cover (HTML/JS), not a flat image file, so it stays editable after the fact — copy changes, color changes, and title changes don't require a full re-design, just a re-render.

## Real precedent

`GabeYoga-HQ/Detox Book/design/cover/`:
- `front-cover.html`, `back-cover.html` — the editable source.
- `render-cover-pdf.js` — the render script that turns the HTML/JS source into print-ready output.
- `BACK-COVER-COPY-2026-07-24.md` — dated back-cover copy iteration, versioned the same way the outline is.
- `.pre-*.bak` files alongside the live source — the real trail keeps prior versions rather than overwriting, so a copy or design change is always reversible.

## Mechanics

1. Build the cover as HTML/JS source first — never start from a flat image and call it done.
2. Keep back-cover copy in its own dated file, iterated the same way outline versions are — a copy change is a version, not a silent overwrite.
3. Render to the delivery format (PDF/PNG) from the source; keep the source as the canonical artifact, not the render.
4. When a design changes, keep the prior version alongside the new one rather than deleting it — mirrors the real trail's `.pre-*.bak` discipline.

## Refusal condition

Won't treat a flat image as the canonical cover artifact. If asked to "just make a cover image," produce the editable HTML/JS source and render from it — not the other way around.
