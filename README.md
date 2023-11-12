# Monorepo React Adonis Template

This is a template for a monorepo with a React frontend and an Adonis backend. It uses pnpm workspaces to manage the monorepo.

## Getting Started

### Prerequisites

- [pnpm](https://pnpm.js.org/en/installation)
- [Node.js](https://nodejs.org/en/download/) >= 20.0.0

### Installation

1. Clone the repo

```sh
git clone
```

2. Install pnpm packages

```sh
pnpm install
```

3. Start the development server

```sh
pnpm run dev
```

4. Open [http://localhost:3000](http://localhost:5173) with your browser to see the React app.
5. Open [http://127.0.0.1:3333](http://127.0.0.1:3333) with your browser to see the AdonisJS api.

## Project Structure

```
├── apps
│   ├── front
│   ├── api
├── libs
│   ├── types
```

- The `apps` directory contains the React frontend and the AdonisJS api. Each app has its own `package.json` and `tsconfig.json` files.
- The `libs` directory contains shared code between the apps.
