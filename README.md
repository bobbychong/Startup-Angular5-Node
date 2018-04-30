# Angular 5 and Node Application Startup

* Start up repository for Angular5/Node Application

## Installation

* Install NodeJS
* Clone repository
* `npm install` from root folder

## Development Workflow

Running the application for development purposes
This will require 2 tabs in your terminal

Startup server
* node backend/app.js

Startup Angular application
* `ng serve`

Node services will be on port 3000 and the Angular application will be served on port 4200

To proxy the server to same port as the Angular application for development
* `npm start`
* This will allow your application

## Deployment

For installation on remote server/Docker
* npm installation
* ng build --production
* node backend/app.js
