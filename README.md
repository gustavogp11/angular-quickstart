# AngularQuickstart

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.2.1.

This project is just the angular project generated with `ng new <app-name>` with the following additions:
1. A common layout (`app.component.html`)
2. Example of Lazy-loading modules 
3. Routing between 3 example pages

### Modules and creation
There are 3 modules in the example: home, configuration and statistics. The modules have been generated using:
`ng generate module home --route home --module app.module`    
`ng generate module configuration --route configuration --module app.module`    
`ng generate module statistics --route statistics --module app.module`    

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
