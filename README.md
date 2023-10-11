# To-do-List-ReactJS-MySQL-Express.JS
This repository contains a simple To-Do List web application with both front-end and back-end components. The front-end is built using React, while the back-end is powered by Express.js and connects to a MySQL database. Here's a brief overview of the repository and how to set it up.

## Prerequisites

Before running this application, ensure you have the following installed:

- Node.js
- MySQL

## Installation

1. Clone this repository to your local machine:
```bash
git clone https://github.com/karan666/To-do-List-ReactJS-MySQL-NodeJS/tree/main.git
```
2. Navigate to project directory
```bash
cd To-do-List-ReactJS-MySQL-NodeJS
```
3. Install dependencies for the front-end (React) and back-end (Express) separately:

### Install front-end dependencies

```bash
cd FrontEnd
```

```bash
npm install
```
### Install back-end dependencies

```bash
cd BackEnd
```
```bash
npm install
```
   
4. Set up the MySQL database:

-Create a MySQL database named to_do_list.
-Modify the MySQL connection settings in server.js to match your MySQL server's credentials.

5. Start the back-end server:

```bash
cd BackEnd
```
```bash
node server.js
```
OR
```bash
nodeon server.js
```

6. Start the front-end application

```bash
cd FrontEnd
```

```bash
npm start
```

The application should now be running on http://localhost:3000, and you can access the To-Do List web app in your web browser.

## Front-end (ReactJS)

The front-end of the application is built using React. It allows you to add and delete To-Do items. The front-end communicates with the back-end API to retrieve and manipulate the data.

## Back-end (Express.JS)

The back-end of the application is powered by Express.js and connects to a MySQL database. It provides API endpoints for fetching, adding, and deleting To-Do items.

## Database (MySQL)

This application uses a MySQL database to store To-Do items. You need to set up the database and configure the connection details in server.js.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments

- The front-end of this project is built using React.

- The back-end is powered by Express.js.

- MySQL is used as the database system.

- CORS and body-parser middleware are used for handling cross-origin requests and parsing request bodies.

## Author

Karan Keshab Shrees
