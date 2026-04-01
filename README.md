# react-base

A minimal, opinionated React starter template built with Vite.

## Stack

| Tool | Version |
|------|---------|
| React | 19 |
| TypeScript | 6 |
| Vite | 8 |
| React Router | 7 |
| SASS | latest |
| ESLint + Prettier | configured |

## Getting Started

```bash
npm install
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

## Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start dev server |
| `npm run build` | Type-check and build for production |
| `npm run lint` | Run ESLint |
| `npm run lint:fix` | Fix lint errors and format |
| `npm run format` | Format source files with Prettier |

## Path Aliases

`@` resolves to `./src`:

```ts
import { MyComponent } from '@/components/MyComponent'
```

## Project Structure

```
src/
  App.tsx       # Root component
  index.tsx     # Entry point
```