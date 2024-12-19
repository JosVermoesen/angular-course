# AngularMovies

## Development Tools used for this app on december 2024

- [Install NVM for different versions of NodeJS)](https://github.com/coreybutler/nvm-windows/releases)
- In terminal `nvm install 20.14.0` and `nvm use 20.14.0`

- [Angular CLI v17)](https://www.npmjs.com/package/@angular/cli): `npm i -g @angular/cli@17`
- [Visual Studio Code](https://code.visualstudio.com/)

## Favorite extensions and settings

- [MarkDown Lint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
- [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)
- In settings 'brackets', activate Bracket Pair Colorization and Editor guides true
- In settings 'auto close', set 'Auto Closing Brackets' and 'Auto Closing Quotes' to 'always'

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
