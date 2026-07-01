# Talent Angels — Constitution

## Non-negotiables
- Every graph node keys off a stable taxonomy-native ID (ESCO uri,
  onet_soc_code, SFIA code, etc.) — never a human-readable label.
- Cross-domain edges must be traceable to a source (loaded from file vs.
  inferred) — no silent inference, per O*NET Sprint 1 finding.
- All architecture decisions >1 sprint in scope go through an ADR in
  docs/decisions/, mirrored to TA-memory/decisions/.
- Agent/Subagent/Skill/Tool vocabulary follows Alberto Ceballos's model
  exactly (see reference below) — don't invent competing terms.
- git commit -s (DCO) on every PR.

## Reference
- Agent taxonomy: top-down (Agent→Subagent→Skill→Tool) and bottom-up
  (Tool→Skill→Subagent→Agent) definitions — Alberto Ceballos, Sprint 2 notes.
