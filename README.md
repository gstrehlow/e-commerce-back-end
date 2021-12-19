# ORM Challenge: E-Commerce Back End

## Video Walkthrough 
- [Link to Video Walkthrough](https://watch.screencastify.com/v/y8cZj4VFIshikVhjoVNl)

## Installation
- Clone the repository
- Setup your .env file with the database name being 'ecommerce_db', and adding in your own login credentials for MySQL.
- Install dependencies using 'npm i sequelize, mysql2, and dotenv'

## Usage
- Log into your MySQL command line and run 'source db/schema.sql'
- In the root directory of the project, type 'npm run seed'
- To start the server, simply type 'npm start'

## User Story 
- As a manager at an internet retail company, I want a back end for my e-commerce website that uses the latest technologies, so that my company can compete with other e-commerce companies.

## Acceptance Criteria
- Given a functional Express.js API
- When I add my database name, MySQL username, and MySQL password to an environment variable file, then I am able to connect to a database using Sequelize.
- When I enter schema and seed commands, then a development database is created and is seeded with test data.
- When I enter the command to invoke the application, then my server is started and the Sequelize models are synced to the MySQL database.
- When I open API GET routes in Insomnia for categories, products, or tags, then the data for each of these routes is displayed in a formatted JSON.
- When I test API POST, PUT, and DELETE routes in Insomnia, then I am able to successfully create, update, and delete data in my database.