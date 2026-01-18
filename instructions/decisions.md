# Decision Log

> Version: 0.1.0  
> Purpose: Record significant decisions and their rationale.

This document is used to track important decisions made during a project.
Its goal is to preserve context, reasoning, and trade-offs, not to justify decisions retroactively.

Each entry should be concise, factual, and written at the time the decision is made.

---

## How to Use This Log

- Record decisions that meaningfully affect architecture, scope, behavior, or constraints.
- Do not log trivial or reversible choices.
- Focus on *why* a decision was made, not only *what* was decided.
- Prefer clarity over completeness.

---

## Decision Template

### Decision ID
A short, unique identifier (e.g. DEC-001).

### Date
YYYY-MM-DD

### Status
Proposed | Accepted | Revised | Deprecated

### Context
Describe the situation and constraints that led to this decision.
Include relevant background and assumptions.

### Decision
State the decision clearly and unambiguously.

### Rationale
Explain why this option was chosen.
Highlight the key factors that influenced the decision.

### Alternatives Considered
List reasonable alternatives and why they were not selected.

### Consequences
Describe expected outcomes, trade-offs, and known limitations.
Include both positive and negative consequences if applicable.

### Notes
Optional. Add clarifications, follow-ups, or references.

---

## Example Entry

### Decision ID
DEC-001

### Date
2026-01-18

### Status
Accepted

### Context
A global set of AI instruction rules is required to ensure consistent behavior
across multiple projects and interfaces.

### Decision
Create a centralized `ai-playbook` repository containing global instruction files
(`core.md`, `facts.md`, `style.md`) shared by all projects.

### Rationale
A centralized approach reduces duplication, improves consistency,
and enables controlled evolution of global rules.

### Alternatives Considered
- Duplicating instructions in each project repository (rejected due to drift).
- Relying solely on ad-hoc prompts (rejected due to lack of reproducibility).

### Consequences
- Global changes must be made deliberately.
- Projects gain stability but lose some local flexibility.

### Notes
Initial version established as v0.1.0.
