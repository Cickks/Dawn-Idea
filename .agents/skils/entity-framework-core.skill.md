# Entity Framework Core Skill

## Purpose
Use EF Core safely for modeling, migrations, querying, performance, and data integrity.

## When To Use It
Use when adding entities, relationships, DbContext configuration, migrations, seed data, or query optimization.

## Checklist
- Model relationships, required fields, constraints, and delete behavior.
- Configure entities with fluent configuration when needed.
- Create and review migrations before applying.
- Avoid inefficient queries and accidental tracking.
- Add integration tests for important data behavior.

## Rules
- Use migrations intentionally and keep them reviewable.
- Avoid lazy loading surprises unless explicitly chosen.
- Use `AsNoTracking` for read-only queries where useful.
- Do not expose entities through API responses.

## Output Format
Return model changes, migration notes, query considerations, tests, and commands run.

## Common Mistakes To Avoid
- Treating migrations as unreviewed generated noise.
- Loading entire tables for simple queries.
- Misconfigured cascade deletes.

## Example Prompt
Use `_codex/skills/entity-framework-core.skill.md` to add this relationship, create the EF Core migration, and verify the generated schema.
