# Node Exercise Repo

## Getting Started

This project is configured with babel so that you can use ES6 Module syntax. It's also bootstrapped for you with extra basic development tools so to get started, be sure to install all dependencies with `npm install`.

## Running the Development Server

To run the development server, use `npm run dev`.

This will re-transpile and restart the server with babel and nodemon.

## Running the Server

To run the server outside of development, use `npm start`.

This will transpile the server code with babel and start the server with node.

## Project Structure

This project is bootstrapped with files to get started, files for configuration and files for mock database queries. You will only be working in `server.js`, `routes/`, and `config/`.

```txt
config/
    index.js
mockdb/
routes/
    index.js
.babelrc
.env.template
.gitignore
package-lock.json
server.js
```

## Config

The `config/` folder is used to load and export node environment variables. Currently, it uses the `dotenv` package to load the environment variables when you start the server process, and exports them under `mysql` and `port`.

`port` will be used to set the express server to listen on the specified port number.

`mysql` will be used later to set up a connection to a MySQL database.

### .env File

There is a `.env.template` file in the root directory. You will need to create a local `.env` file and copy the contents of the `.env.template` file in to `.env`. Be sure to change the `PORT` value to `PORT=5000`. The `DB_` values will be changed in a later lesson.

## MockDB

The `mockdb/` folder contains a mock service for interacting with user data.

- The `getAll` method returns the data list
- The `getOne` method takes in an user object id parameter and returns a single user data object
- The `add` method takes in an user object parameter and adds it to the data list
- The `update` method takes in an user id and object as parameters and updates one user object in the data list
- The `delete` method takes in an user id parameter and removes one user object the data list
# expressRouting
