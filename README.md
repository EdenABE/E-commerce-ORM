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

## Technology used
```

VS code
mysql
node js

## Installation

```
npm i
```

## Usage

```
Open mysql on command line 'mysql -u root -p'
Enter your mysql password
Use the schema.sql file in the db folder to create your database using MySQL shell commands 'SOURCE db/schema.sql'
quit mysql
npm run seed
node server.js
```

## MOC

Here is the link to the application's backend videos:
GET and DELETE route:
https://drive.google.com/file/d/1SY7Gk2GwbvzFom_6NC_ZJ-6iz0SJnw50/view

POST and PUT route:
https://drive.google.com/file/d/1926fUa5IseEhylc-uDRztxusS8F9AkjO/view
