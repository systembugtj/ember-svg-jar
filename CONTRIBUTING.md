## Development setup

### Installation

* `git clone <repository-url>` this repository
* `cd ember-svg-jar`
* `npm install`

### Building

* `npm run build`

### Running tests and linting

Run all tests and lint code (`npm run lint && npm run nodetest && ember test`):

```shell
npm test
```

Test node modules (`src` directory):

```shell
npm run nodetest
```

Test Ember related code:

* `ember test`
* `ember test --server`
* `ember try:each`

Lint all code (`src`, `addon`, `app`, `node-tests`, `tests` directories)

```shell
npm run lint
```

### Running the dummy app

* `ember serve`
* Visit the app at [http://localhost:4200](http://localhost:4200)

For more information on using ember-cli, visit [https://ember-cli.com/](https://ember-cli.com/).

# How To Contribute

## Installation

* `git clone <repository-url>`
* `cd my-addon`
* `npm install`

## Linting

* `npm run lint:hbs`
* `npm run lint:js`
* `npm run lint:js -- --fix`

## Running tests

* `ember test` – Runs the test suite on the current Ember version
* `ember test --server` – Runs the test suite in "watch mode"
* `ember try:each` – Runs the test suite against multiple Ember versions

## Running the dummy application

* `ember serve`
* Visit the dummy application at [http://localhost:4200](http://localhost:4200).

For more information on using ember-cli, visit [https://ember-cli.com/](https://ember-cli.com/).
