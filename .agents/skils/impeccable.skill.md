# Impeccable Skill

## Purpose
Run a high-standard final polish pass that makes a project feel professional, cohesive, reliable, and ready to show to a client, employer, or real users.

## When To Use It
Use near the end of a feature, app, website, API, portfolio project, client deliverable, or repository cleanup when the goal is not just "working" but excellent.

## Checklist
- Inspect the project structure, README, setup steps, and current implementation before editing.
- Identify the product's main user journey and verify it works end to end.
- Polish UI details: spacing, typography, hierarchy, responsiveness, accessibility, empty states, loading states, errors, and copy.
- Review code quality: clear names, small components/functions, maintainable architecture, no dead code, no needless abstractions.
- Review backend quality when present: DTOs, validation, auth, errors, logging, async usage, and database access.
- Review repository quality: `.gitignore`, `.editorconfig`, `.env.example`, useful README, scripts, CI, and no generated clutter.
- Review security basics: no secrets, safe config, input validation, least privilege, and no sensitive logging.
- Run available build, test, lint, typecheck, and smoke-test commands.
- Separate launch blockers from nice-to-have refinements.

## Rules
- Do not rewrite the project for taste alone.
- Prefer focused improvements with visible user or maintainer value.
- Preserve the existing stack and patterns unless they are causing real harm.
- Treat accessibility, mobile responsiveness, security, and setup documentation as part of quality.
- Be direct about anything that could not be verified.
- Never create or commit secrets.

## Output Format
Return:
- Impeccable verdict: ready, close, or not ready.
- Changes made.
- Files changed.
- Checks run and results.
- Remaining blockers.
- Recommended next refinements.

## Common Mistakes To Avoid
- Calling a project polished because it looks nice on one desktop screen.
- Ignoring setup docs, tests, errors, empty states, and mobile behavior.
- Making broad rewrites without improving the outcome.
- Hiding unrun checks or unresolved risks.
- Adding generic filler content instead of project-specific polish.

## Example Prompt
Use `_codex/skills/impeccable.skill.md` to make this project impeccable. Inspect it first, improve the highest-impact UI, code, documentation, testing, security, and repo-quality issues, then run available checks and give me a readiness verdict.
