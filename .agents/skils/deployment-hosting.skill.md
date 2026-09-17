# Deployment Hosting Skill

## Purpose
Prepare apps for reliable deployment, hosting, environment configuration, CI/CD, release checks, and rollback planning.

## When To Use It
Use when deploying to Azure, Render, Vercel, Netlify, Cloudflare, Docker, GitHub Actions, mobile app stores, or any production/staging environment.

## Checklist
- Identify app type, runtime, database, background jobs, static assets, and external services.
- Choose hosting that fits the stack, budget, traffic, and operational needs.
- Document build, start, migration, seed, and test commands.
- Define environment variables and secret storage without committing real secrets.
- Add CI checks for restore/install, build, test, lint/typecheck, and package where useful.
- Plan database migrations, backups, health checks, logs, monitoring, and rollback.
- Configure domains, HTTPS, CORS, redirects, caching, and error pages.
- Verify staging before production.

## Rules
- Do not call a project deployed until the actual runtime path is verified.
- Keep deployment steps repeatable.
- Separate build-time config from runtime secrets.
- Prefer boring, documented deployment over clever manual steps.
- Always mention unverified deployment assumptions.

## Output Format
Return:
- Recommended host and why.
- Required environment variables.
- CI/CD or deployment files changed.
- Deployment steps.
- Verification commands.
- Rollback and monitoring notes.

## Common Mistakes To Avoid
- Deploying without documenting env vars.
- Running migrations manually without a plan.
- Forgetting HTTPS, CORS, logs, and health checks.
- Assuming local build success means hosting success.
- Leaving production secrets in source files.

## Example Prompt
Use `_codex/skills/deployment-hosting.skill.md` to prepare this app for deployment. Recommend the host, add CI/deployment files, document env vars, and give me staging-to-production steps.
