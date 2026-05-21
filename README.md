# Practice GitHub Actions Project

This is a React + Vite practice project for learning GitHub Actions workflows.

The app includes a small React UI, tests with Vitest and React Testing Library, linting with ESLint, and GitHub Actions workflows for running project checks.

## Getting Started

Install dependencies:

```sh
npm install
```

Start the development server:

```sh
npm run dev
```

## Available Scripts

Run the linter:

```sh
npm run lint
```

Run tests:

```sh
npm test
```

Build the project:

```sh
npm run build
```

Preview the production build:

```sh
npm run preview
```

## GitHub Actions

The project includes workflow examples in `.github/workflows`.

`deploy.yml` runs the main project checks in order:

1. Lint
2. Test
3. Build
4. Simulated deploy step

`issues.yml` runs when GitHub issues events occur and prints event details for practice.

## Tech Stack

- React
- Vite
- Vitest
- React Testing Library
- ESLint
- GitHub Actions
