# Dawn Idea

Website starter built with React, Vite, and TypeScript.

## Development

Use Node.js 24 LTS and npm.

```sh
npm install
npm run dev
```

## Checks and production build

```sh
npm run lint
npm run build
npm run preview
```

The production build is written to `dist/`.

## Project structure

- `src/App.tsx`: starter page
- `src/App.css`: page styles
- `src/index.css`: global styles
- `public/`: static assets
- `.agents/`: existing project agent resources

Environment files are ignored by Git. Only variables prefixed with `VITE_` are exposed to the browser; never put secrets in them.
