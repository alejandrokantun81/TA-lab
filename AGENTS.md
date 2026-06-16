# AGENTS.md — TA-lab

Routing for non-Claude agents (Codex, Antigravity, Cursor, Gemini, …) in
`TA-lab`, the practice & experiments repo of Talent Angels.

## Read first

1. `../CLAUDE.md` — authoritative project policy (git, DCO, secrets).
   On GitHub: `LFX-Talent-Angels/TA-workspace`.
2. `CLAUDE.md` in this repo.

Treat `CLAUDE.md` as authoritative; keep both files in sync.

## Rules (summary)

- This is a **low-bar sandbox** for exercises and experiments, not production
  code. Light review, no strict CI.
- Work only in `mentees/<github-handle>/` (your own space) or in an exercise
  folder a mentor assigned.
- Still required: DCO sign-off (`git commit -s`), no secrets, no personal data
  (nothing from `Mentees/`). Branch + PR; never push to `main`.
- Keep large/third-party data out of git.
- Graduating an experiment into real code? Reimplement it in `TA-agents` with
  tests + CI + full review.
