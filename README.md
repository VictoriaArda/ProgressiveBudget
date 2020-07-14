# Unit-18-PWA-Homework-Online-Offline-Budget-Trackers

Refactoring an existing online only budget app to work offline and online.

## User Story

As a frequent traveller I need to keep on top of my budget, even when in areas with a poor internet connection. Being able to update my budget offline and have it update correctly when I have an internet connection again.

## MVP

User should be able to:
* 1) App can be taken offline
* 2) Deposits and withdrawals can be made offline
* 3) When back online the deposits and withdrawals update the database

## Process

Using provided code refactor to take offline, adding Service Worker, web-manifest & cache API:

* 1) Add Manifest file. Add link in HTML file header
* 2) Add service-worker. Add script link in HTML.
* 3) Add db.js to save to indexedDb, add link to script in HTML (before Index.js link)


### Requirements

Web manifest file
Service worker js
NPM Mongoose
Npm Express


## Deployment

Github Repo: https://github.com/VictoriaArda/ProgressiveBudget

Heroku Deployed App: https://progressivebudget2020.herokuapp.com/

## Author

Victoria Arda