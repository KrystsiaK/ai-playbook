# SAP Web Components Project — Overview

## Purpose
This project uses **UI5 Web Components** as the UI layer and **OData V4** as the data protocol.
The goal is to build a framework-agnostic frontend without relying on the SAPUI5 runtime.

## Stack (explicit)

- UI: UI5 Web Components (custom elements, shadow DOM)
- Styling: SAP Design System (via UI5 Web Components theming)
- Data: OData V4 services
- Transport: HTTP(S), JSON
- Runtime: Any modern browser (no SAPUI5 bootstrap)

## Explicit non-goals (important)

- ❌ SAPUI5 runtime (`sap.ui.core`, XML Views, Controllers)
- ❌ UI5 Router / Component.js lifecycle
- ❌ OData V2
- ❌ Implicit framework magic (Angular/React-specific abstractions)

## Source of truth

All authoritative documentation links are listed in:
- `docs.md`

When in doubt, this file + `docs.md` define the correct interpretation of the project.

## How to read this project

1. Read `overview.md` (this file)
2. Check `docs.md` for official documentation
3. Check `constraints.md` for strict rules and boundaries
