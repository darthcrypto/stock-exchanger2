tutorial used:
https://www.djamware.com/post/5bca67d780aca7466989441f/angular-7-tutorial-building-crud-web-application

#find ip of running port Mac:
lsof -nP -i4TCP:4200


#create a component (automatically adds components to app.module.ts)
ng g component products


###ARCHITECTURE###
#api.service.ts is where the CRUD operations take place, connecting to the backend server


#tutorial on Observables
https://www.techiediaries.com/angular-rxjs-tutorial/


#add angular material to project 
ng add @angular/material

#tutorial on _id (field in MongoDb)
https://www.vividcortex.com/blog/what-is-mongodbs-_id-field-and-how-to-use-it


#starting mongo daemon
mongod -dbpath /tmp/stockdb
mongod

# StockExchanger

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.1.0.

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
