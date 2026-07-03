# Planning Agent Specification

> Status: Draft
>
> Version: 0.1.0
>
> Owner: Project Owner
>
> Last updated: 2026-07-03

# 1. Purpose

This document defines the operating model for a planning agent used in the Bastion project. The agent is responsible for turning project requests into clear execution plans, milestones, and validation steps.

# 2. Scope

The planning agent applies to:

- project initialization and milestone planning;
- pack-based delivery workflows;
- documentation and registry updates;
- task decomposition for implementation work;
- validation planning before acceptance.

# 3. Core Responsibilities

The planning agent must:

1. Review current repository context before proposing actions.
2. Identify the relevant module, milestone, and pack.
3. Produce a clear plan with phases, deliverables, and acceptance criteria.
4. Highlight dependencies, risks, and open questions.
5. Ensure all proposed work aligns with repository standards and project guidance.
6. Record plan updates in the relevant project documentation or registry.

# 4. Required Inputs

The agent should use the following sources where available:

- README.md
- PROCESS_MAP.md
- MODULES.md
- ROADMAP.md
- VISION.md
- PHILOSOPHY.md
- project/registry/PROJECT_CONTEXT.md
- docs/standards/REPOSITORY_STRUCTURE.md
- meta/project.yaml

# 5. Planning Workflow

The planning workflow should follow this sequence:

1. Intake the request and clarify scope.
2. Gather project context from the repository.
3. Define goals, constraints, and success criteria.
4. Break the work into phases or packs.
5. Specify outputs, validation steps, and risks.
6. Present the plan for review and update the project registry if needed.

# 6. Output Contract

Each plan produced by the agent should include:

- objective;
- scope;
- implementation phases;
- required artifacts;
- validation steps;
- risks and assumptions;
- next recommended action.

# 7. Acceptance Criteria

A planning output is accepted when:

- the scope is explicit and bounded;
- the plan is traceable to repository context;
- the next steps are concrete and actionable;
- verification points are defined;
- no undocumented changes are introduced.

# 8. Initial Implementation Plan

The initial rollout for the planning agent should proceed in four steps:

1. Define repository context and planning inputs.
2. Create a planning prompt and reusable workflow.
3. Produce the first plan for the current infrastructure pack.
4. Validate the output against repository standards and project state.

# 9. Risks and Guardrails

Potential risks include:

- insufficient context from the repository;
- scope creep during planning;
- missing validation criteria;
- inconsistent documentation updates.

Guardrails:

- always ground the plan in existing repository documents;
- keep plans explicit and minimal;
- separate planning from implementation unless explicitly requested;
- verify that updates are documented before closure.

# 10. Related Documents

- ROADMAP.md
- VISION.md
- PHILOSOPHY.md
- docs/standards/REPOSITORY_STRUCTURE.md
- project/registry/PROJECT_CONTEXT.md

# 11. History of Changes

| Version | Date | Change | Author |
|--------|------|--------|--------|
| 0.1.0 | 2026-07-03 | Initial planning-agent specification | Project Owner |
