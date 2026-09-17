# Admin Dashboard Skill

## Purpose
Design and build secure, efficient admin dashboards for managing users, content, bookings, orders, payments, support, settings, and operational workflows.

## When To Use It
Use when building internal tools, CRUD dashboards, role-based admin areas, moderation queues, reports, operational tables, or business owner portals.

## Checklist
- Identify admin users, roles, permissions, workflows, and high-risk actions.
- Design dense but scannable layouts with tables, filters, search, sorting, pagination, and bulk actions where needed.
- Add clear detail views, edit forms, audit history, confirmations, and undo/rollback where practical.
- Enforce authorization server-side for every admin route and action.
- Validate inputs and protect destructive operations.
- Include loading, empty, error, success, and permission-denied states.
- Add audit logs for sensitive actions.
- Verify accessibility, keyboard navigation, responsive behavior, and data table usability.
- Add tests for permissions and critical workflows.

## Rules
- Admin UI should be calm, fast, and operational, not marketing-style.
- Never rely on hidden frontend controls for authorization.
- Make destructive actions explicit and recoverable where possible.
- Prefer clear filters and saved views over overloaded dashboards.
- Keep operational data accurate, current, and exportable when useful.

## Output Format
Return:
- Admin workflow design.
- Roles and permissions.
- Data model/API needs.
- UI screens and components changed.
- Tests and verification steps.
- Remaining operational risks.

## Common Mistakes To Avoid
- Building admin routes without server-side authorization.
- Making dense tables unreadable on smaller screens.
- Missing audit trails for sensitive changes.
- Forgetting pagination and search for growing data.
- Hiding destructive actions behind vague buttons.

## Example Prompt
Use `_codex/skills/admin-dashboard.skill.md` to build a secure admin dashboard for this app. Include role-based permissions, searchable tables, detail/edit views, audit logs, safe destructive actions, and tests for critical admin behavior.
