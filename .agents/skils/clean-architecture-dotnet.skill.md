# Clean Architecture .NET Skill

## Purpose
Structure .NET applications so domain, application, infrastructure, and presentation concerns stay maintainable.

## When To Use It
Use for new ASP.NET Core projects, architecture refactors, service boundaries, and dependency direction reviews.

## Checklist
- Identify project type, domain model, use cases, and external dependencies.
- Keep domain/application logic independent from ASP.NET and EF where practical.
- Place infrastructure behind interfaces when it improves testability.
- Keep controllers thin and services focused.
- Add tests around application behavior.

## Rules
- Do not over-engineer small apps.
- Use clean architecture to reduce coupling, not to create ceremony.
- Keep names clear and folders predictable.

## Output Format
Return proposed structure, dependency rules, changed files, tests, and tradeoffs.

## Common Mistakes To Avoid
- Creating too many projects for a tiny API.
- Hiding simple logic behind needless interfaces.
- Letting EF entities become public API contracts.

## Example Prompt
Use `_codex/skills/clean-architecture-dotnet.skill.md` to structure this ASP.NET Core API for maintainable growth without over-engineering it.
