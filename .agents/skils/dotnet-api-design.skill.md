# .NET API Design Skill

## Purpose
Design clean ASP.NET Core APIs with consistent contracts, validation, errors, and documentation.

## When To Use It
Use for new API endpoints, endpoint reviews, DTO design, route design, and API consistency passes.

## Checklist
- Define resource routes, request DTOs, response DTOs, status codes, and errors.
- Keep controllers thin and delegate business logic to services.
- Validate inputs and model state.
- Use async correctly and support cancellation where practical.
- Document endpoints with OpenAPI/Swagger.

## Rules
- Do not expose EF entities directly.
- Keep response shapes consistent.
- Use meaningful HTTP status codes.
- Avoid business logic in controllers.

## Output Format
Return API contract, implementation plan or changes, validation behavior, tests, and commands run.

## Common Mistakes To Avoid
- Returning raw database models.
- Mixing persistence, validation, and HTTP concerns in one class.
- Inconsistent error responses.

## Example Prompt
Use `_codex/skills/dotnet-api-design.skill.md` to design and implement CRUD endpoints for this resource with DTOs, validation, and tests.
