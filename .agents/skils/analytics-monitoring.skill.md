# Analytics Monitoring Skill

## Purpose
Add practical product analytics, logging, error tracking, metrics, and monitoring so app behavior and production health are visible.

## When To Use It
Use when adding event tracking, dashboards, error reporting, performance monitoring, health checks, audit logs, alerts, funnels, or production observability.

## Checklist
- Define the questions analytics should answer and the incidents monitoring should catch.
- Track meaningful events: signup, login, onboarding, purchase, booking, search, save, share, error, and conversion actions as relevant.
- Use consistent event names, properties, user ids, anonymous ids, and consent rules.
- Avoid collecting unnecessary personal or sensitive data.
- Add backend structured logs, request correlation, health checks, and error boundaries.
- Configure alerts for downtime, high error rates, failed jobs, payment/webhook failures, and abnormal latency.
- Document tools, event taxonomy, dashboards, and runbook steps.
- Verify events and logs in development or staging.

## Rules
- Measure decisions, not vanity noise.
- Respect privacy, consent, and data minimization.
- Never log secrets, tokens, passwords, or sensitive payloads.
- Make monitoring actionable with owners and thresholds.
- Keep event naming stable and documented.

## Output Format
Return:
- Analytics and monitoring plan.
- Event taxonomy or log fields.
- Files changed.
- Tools/configuration needed.
- Verification steps.
- Privacy and alerting notes.

## Common Mistakes To Avoid
- Tracking everything with no purpose.
- Logging sensitive data.
- Adding analytics only on the frontend while backend failures stay invisible.
- Creating alerts nobody can act on.
- Forgetting to verify events reach the destination.

## Example Prompt
Use `_codex/skills/analytics-monitoring.skill.md` to add product analytics and production monitoring to this app. Define events, add safe logging/error tracking, document dashboards, and verify the flow.
