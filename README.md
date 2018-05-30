# SamCli

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.4.10.

## Setup local development
Follow these steps to checkout sam-ui-elements in separate location in your local environment
```
git clone https://github.com/GSA/sam-ui-elements
cd sam-ui-elements
git checkout main
npm link --only=production
```

To link and setup your cloned environment
```
git clone https://github.com/GSA/sam-design-system-site
cd sam-design-system-site
git checkout develop
npm install
npm link sam-ui-elements
npm run start
```

For builds, update of `sam-ui-elements` version in the Dockerfile. Run this command to see the available tags:

```
npm dist-tag ls sam-ui-elements --registry https://artifactory.helix.gsa.gov/artifactory/api/npm/ART-001-GP-SFE-npm
```

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
