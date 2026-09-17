# Frontend Refactor Skill

## Purpose
Improve frontend code structure without changing intended behavior.

## When To Use It
Use when components are too large, styling is duplicated, state is tangled, or frontend code is hard to maintain.

## Checklist
- Inspect framework, routing, component conventions, and tests.
- Identify behavior that must remain unchanged.
- Extract components only when they reduce real complexity.
- Consolidate styling and state carefully.
- Run lint, typecheck, tests, and smoke checks.

## Rules
- Keep the refactor scoped.
- Preserve public behavior and accessibility.
- Follow existing patterns before adding new abstractions.

## Output Format
Return refactor summary, files changed, behavior preserved, checks run, and follow-up opportunities.

## Common Mistakes To Avoid
- Large rewrites without tests or visual verification.
- Creating abstractions for one-off code.
- Changing UI behavior accidentally.

## Example Prompt
Use `_codex/skills/frontend-refactor.skill.md` to simplify this React screen while preserving behavior and improving testability.
