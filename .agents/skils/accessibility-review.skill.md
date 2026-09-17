# Accessibility Review Skill

## Purpose
Find and fix accessibility barriers in web, mobile, and API-driven product interfaces.

## When To Use It
Use before launch, after UI changes, or when forms, navigation, modals, dashboards, or complex controls are added.

## Checklist
- Check semantic structure, labels, roles, headings, and landmarks.
- Verify keyboard navigation, focus order, focus styles, and escape behavior.
- Review contrast, text size, target size, motion, and responsive zoom tolerance.
- Confirm form errors are clear and programmatically associated.
- Test screen-reader-friendly names for buttons, icons, images, and inputs.

## Rules
- Fix the source of the barrier, not just symptoms.
- Prefer native HTML controls where possible.
- Do not rely on color alone.

## Output Format
Lead with findings by severity, then fixes applied, files changed, and checks run.

## Common Mistakes To Avoid
- Adding `aria` where semantic HTML would work better.
- Hiding focus outlines without replacement.
- Leaving icon-only buttons unnamed.

## Example Prompt
Use `_codex/skills/accessibility-review.skill.md` to audit this UI and fix high-impact accessibility issues.
