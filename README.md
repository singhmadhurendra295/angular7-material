# Ng7FeatureModule

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

Create angular app with routing
ng new ng7-feature-module[project-name] --routing

Add module such as user ,booking etc in angular
ng generate module user[module-name]

Add module such as user ,booking etc in angular with routing
ng generate module user[module-name] --routing

Create component under the project modules
ng generate component user/registration[module-name/component-name]

Create service in angular app
ng generate service user[service-name]
ng generate service services/user[folder-name/service-name]

Add external library such as angular material
ng add @angular/material[external-lib]

Create auth guard in application
ng generate g auth[auth-file-name]
ng generate g auth/auth[folder-name/auth-file-name]
