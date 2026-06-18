# CareerHub SA - Codex Task Execution Rules

## Objective

Complete ONLY the assigned task.

---

## Context Loading Rules

Read only:

1. docs/context/CODEX_TASK_RULES.md
2. Files explicitly listed in task scope

Do NOT:

- Scan repository root
- Traverse unrelated directories
- Search entire codebase
- Read previous phase outputs
- Analyze future phases

If additional files are required:

- Stop
- Report missing dependency
- Request approval before reading

---

## Modification Rules

Allowed:

- Files listed in scope
- Direct dependencies of scoped files

Not Allowed:

- Global refactors
- Architecture changes outside scope
- Formatting unrelated files
- Dependency upgrades not required

---

## Output Format

### Files Changed

list only modified files

### Validation

show only executed validations

### Risks

show only task-related risks

### Notes

show only implementation notes

---

## Commit Rule

Create one commit only.

---

## Stop Rule

After task completion:

STOP.

Do not continue.

Do not suggest future work.

Do not start another phase.
