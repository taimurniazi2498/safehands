# SafeHands

Starter for the SafeHands Insurance Quote SPA. It is a Vite + React app with React Router, ESLint and Prettier. The Home page shows the SafeHands logo and a welcome banner.

## Tech

- Vite
- React
- React Router
- ESLint
- Prettier

## Run locally

```bash
npm install
npm run dev
```


Then open the link shown in the terminal (for example http://localhost:5173/). The Home page loads at `/`.

## Scripts

- `npm run dev` starts the dev server
- `npm run build` creates a production build
- `npm run lint` checks the code with ESLint
- `npm run format` formats the code with Prettier

## Project structure

```
src/
  assets/       images (logo.svg)
  components/   reusable components (Home)
  pages/        route pages (HomePage)
  App.jsx       routes
  main.jsx      entry point with BrowserRouter
  ```
  