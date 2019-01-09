# Contributing

> This project is built with [Vue.js], using [Vue CLI]. It uses [Vuex] for state management and
> [vue-router] for routing.

## Issues

Feel free to [♥ open an issue], or [♥♥♥ propose a pull request]. To prevent duplication, please have
a look at [existing issues] before posting a new one.

## Coding standards

- [Airbnb] via [@vue/eslint-config-airbnb],
- [Prettier] via [@vue/eslint-config-prettier], with `singleQuote = true` and `trailingComma = 'all'`.

## Scripts

| Command          | Description                                                                                                   |
| ---------------- | ------------------------------------------------------------------------------------------------------------- |
| **`yarn serve`** | Starts a development server.                                                                                  |
| **`yarn test`**  | Runs [Jest] unit test suite in development mode. Use `CI=true yarn test` to run in CI mode.                   |
| **`yarn e2e`**   | Runs [Cypress] end-to-end test suite in development mode. Use `CI=true yarn e2e` to run in CI mode.           |
| **`yarn lint`**  | Runs [ESLint] and [Prettier] linting and tries to fix errors. Use `CI=true yarn lint` to lint without fixing. |
| **`yarn build`** | Generate a production-ready build in the `dist/` directory.                                                   |

## Getting started

### Step 1. Install dependencies

> **Prerequisites:** you need to have, [NodeJS] and [npm] installed.

```bash
yarn
```

Installs this project dependencies in the `node_modules/` directory.

### Step 2. Start a development server

```bash
yarn serve
```

Spawns a development server on <http://localhost:8080/>.

### Step 3. Run unit tests

```bash
yarn test
```

Runs [Jest] unit test suite in development mode:

### Step 4. Run end-to-end tests

```bash
yarn e2e
```

Spawns a development server and runs [Cypress] end-to-end test suite in development mode.

[vue.js]: https://vuejs.org/
[vue cli]: https://cli.vuejs.org/
[vuex]: https://vuex.vuejs.org/
[vue-router]: https://router.vuejs.org/
[♥ open an issue]: https://github.com/amercier/vue-template/issues/new
[♥♥♥ propose a pull request]: https://github.com/amercier/vue-template/pulls
[existing issues]: https://github.com/amercier/vue-template/issues?q=is%3Aissue
[airbnb]: https://github.com/airbnb/javascript
[prettier]: https://prettier.io/
[@vue/eslint-config-airbnb]: https://www.npmjs.com/package/@vue/eslint-config-airbnb
[@vue/eslint-config-prettier]: https://www.npmjs.com/package/@vue/eslint-config-prettier
[jest]: http://jestjs.io/
[cypress]: https://www.cypress.io/
[eslint]: https://eslint.org/
[nodejs]: https://nodejs.org/
[npm]: https://www.npmjs.com/
[vue cli configuration reference]: https://cli.vuejs.org/config/
