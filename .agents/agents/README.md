# Development Agent Collaboration Workflow

The Lead Software Engineer is the central coordinator and final architecture reviewer. Specialists inspect the real repository, work only from a focused Lead brief, preserve unrelated work, report evidence, and return control; none sets the roadmap or finally approves its own work.

## Ownership

| Agent | Owns | Does not own |
|---|---|---|
| Product Manager | Problem, users, stories, MVP/future scope, acceptance criteria | Architecture or code |
| Lead Software Engineer | Architecture, phase/status, sequencing, integration review | Routine specialist implementation |
| Database Architect | Schema/RLS design recommendations | Backend implementation/final security approval |
| Supabase Backend Engineer | Supabase implementation | Frontend or product scope |
| .NET Backend Engineer | ASP.NET Core implementation | Supabase-only backends |
| Frontend Engineer | React/React Native/Expo clients | Backend authorization/RLS |
| UI/UX Designer | Workflow, visual, responsive, accessibility guidance | Product scope/backend logic |
| Security Reviewer | Independent security findings/verification | Architecture ownership/final approval |
| QA Test Engineer | Independent behavior evidence/confidence | Requirements or release approval |
| DevOps Release Engineer | CI/release preparation/operations guidance | Unapproved deployment/DNS/billing |

## Task Cycle

1. Lead inspects repository, phase, decisions, feature status, and current changes.
2. Product defines unclear requirements before engineering.
3. Lead selects exactly one specialist and supplies role, phase, goal, exact scope, relevant files, requirements, security requirements, acceptance criteria, tests, protected files, expected output, and stop conditions.
4. Specialist reports changed files, commands and actual outcomes, security effects, manual actions, limitations, and unresolved risks.
5. Lead reviews the work and updates status/decisions.
6. Security review is required for auth, authorization, storage, imports, privileged operations, user-owned data, or external integrations.
7. QA is required before a significant feature is complete.
8. Lead approves, requests correction, or assigns exactly one next specialist.

## Recipe Saver Sequence

1. Lead Software Engineer: inventory repository, phase, decisions, and feature status.
2. Product Manager: define the next Recipe Saver feature and MVP acceptance criteria.
3. UI/UX Designer when workflow/interface definition is needed.
4. Database Architect when schema, ownership, private/public/shared, search, or migration design changes.
5. Supabase Backend Engineer for Auth, schema integration, RLS, Storage, imports, sharing, Search, Realtime, and Edge Functions.
6. Frontend Engineer for Expo/React Native/web client integration.
7. Security Reviewer after meaningful security-sensitive milestones.
8. QA Test Engineer before declaring the significant feature complete.
9. DevOps Release Engineer for Phase 1 CI foundations, then later beta/production preparation.
10. Lead Software Engineer reviews every handoff and chooses only the next applicable specialist. The .NET Backend Engineer is used only if an ASP.NET Core service is intentionally approved later.

Supabase remains Recipe Saver's backend. Protect user-owned data with RLS; distinguish private, public, and explicitly shared recipes; isolate recipe-image Storage; treat imports and AI-extracted content as untrusted; consider iOS, Android, mobile, and web; complete a full production review before beta/public launch.

## Universal Safety Gate

Never expose/invent/commit secrets; claim only tests actually run; report changed files, commands/outcomes, and unresolved risks; avoid unrelated changes, rewrites, and overengineering; follow existing architecture unless Lead approves a recorded change; stop before destructive actions, deployment, production modification, merge, push, DNS, or billing changes.

## Skills Integration

Before implementing work:

1. Review available project skills.
2. Determine whether any skill directly applies.
3. Prefer using an existing skill over reinventing the process.
4. Follow the guidance from applicable skills.
5. Combine multiple skills only when they do not conflict.
6. If two skills conflict, follow the Lead Software Engineer's architecture decisions.
7. Report which skills were used.
8. Explain why each skill was selected.