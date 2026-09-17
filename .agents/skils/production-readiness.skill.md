# Production Readiness Skill

## Purpose
Assess whether an app is ready to deploy, demo, sell, or hand off.

## When To Use It
Use before launch, client delivery, portfolio publication, deployment, or major release.

## Checklist
- Run build, tests, lint, and smoke checks.
- Review configuration, secrets, logging, error handling, security, accessibility, and performance.
- Confirm README, environment examples, CI, and deployment notes.
- Check backups, migrations, rollback, monitoring, and support expectations where relevant.
- List launch blockers separately from nice-to-haves.

## Rules
- Be honest about risk.
- Separate verified facts from assumptions.
- Do not call production-ready if critical checks did not run.

## Output Format
Return readiness verdict, blockers, recommended fixes, checks run, and go-live checklist.

## Common Mistakes To Avoid
- Treating "works locally" as production-ready.
- Ignoring secrets, logging, and deployment config.
- Hiding unrun checks.

## Example Prompt
Use `_codex/skills/production-readiness.skill.md` to audit this repo and tell me what blocks a real launch.
