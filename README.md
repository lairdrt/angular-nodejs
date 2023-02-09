# Installing Node.js and Angular on a Raspberry Pi Zero 2 W

Installing and using [Node.js](https://nodejs.org/en/) and [Angular](https://angular.io/) on a very resource-constrained microcomputer such as the [Raspberry Pi Zero 2 W](https://www.raspberrypi.com/products/raspberry-pi-zero-2-w/) requires optimizing memory usage so that the build/deploy chain does not cause the OS to kill processes that tend to exhaust available resources.

The following describes the steps required to install and successfully use both Node.js and Angular to build viable applications on a Raspberry Pi. The tutorial below was completed successfully using the Raspberry Pi Zero 2 W (having 512MB RAM) with the OS configured as given below.

## Version Information

**Target hardware:** Raspberry Pi Zero 2 W

**Target OS:** Raspbian GNU/Linux 11 (bullseye)

**Angular CLI:** 15.1.4

**Node:** 18.14.0

**Package Manager:** npm 9.4.1

**Angular:** 15.1.3

<hr>

# AngularTourOfHeroes

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.1.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
