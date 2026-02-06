# AI Vibecoding Project — Constraints & Boundaries

## Hard constraints

- Do not assume AI output is correct by default.
- Do not hide uncertainty or missing context.
- Do not generate or reuse proprietary or licensed code.
- Do not skip human validation for architecture, security, or performance.

## Design-to-code rules

- Figma is the visual source of truth.
- Layout, spacing, and typography must be traceable to the design.
- Ambiguities must be stated explicitly.

## Code quality rules

- Generated code must be readable and modular.
- Prefer clarity over clever abstractions.
- Remove unused code immediately.

## AI usage rules

- Prompts must be explicit and contextual.
- Large tasks must be broken into smaller steps.
- When tools disagree, reconcile manually.

## Anti-hallucination rule

If a behavior or API cannot be verified:
treat it as uncertain or exclude it.
