# Document Status

> Purpose: Track the lifecycle status of key project documents.

---

# Status Definitions

| Status | Meaning |
|--------|---------|
| Planned | Document is expected but not yet created. |
| Draft | Document exists but is not finalized. |
| Active | Document is current and usable. |
| Deprecated | Document is retained for history but should not be used as the current source. |
| Archived | Document is historical and no longer maintained. |

---

# Current Document Status

| Document | Path | Status | Owner | Notes |
|----------|------|--------|-------|-------|
| PROJECT_CONTEXT.md | project/registry/PROJECT_CONTEXT.md | Active | Project Registry | Primary human-readable project context. |
| PROJECT_STATE.yaml | project/registry/PROJECT_STATE.yaml | Active | Project Registry | Primary machine-readable project state. |
| DOCUMENT_INDEX.md | project/registry/documents/DOCUMENT_INDEX.md | Active | Project Registry | Central document map. |
| DOCUMENT_STATUS.md | project/registry/documents/DOCUMENT_STATUS.md | Active | Project Registry | Document lifecycle tracking. |
| MILESTONE_HISTORY.md | project/registry/history/MILESTONE_HISTORY.md | Active | Project Registry | Milestone history. |
| CHANGELOG.md | project/registry/history/CHANGELOG.md | Active | Project Registry | Registry change history. |
| DECISION_LOG.md | project/registry/history/DECISION_LOG.md | Active | Project Registry | Structured project decisions. |
| AGENT_PLAN.md | docs/standards/AGENT_PLAN.md | Active | Standards | Agent planning standard. |
| AI_CONNECTION.md | docs/standards/AI_CONNECTION.md | Active | Standards | AI collaboration standard. |

---

# Maintenance Rules

1. Every new registry document must be added to DOCUMENT_INDEX.md.
2. Every tracked document must have a lifecycle status.
3. Deprecated documents must include a replacement reference when applicable.
4. Major documentation changes must be reflected in CHANGELOG.md.
5. Project-level decisions must be reflected in DECISION_LOG.md.

---

Last Updated: 2026-07-03
