# Code Review Skill

## Purpose
Review code for bugs, regressions, maintainability, security, performance, and missing tests.

## When To Use It
Use for PRs, diffs, commits, working-tree changes, or focused file reviews.

## Checklist
- Inspect the diff and relevant surrounding code.
- Prioritize bugs and behavioral risks over style preferences.
- Check tests, validation, error handling, security, and edge cases.
- Reference exact files and lines where possible.
- Keep summary brief after findings.

## Rules
- Lead with findings ordered by severity.
- Do not bury serious issues in prose.
- Mention when no issues are found and identify residual test gaps.

## Output Format
Findings first, then open questions, then brief summary and verification gaps.

## Common Mistakes To Avoid
- Giving compliments before defects.
- Reporting style nits as major issues.
- Reviewing code without reading the surrounding behavior.

## Example Prompt
Use `_codex/skills/code-review.skill.md` to review this PR like a senior engineer and focus on bugs, security, and missing tests.
