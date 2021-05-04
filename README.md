### 1. Install Cypress

[Follow these instructions to install Cypress.](https://on.cypress.io/guides/installing-and-running#section-installing)

### 2. Git clone repoo
```
## clone this repo to a local directory
git clone git@github.com:damien-cooke/cypress-interview.git

## cd into the cloned repo
cd cypress-interview

## install the node_modules
npm install

## start the local webserver
npm start
```

The `npm start` script will spawn a webserver on port `8888` which hosts the TodoMVC app.

You can verify this by opening your browser and navigating to: [`http://localhost:8888`](http://localhost:8888)

You should see the TodoMVC app up and running. We are now ready to run Cypress tests.

## to run cypress
```
npm run cypress:open
```