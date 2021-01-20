# AngularTemplate

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.0.5 with the following command:

> ```ng new angular-template --commit=false --create-application=false --directory=202101-angular-template --new-project-root=libs --prefix=temp --routing=false --skip-git=true```

## Applications

The applications are stored in the `libs` folder via `ng generate application application-name`.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

To start different applications within the workspace use the `--project` argument with the name of the project, e.g. `ng serve --project=second-app`

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running lint

Run `ng lint` to execute the linting via [TSLint](https://github.com/palantir/tslint). However `TSLint` is deprecated and replaced by [ESLint](https://github.com/eslint/eslint). To generate a new application with `ESLint` by default use the `--collection=@angular-eslint/schematics` argument. Make sure you've installed `npm i @angular/cli @angular-devkit/{core,schematics} @angular-eslint/schematics` before creating the new application.

### Migrating to ESLint

Following the official documentation of the [Angular-ESLint](https://github.com/angular-eslint/angular-eslint#migrating-an-angular-cli-project-from-codelyzer-and-tslint) Migration.

First run `ng add @angular-eslint/schematics`. Afterwards run `ng g @angular-eslint/schematics:convert-tslint-to-eslint {{YOUR_PROJECT_NAME_GOES_HERE}}` on all projects within the workspace. When finished simply remove the `tslint.ts` file from your workspace and uninstall all `TSLint` related plugins/dependencies `npm uninstall tslint`.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
