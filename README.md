# Dawn Idea

A website starter built with React, Vite, TypeScript, and custom CSS. The development foundation is ready; the client brief, content, pages, and visual design still need to be defined. This is not a completed client website.

## Get started

Install Node.js 24 and npm, then run:

```sh
git clone https://github.com/Cickks/Dawn-Idea.git
cd Dawn-Idea
npm ci
npm run dev
```

Open the local URL printed by Vite. No environment variables are required.

## Commands

| Command | Purpose |
| --- | --- |
| `npm run dev` | Start the development server with live updates. |
| `npm run lint` | Check source code with Oxlint. |
| `npm run build` | Run TypeScript checks and create the production build in `dist/`. |
| `npm run preview` | Preview the production build locally after building. |

Before opening a pull request, run `npm ci`, `npm run lint`, and `npm run build`. There is no dedicated automated test suite yet. GitHub Actions runs these installation, lint, and build checks using Node.js 24 on pushes to `main` and `mikedev/**`, pull requests, and manual runs.

## Project structure

```text
.agents/
  agents/             Role instructions and collaboration workflow
  skils/              Reusable project skills (existing directory spelling)
.github/workflows/    GitHub Actions CI
public/               Static assets
src/
  assets/             Assets imported by application code
  App.tsx             Starter page
  App.css             Page styles
  index.css           Global styles
  main.tsx            React entry point
AGENTS.md             Project instructions
STARTER_STATUS.md     Decisions, current status, and remaining work
```

## Branch workflow

| Branch | Purpose |
| --- | --- |
| `main` | Stable project baseline. |
| `mikedev/develop` | Integration branch for reviewed changes. |
| `mikedev/first-code` | First website implementation. |

Start implementation on `mikedev/first-code`. Open a pull request into `mikedev/develop`, then promote reviewed work through a pull request from `mikedev/develop` into `main`. This is the intended collaboration workflow; it does not imply branch protection is configured.

```sh
git fetch origin
git switch mikedev/first-code
```

## Project guidance

See [AGENTS.md](AGENTS.md) for the agent and skill workflow, and [STARTER_STATUS.md](STARTER_STATUS.md) for current decisions and the next-session handoff.

Keep secrets and local references out of Git. Any future `VITE_` variables are browser-visible and must not contain secrets.

## License

[MIT](LICENSE).
