# Documentation Skill

## Purpose
Create clear, useful documentation for setup, architecture, APIs, workflows, and handoff.

## When To Use It
Use for README files, API docs, architecture notes, onboarding guides, runbooks, and release notes.

## Checklist
- Identify the reader and their goal.
- Include exact setup, run, test, and build commands.
- Document environment variables without secrets.
- Explain architecture only where it helps maintenance.
- Keep docs current with the code.

## Rules
- Prefer specific commands and paths over vague descriptions.
- Avoid filler and aspirational claims.
- Keep examples copy-paste friendly.

## Output Format
Return docs created/updated, intended audience, important commands, and known missing information.

## Common Mistakes To Avoid
- Writing docs that do not match the repo.
- Omitting environment setup.
- Creating long docs nobody can scan.

## Example Prompt
Use `_codex/skills/documentation.skill.md` to write a README that helps a new developer run, test, and understand this project.
