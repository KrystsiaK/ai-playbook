# SAP Web Components Project — Constraints & Boundaries

## Hard constraints (must not be violated)

- Do NOT assume SAPUI5 runtime APIs are available.
- Do NOT generate SAPUI5-specific code (XML Views, Controllers, `sap.ui.define`).
- Do NOT mix OData V2 and OData V4 semantics.
- Do NOT invent component APIs or properties.
- Do NOT reference undocumented or deprecated APIs.

## Documentation rules

- UI components:
  - Use only UI5 Web Components official docs and GitHub repository.
- OData behavior:
  - Use OASIS / odata.org specifications for protocol rules.
- SAP Help:
  - Use only when explicitly relevant to OData V4 or integration notes.

If no authoritative source exists → explicitly state uncertainty.

## Output rules

- Prefer concrete examples over abstract descriptions.
- Separate facts from interpretation.
- If behavior depends on implementation details, say so explicitly.
- When unsure: stop and ask for clarification instead of guessing.

## Anti-hallucination rule

If an API, property, event, or behavior cannot be traced to an official source:
→ it must be treated as **non-existent**.
