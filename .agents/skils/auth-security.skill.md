# Auth Security Skill

## Purpose
Review and implement safer authentication, authorization, secrets, and API security defaults.

## When To Use It
Use for login flows, roles/claims, JWT/cookie auth, protected APIs, CORS, secrets, and security reviews.

## Checklist
- Identify identity provider, session/token model, roles, and permissions.
- Enforce authorization server-side on every protected operation.
- Validate input and avoid leaking sensitive errors.
- Protect secrets with environment variables or a secret manager.
- Review CORS, CSRF, rate limiting, HTTPS, headers, and logs.

## Rules
- Never commit secrets.
- Deny by default.
- Do not trust client-side checks.
- Log security-relevant events without sensitive data.

## Output Format
Lead with risks, then fixes, files changed, verification, and remaining security assumptions.

## Common Mistakes To Avoid
- Confusing authentication with authorization.
- Putting secrets in config files.
- Returning too much detail from auth failures.

## Example Prompt
Use `_codex/skills/auth-security.skill.md` to review this ASP.NET Core auth flow and fix unsafe defaults.
