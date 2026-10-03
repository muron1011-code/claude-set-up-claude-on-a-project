# Project Overview

A small Node.js REST API for managing users and checking service health.

## Commands

* `npm run dev` — start the development server on http://localhost:3000
* `npm test` — run the test suite
* `npm run lint` — run ESLint

## Conventions

* Use CommonJS modules (`require` / `module.exports`), not ES modules.
* Keep one route file per resource in `routes/`, not multiple resources in the same route file.
* Access application data through `db/store.js`, not directly from route handlers.

## Architecture

* `server.js` — application entry point.
* `routes/` — contains one route file per resource.
* `db/store.js` — data access layer.
* `tests/` — automated tests.
