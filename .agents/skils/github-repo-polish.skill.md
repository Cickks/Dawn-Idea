# GitHub Repo Polish Skill

## Purpose
Make repositories professional, understandable, and ready for collaboration.

## When To Use It
Use when preparing a repo for GitHub, client handoff, portfolio review, or team collaboration.

## Checklist
- Add or improve README, `.gitignore`, `.editorconfig`, license notes if needed, and `.env.example`.
- Confirm clear project structure and setup commands.
- Add GitHub Actions for build/test/lint where practical.
- Add PR template and contribution notes when useful.
- Verify no secrets or generated junk are committed.

## Rules
- Documentation must help someone run the project.
- Keep badges and templates meaningful.
- Avoid generic boilerplate that lies about the project.

## Output Format
Return repo improvements, files changed, verification commands, and remaining setup needs.

## Common Mistakes To Avoid
- README with no real setup instructions.
- Missing environment variable documentation.
- CI that does not run the commands developers actually use.

## Example Prompt
Use `_codex/skills/github-repo-polish.skill.md` to prepare this app repository for a professional GitHub push.
