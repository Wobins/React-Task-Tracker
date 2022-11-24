# React Task Tracker

Here is a to-do app project made with JavaScript and React.

# Features
- you can add a task with or without a reminder
- you can list your tasks
- you can delete your tasks


# How it works
The React client app communicates with a local API backed by a JSON file that we can decide to provision first or not.\
We use Cypress for testing.

# How To Start
To start the app you have follow the steps below:
- first, unzip the folder
- then, make sure you have node and npm installed in your machine
- after it, you must position in the unzip folder on your terminal
- run `npm install` to install all the dependencies
- start the server on port 5000 by running `npm run server` 
- open your browser to view the API at [http://localhost:5000/tasks](http://localhost:5000/tasks)
- launch the React app with `npm start` command and open [http://localhost:3000](http://localhost:3000)
- start testing with Cypress by running `npm run cypress:open`, if you have chrome it will be open by default but you can edit it at the line 24 of package.json file
- now you can visit all the tests in the cypress/e2e folder


# My Tests
- check-links.cy.js: to verify all links correctly works
- apitest.cy.js: to test the API
- ui-behavior.cy.js: to check if the UI responds when adding a task with exact styles
- 1-addtodo.cy.js: to add tasks with cypress commands
- 2-addtodo.cy.js: to add tasks using Page object modelling 
- deletetask.cy.js: to delete the last task listed
