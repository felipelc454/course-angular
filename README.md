# Intermediate Angular Course - Digital Innovation One

This course was designed for the [Digital Innovation One](https://digitalinnovation.one/) platform

The course consists of a film system, with the possibility of registering, editing, listing and viewing the films.

## Installation

1. clone the repository `git clone git@github.com:RenanRB/curso-angular.git`
2. Enter the project and install the `npm install` dependencies

## Local Environment

Run `ng serve` and the project will upload locally. Go to url `http://localhost:4200/`. The project is already reloaded automatically depending on the changes you make to the code

## Simulating the Backend

Run `npm install -g json-server` to globally install the json server. After installation go into the project folder and run `json-server --watch db.json`, with that a server will be started at url `http://localhost:3000/`, after startup it will be possible to perform http requests.

## Generating component

Run `ng generate component component-name` to create a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project build. The project will be created inside the `dist/` directory. Add `--prod` along with build command to generate minified and ready for production environment.

