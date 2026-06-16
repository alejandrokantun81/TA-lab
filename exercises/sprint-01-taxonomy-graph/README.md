# Sprint 1 — Research & build a taxonomy graph

**Weeks 1–2 · Foundations** (see `TA-workspace/ROADMAP.md`).

This is the warm-up sprint. The point is **not** production code — it's to get
hands-on with knowledge graphs and the taxonomies, and for mentors to see how
each of you works.

## Goals

1. **Understand knowledge graphs** — nodes, edges, properties; how to model and
   query them. Collect what you learn in `TA-resources/knowledge-graphs/`.
2. **Pick one taxonomy** (ESCO, O*NET, SFIA, BLS, or Lightcast) and **build a
   small graph** of part of it — e.g. a handful of occupations linked to their
   skills/tasks.
3. **Reflect** — what's the data model? What's hard? What would Locator /
   Connector need from this graph?

## What to deliver

In your own folder `mentees/<your-github-handle>/sprint-01/`:

- A short **`NOTES.md`**: which taxonomy, where the data came from (link + its
  license), the graph model you chose, and what you learned (theory + practice).
- The **graph itself** in any form you like: a Cypher script, a small Neo4j dump,
  a notebook, a Python script, a diagram, even a hand-drawn model. Anything that
  shows the nodes/edges and how you'd traverse them.
- A couple of **example questions** your graph can answer (e.g. "what skills does
  occupation X require?").

## How it's reviewed

Light review, learning-focused. Mentors look at your reasoning and approach, not
polish. Open a PR, `git commit -s` (DCO), and request a review.

## Tips

- Don't try to load a whole taxonomy. A small, correct slice beats a huge mess.
- Keep large downloads out of git — link to the source instead.
- Use whatever AI coding agent you like; have it read this repo's `CLAUDE.md`
  first. You own and must understand what you submit.
