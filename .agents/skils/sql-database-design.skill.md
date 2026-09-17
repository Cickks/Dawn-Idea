# SQL Database Design Skill

## Purpose
Design relational databases with clear schemas, constraints, indexes, and performance expectations.

## When To Use It
Use for schema planning, ERDs, SQL review, migrations, reporting needs, and performance investigations.

## Checklist
- Identify entities, relationships, cardinality, and lifecycle.
- Normalize data unless denormalization has a clear reason.
- Add primary keys, foreign keys, unique constraints, and indexes.
- Plan seed data and migration order.
- Check query patterns and growth risks.

## Rules
- Prefer data integrity in the database, not only in application code.
- Name tables, columns, and constraints clearly.
- Index for real queries, not guesses.

## Output Format
Return ERD summary, schema proposal, indexes, migration plan, and validation queries.

## Common Mistakes To Avoid
- Missing constraints for important business rules.
- Over-indexing without query evidence.
- Storing structured data as blobs without a reason.

## Example Prompt
Use `_codex/skills/sql-database-design.skill.md` to design the database schema for this app and include indexes and migration notes.
