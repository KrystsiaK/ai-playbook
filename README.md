---

## Usage

### With ChatGPT Projects
1. Create a Project in ChatGPT
2. Upload selected files from `ai-playbook`
3. In Project Instructions, explicitly:
   - reference which files are authoritative
   - define precedence rules in case of conflicts

### With Project Repositories
- Each project should have its own repository
- Add a `00_instructions.md` file that:
  - extends or constrains `ai-playbook`
  - does **not** duplicate global rules
  - overrides them only when necessary

---

## What This Repository Does Not Contain

- project-specific business logic
- domain knowledge
- user data
- experimental or temporary instructions

All of the above belong in **project-level repositories**, not here.

---

## Stability and Change Policy

This repository:
- evolves slowly
- changes intentionally
- prioritizes clarity over completeness

Any modification should be minimal, justified, and documented.
