# E-commerce Back End

## Description 

This project utilized initial code to develop a backend application for an e-commerce platform. The application employs a command-line interface (CLI) and object-relational mapping for diverse data manipulation, storage, and retrieval methods when utilizing HTTP methods with a RESTful API.

The schema.sql file in the db folder was executed in MySQL Workbench to generate the ecommerce_db and establish a connection with Insomnia Core via the command-line interface (CLI). Once the database is established, specific NPM packages are installed using npm i. The MySQL2 and Sequelize packages are employed to link an Express.js API to a MySQL database, leveraging the dotenv package to securely store environmental variables like username, password, and database name. The npm run seed command migrates the data to MYSQL, creating a table from the four objects located in the models folder: Product, Category, Tag, ProductTag.

After successfully installing Node.js packages and seeding the database without errors, execute NPM Start to initiate the server and connect to the local host http://localhost:3001/. Subsequently, an API GET request is executed for each route, displaying the results in JSON format. All API POST, PUT, and DELETE routes are tested in Insomnia Core, confirming the ability to create, update, and delete data in the database.

## Installation/Usage

From the terminal, run:

`npm init`

`npm install`

`npm run start`

## Link

The following video shows the application's GET, POST, PUT, and DELETE routes for `PRODUCTS`,`TAGS` & `CATEGORIES` tested with Insomnia:

https://watch.screencastify.com/v/FIvoZmaEJWC1yumuFhnt
 
 Github: <a href="https://github.com/ocarly/EcommBackEnd">ocarly</a>