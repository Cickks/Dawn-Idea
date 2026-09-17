# Frontend Design Skill

## Purpose
Design and implement polished frontend experiences that combine strong visual design, clean component structure, responsive behavior, accessibility, and practical product usability.

## When To Use It
Use when creating or improving frontend screens, dashboards, landing pages, forms, navigation, component libraries, responsive layouts, and client-facing web app interfaces.

## Checklist
- Inspect the existing framework, routing, styling approach, and component patterns before changing code.
- Identify the primary user task, screen hierarchy, and most important actions.
- Design layout with clear spacing, typography, alignment, contrast, and visual rhythm.
- Build responsive behavior for mobile, tablet, and desktop.
- Use semantic HTML, accessible labels, keyboard support, visible focus states, and useful alt text.
- Include expected states: loading, empty, error, disabled, hover, focus, active, and success.
- Keep components focused, named clearly, and consistent with the existing design system.
- Verify with build, lint, typecheck, tests, and browser smoke checks when available.

## Rules
- Build the actual usable interface, not a placeholder or marketing shell.
- Prefer established project patterns before adding new UI abstractions.
- Use icons for tool actions when appropriate and label unfamiliar controls with accessible names or tooltips.
- Avoid one-note palettes, oversized decorative sections, unreadable mobile layouts, and nested card clutter.
- Keep text inside its containers at all supported viewport sizes.
- Do not sacrifice accessibility for visual novelty.

## Output Format
Return:
- What changed and why.
- Files changed.
- Responsive and accessibility checks performed.
- Commands run.
- Remaining risks or follow-up improvements.

## Common Mistakes To Avoid
- Making the page prettier without improving workflow clarity.
- Designing only for desktop.
- Creating large components that mix layout, state, fetching, and presentation.
- Adding custom controls where native controls would be more accessible.
- Ignoring focus, keyboard, loading, and error states.
- Overusing gradients, shadows, rounded cards, or generic visual filler.

## Example Prompt
Use `_codex/skills/frontend-design.skill.md` to design and implement this frontend screen like a senior product engineer. Inspect the existing app first, improve the layout, responsiveness, accessibility, and component structure, then run the available checks.
