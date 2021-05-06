# Image Repository

This image repository is created using the MERN stack for Shopify's Fall 2021 Developer challenge.

## Prerequisite 
This application uses MongoDB Atlas, a free cloud database service. Make sure you have an account and a database setup. Complete the first four steps:
[MongoDB Atlas Setup](https://docs.atlas.mongodb.com/getting-started/)

## Installation
Git clone the repository and cd into the client directory and run:

```bash
npm install
```
Do the same thing for the server directory. This will install the node modules needed for the front end and back end in their respective folders.

## Database Configuration
The project uses the Node.js driver to connect to the database. Head into the server/index.js file and change the connection URL variable. The beginning of the string should look like this:

```bash
mongodb+srv://<username>:<password>@cluster0...
```
Look for connect --> connect your application:
![MongoDB UI](/client/src/images/mongodb.png?raw=true "Title")

## Running the App
To start the front end cd into the client directory and run
```bash
npm start
```
To start the backend (from a new terminal) cd into the server directory and run
```bash
npm start
```