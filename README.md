# goutube
# Gotube

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.0.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

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

README- Youtube API

Before I started
This was a first time to work with PWA (server Worker) And it was a good choice Of (PWA technology) and Youtube API because it’s a hard read documentation.
I was always working by bootstrap framework but also I had to code with Angular Material to make a paging, filter, and sorting.
I selected a Pink color that almost near youtube Color and it’s a quite style color.
I had to change a style of Details Page to fit with any channel too.
    
About The Project
Angular Demo for the Youtube Data API v3 ( Non-OAuth )

Requirements
  •	Npm
  •	TypeScript, a typed superset of JavaScript that compiles to plain JavaScript and provides type capabilities to JavaScript code
  •	Angular, a JavaScript framework that allows you to create efficient and sophisticated single-page applications
  •	RxJS, a library for composing asynchronous and event-based programs by using observable sequences.
  •	API key From Google Console
  •	PWA (server Worker)



Results:
  •	Integrate with YouTube official API. 
  •	 Retrieve a list of videos from a specific YouTube channel (choose any channel as Init channel) 
  •	 The app should cache and display the list of videos while offline after the first run.
  •	2 pages (Home/Details) with SPA (Single page application)

Home Page
  •	list of videos retrieved from integrated YouTube channel including videos date 
    o	Title 
    o	Thumbnail 
    o	View Details button in table view
  •	Implement paging in the video table
  •	Videos can be ordered by each table column when clicked on it.
  •	Adding a search box at top of the table and should search in the videos titles.

Details Page
  •	View full details of selected video
    o	Title 
    o	Upload date
    o	Duration  { still without Pipe to format it}
    o	 # of links 
    o	# of views 
    o	 Description Thumbnail
  •	option to rate the video and adding the video to favorite list. With writing and reading the rate and favorite list from local storage
