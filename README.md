# Web Portfolio

Personal portfolio built with **React + TypeScript + Vite**. The current app is an intentionally minimal starting point: the Studio design will be translated into real components and responsive CSS in later iterations.

## Run locally

Requires a Node.js version supported by Vite 7 (Node 20.19+ or 22.12+).

```bash
npm install
npm run dev
```

## Scripts

- `npm run dev` — start development server
- `npm run typecheck` — run TypeScript checks
- `npm run build` — type-check and produce a `dist/` build
- `npm run preview` — preview the production build

## Project layout

```text
public/assets/       Static media (including future satin video)
src/components/      Reusable UI components
src/styles/          Tokens, global reset, and layout styles
src/App.tsx          Application entry component
src/main.tsx         React DOM bootstrap
```

No UI framework, routing, or animation library has been added yet. We'll introduce tools only when the design needs them.
