# VeloCity - README
## See it in action here: [VeloCity](https://velocity-components-tracker.herokuapp.com)

## What the App has been written for
This application works hand in hand with the Activity Logging site Strava.  The problem we have solved is that knowing how far your bike has ridden does not help you judge whether the components on the bike need replacing.

This App monitors the individual components on a bike, and tracks ther use, letting the user know when they have reached their recommended replacement distance.

## User Stories
### Basic
```
As a bike enthusiast I want to know when I need to change a bike component
As a user I want to log into the application to see personalised information about my bike
As a bike enthusiast I want to know how many miles until I need to change my components
As a user I want to be able to add components to be tracked (input brand, first usage date, lifespan)
```
### Advanced
```
As a user I want to be able to tell the app when I have replaced a part
As a user I want to be able to add a different bike to track its components
As a user I want the app to make recommendations on lifespan
```

## Installation
To get a development environment running:
- Install gems and dependencies
```
$ bundle install
$ npm install --check-files
```
- Create development and test env databases and tables
```
$ rails db:create
$ rails db:migrate
$ db:migrate RAILS_ENV=test
```
- Start local server and visit ```http://localhost:3000``` in browser to view VeloCity homepage
```
$ rails s
```

## Technologies Used
| Technology | Description | Use |
| :--------------------------------: | :--------------------------------: | :--------------------------------: |
| Rails ~> v6.0.0 | Web app framework | Back-end API |
| React | JS framework | Front-end user interface |
| Strava API | Fitness activity tracker| Provide user cycling data |
| RSpec | Ruby test framework  | Test Rails models and controllers |
| Jest | React test framework | Test React components |
| Cypress | End-to-end test framework | Test features |
| Postman | HTTP API interface | Simulate HTTP requests |
| ESLint | JS linter | Maintain JS code quality |
| RuboCop | Ruby linter | Maintain Ruby code quality |
| JWT | JSON Web Tokens | Manage authentication |
| PostgreSQL | Database management system | Store app data in database |
| JQuery | JS library | Add dynamic front-end behaviour |

## Development process
TDD processes have been followed in the development of this application.  There have been times when spiking the code was necessary, such as the testing of the Strava API's.

