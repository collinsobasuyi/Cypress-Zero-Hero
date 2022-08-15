# -Cypress-Zero-Hero
## Cypress test for learning purposes - Quick and easy Web UI Automation from scratch with Cypress 5 - a modern JavaScript-based framework

npx cypress run --record --key ae9d6759-838e-4c3a-9e3d-905f2ca842c1

### asynchronous programming provides opportunities for a program to continue running other code while waiting for a long-running task to complete.

# Environment set up
1. Install chrome browser
2. install node.js
3. install git
4. install IDE (Visual studio code)

# Setup and start project
1. git clone https://github.com/Postavshik/ngx-cypress-test
2. npm install
3. npm start
4. open http://localhost:4200

# Cypress installation
1. npm init
2. npm install cypress --save-dev
3. npx cypress open

# Documents
1. Cypress configuration https://docs.cypress.io/guides/references/configuration.html#Options

# open cypress.json, edit and save
1. add "baseUrl" : "http://localhost:4200" as our base url
2. add "ignoreTestFiles": "**/examples/*" to ignore example files
3. add "viewportHeight": 768, "viewportWidth": 1024 for browser screen resolution