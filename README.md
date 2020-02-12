# Go_Project_FrontDB
Front-end of the project

## Content of the repository
1. projectVolume/app.js is the starting point of the server.
2. projectVolume/index.html is the content of our web interface.
3. resources/css/ contains the minified version of bootstrap css.

## Process
This repo gives an easy to deploy web interface in order to navigate and exploit the data retrieved by the Go code. The interface will connect to our MongoDB in order to retrieve all the data needed, being:
1. Check, from an Eth_Address, if a person exist in our table Identity.
2. If existing, retrieve all the personal data of the person and display it.
3. And, still if existing, retrieve all the relations and their associated weight, then display it as a list.
