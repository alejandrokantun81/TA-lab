# TA-lab

The **practice & experiments** repo for Talent Angels: a low-bar sandbox for
exercises, taxonomy explorations, and quick idea validation. This is where
mentees learn by doing **before** code lands in `TA-agents`.

This is a **subrepo** of the Talent Angels workspace.

## What this repo is for

- **Exercises** set by mentors (e.g. Sprint 1: build a graph of a taxonomy).
- **Per-mentee scratch space** under `mentees/<github-handle>/` — your own area
  to experiment. Mentors use this to see how each person works.
- Throwaway-friendly: prototypes, notebooks, spikes, quick validations.

It is **not** production code. The bar is intentionally lower than `TA-agents`:
no strict CI, light review focused on learning feedback, not gatekeeping.

## Rules (the few that still apply)

- **Still required:** DCO sign-off (`git commit -s`), no secrets, no personal
  data (nothing from the local `Mentees/` folder).
- Work in your own folder: `mentees/<your-handle>/`. Don't edit someone else's.
- Keep large data out of git (use links or `.gitignore`d local data).
- When an experiment graduates into real code, move/reimplement it in
  `TA-agents` with the full bar (tests, CI, review).

## Read first

1. The workspace policy: `../CLAUDE.md` (git, DCO, secrets).
2. The exercise brief under `exercises/`.

## Layout

```
exercises/                       # mentor-defined briefs
└── sprint-01-taxonomy-graph/    # Sprint 1: research + build a taxonomy graph
mentees/<github-handle>/         # your scratch space
```
