# MissionariesMapApp

Hi Ken, I added some documentation to get started in this app, good luck.

## Getting started
- You will first need to install https://code.visualstudio.com/ , this is what I use for a code editor.
- then you need to download Node js: https://nodejs.org/en/ , this will be for JavaScript librarys.
- after that you can install the Angular command line by typeing `npm install -g @angular/cli` into your terminal, you can reference the docs here: https://angular.io/cli
- If you don't have a github account you will need to create one and then download the git comand line tool, docs are here: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
- After you have git installed you can do `git clone https://github.com/mikegg89/MissionariesMap.git`
- follow the prompt to cd into the app and you can use `npm i` to download all the JavaScript dependancies for the app.
- Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

Look in app/map/map.component.ts to get started in the JavaScript
Look in app/map/map.component.html to edit the HTML look and feel of the app, I set the map to be the full view of the screen but this can be adjusted with the height and width.

Hope this helps, feel free to reach out if you need any help.

# OpenLayers
OpenLayers is the JavaScript Library for interfacing with https://www.openstreetmap.org/
Docs: https://openlayers.org/en/latest/apidoc/module-ol_control_Zoom-Zoom.html


# Angular Documentation
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.1.2.

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
