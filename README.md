# E-Commerce-Back-End

Link to watch demo, <a href="https://drive.google.com/file/d/1yjZTZ4-6diQDEhmVkK-KUv1uBrFJhXSP/view">here</a>

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

<h1>Technologies used<h1>
Javascript, Node.js, Express.js, Sequelize npm package, MySQL2 npm package & dotenv npm package.

<h1>Installation process<h1>
Git clone the code ''. Then install the dependecies, npm i. Then log into mysql and drop and create database using source schema.sql. then in the terminal run 'npm run seed'. then start the server, node server.js