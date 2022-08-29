# Phonebook-app

## Tech stack

React 18.2.0</br>
Node 16.16.0</br>
Express 4.18.1

* It's recomended to use the same versions

## Up and Running

To get started, clone/fork or download as zip the repository.

### Command to download packages

  npm install

### Command to run the app

  npm start

### Folder Structure (Demo)

    ├── client                         
        ├── src                      # Contains all files used across the project  
            ├── api                      # All services that take care of the communication between the React application(frontend) and an API(backend)
            ├── components               # Collection of UI components
            ├── helpers                  # Contains helper functions
            ├── hooks                    # Contains custom hooks which are used in several components         
        ├── public                   # Contains all static files of the project
            ├── index.html               
            ├── manifest.json            
            ├── robots.txt               
        ├── README.md   
        ├── package.json
        ├── package.json.lock
    ├── server
        ├── index.js                 # Handles app start up 
        ├── controllers              # Contains functions that processes the requests
        ├── db                       # Function that initialize the server conection to the data base 
        ├── helper                   # Contains helper function to generate json web tokens
        ├── middlewares              # Contains all the middleware used in the project
        ├── models                   # All data models required for the application or database
        ├── routes                   # Contains all the routes of the application
        ├── README.md   
        ├── package.json
        ├── package.json.lock
    ├── .gitmodules                
    ├── package.json                
    ├── package-lock.json 
------

### Todo's List

[x] REST API creation, server/.

[x] API implementaion, client/src/api/.

[x] Add client side form validations frontend/src/helpers.

[x] Add server side form validations server/middlewares.

[ ] CI/CD integration.

[ ] Unit Tests.

[ ] Integration Tests.
