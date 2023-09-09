# Simple TypeScript Starter | 2023

### Features

- Minimal
- TypeScript v4
- Testing with Jest
- Linting with Eslint and Prettier
- Pre-commit hooks with Husky
- VS Code debugger scripts
- Local development with Nodemon

### Scripts

#### `yarn dev`

Starts the application in development using `nodemon` and `ts-node` to do hot reloading.

#### `yarn start`

Starts the app in production by first building the project with `yarn build`, and then executing the compiled JavaScript at `build/index.js`.

#### `yarn build`

Builds the app at `build`, cleaning the folder first.

#### `yarn test`

Runs the `jest` tests once.

#### `yarn test:dev`

Run the `jest` tests in watch mode, waiting for file changes.

#### `yarn prettier-format`

Format your code.

#### `yarn prettier-watch`

Format your code in watch mode, waiting for file changes.
