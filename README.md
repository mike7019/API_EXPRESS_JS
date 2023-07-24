# CRUD users
This is an API built using ExpressJS. This document will guide you through the steps required to install and run the API on your local machine.

# Prerequisites
Ensure you have the following installed on your system:

Node.js >=14.x
Npm >=6.x (comes with Node.js)

# Installation
Clone the repository:

git clone https://ProductoAutomatizacion@dev.azure.com/ProductoAutomatizacion/Arquitectura/_git/API_ExpressJS

sometimes will ask for an authentication. you will cancel the first auth window, then close the second auth window and on the Git Bash will request a password. heres the password

m7kg5bv2pvaqbbaw6ejzgy7a6s5nxinxskqv35tmmbtb7fvd4arq

it has to be copied and pasted with right click over Git Bash, it wont display the password but will be there and just hit enter and will clone the project.

# Change into the project directory using Git Bash console:

cd project-name

once in the main folder with the project, on a Git Bash console will execute the following commands

# Install the project dependencies:

npm install

# Install nodemon as a dev dependency:

npm install --save-dev nodemon

nodemon is a tool that helps develop Node.js based applications by automatically restarting the node application when file changes in the directory are detected.

# Configuration

Open the package.json file and modify the "scripts" section to include nodemon for development purpose:

"scripts": {
  "start": "node app.js",
  "dev": "nodemon app.js"
}

In this configuration, npm start will run the application with node, while npm run dev will run the application with nodemon, enabling automatic restarts when your code changes.

# Running the application
To start the application in development mode, use the following command:

npm run dev

To start the application in production mode, use the following command:

npm start

# Testing

once the server is running, you will look on any web browser the following path

http://127.0.0.1:4001/api/

the port 4001 might change depends on the server default setup.

it will display the API documentation with the Swagger GUI and will be easy to test the API there, also you may use POSTMAN to confirm and to test this API using the SerenityREST automation provided previously

# Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

# License
Choucair Cardenas Testing.