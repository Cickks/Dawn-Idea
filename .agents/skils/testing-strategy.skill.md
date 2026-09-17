# Testing Strategy Skill

## Purpose
Create practical automated and manual testing plans that match project risk.

## When To Use It
Use for new features, release checks, refactors, API work, UI changes, and bug fixes.

## Checklist
- Identify critical behavior and failure modes.
- Choose unit, integration, API, UI smoke, or end-to-end tests appropriately.
- Cover happy path, validation, auth, boundaries, and regressions.
- Keep tests deterministic and readable.
- Run the relevant test commands.

## Rules
- Test behavior over implementation.
- Add the smallest useful coverage for the risk.
- Prefer fast tests unless a full-stack check is needed.

## Output Format
Return test plan, tests added, commands run, failures, and remaining gaps.

## Common Mistakes To Avoid
- Writing brittle snapshot-only tests.
- Ignoring negative paths.
- Calling work complete without running tests.

## Example Prompt
Use `_codex/skills/testing-strategy.skill.md` to add meaningful tests for this feature and run the relevant checks.
