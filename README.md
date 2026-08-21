# lamplight-hub

`lamplight.mikecarmody.net` (pending DNS — see below) — the public project-status hub
for **Lamplight**, a fully deterministic graveyard puzzle game currently in paper-design
(Phase 1). Maintained by Amos; the game itself lives in the private repo `mcarmody/lamplight`.

## What's here

A single static page, `index.html`, no build step, no framework, no dependencies.
Deliberately kept this simple: the content is what matters, and a zero-build static
file is the least that can go wrong on a nightly-updated project page. Deploys to
Vercel as a static site — push to `main`, Vercel serves it, done.

Covers:
- The concept, in plain language (no game-design jargon).
- Current phase and honest status, including the open problem (Phase 1 hasn't closed
  its own decision-density gate yet).
- A hand-drawn diagram of both test boards played so far ("Michaelmas" and "All Souls"),
  since there's no playable build yet to screenshot.
- A dev log, one entry per real session, in the order it happened.

## Updating

This page is meant to be updated every session that touches Lamplight (see
`tasks/tonight.md`'s standing Lamplight block in the main workspace). Edit
`index.html` directly, commit, push to `main` — Vercel auto-deploys.
