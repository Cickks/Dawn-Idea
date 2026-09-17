# Dawn Idea project instructions

## Project
- Stack: React, Vite, TypeScript, custom CSS, npm, Node 24.
- Phase: verified starter; client requirements and design remain to be defined.
- Preserve the selected stack and existing work. Add dependencies or services only when needed.

## Agents and skills
- Read `.agents/agents/README.md` and the applicable role before implementation.
- Lead Software Engineer coordinates scope and reviews results. Assign one focused specialist at a time with a concrete brief and acceptance criteria.
- Read relevant files in `.agents/skils/` before work; the existing directory is spelled `skils`.
- Use Product Manager for unclear requirements, UI/UX Designer for design, Frontend Engineer for React, QA for significant behavior changes, DevOps for CI, and Security Reviewer for sensitive features.
- Apply installed skills when relevant. Report the roles, skills, and verification used.
- Requirements from other projects in reusable guidance do not become Dawn Idea requirements.

## Local references
- If present, read the ignored `WORKSPACE.local` for machine-specific references supplied by the owner.
- Local references are optional development resources, not build dependencies. Do not publish their contents or filesystem paths.
- Inspect an authorized reference template before adapting suitable components. Preserve its original files and replace project-specific content and assets.

## Verification
- Use `npm ci`, `npm run lint`, and `npm run build`.
- Check desktop/mobile behavior and accessibility for UI changes.
- No environment variables are currently required; `VITE_` variables are browser-visible.
- Keep secrets, dependencies, generated files, and private local references out of Git.
- Review diffs and report actual checks and limitations.
- Follow the user's authorized Git scope; do not force-push or deploy without explicit authorization.
