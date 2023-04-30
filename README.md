# E-Commerce Back End

Back-end for an e-commerce website using Express.js API to use Sequelize to interact with a MySQL database.

## [Table of Contents](#table-of-contents)

- [Description](#description)
- [Final Result](#final-result)
- [Walkthrough Video](#walkthrough-video)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Tests](#tests)
- [Contact Me](#contact)

## [Description](#table-of-contents)

This database contains four Sequelize models: Category, Product, Tag, and ProductTag; these models have association methods to create a relationship between them.

The API routes in product-routes.js, tag-routes.js, and category-routes.js perform CRUD operations. To seed data to the database we run the `npm run seed` comamand . Finally, to sync Sequelize to the MySQL database on server start I added code to server.js.

`Technologies used:`

- JavaScript
- Node.js
- Express.js
- MySQL
- Sequelize
- Insomnia

## [Final Result](#table-of-contents)

![]()
![]()

## [Walkthrough Video](#table-of-contents)

[Link to walkthrough video]()

## [Installation](#table-of-contents)

Install the following packages and dependencies:

> Node.js

> MySQL

> Insomia or any other API development enviroment

Once you have Node.js and MySQL installed, you'll need to install the required dependencies for this app: Express.js sequelize, MySQL2

> package.json: npm init -y and npm i

## [Usage](#table-of-contents)

Add your MySQL username, password, and database name as environment variables. 

> DB_NAME='ecommerce_db'  
> DB_USER='your_username'  
> DB_PW='your_password'

Open MySQL shell and insert the commands: 

> source db/schema.sql
> use ecommerce_db

Exit MySQL shell and 
Start the app by running the following command in your terminal: 

> npm run seed
> node server.js

## [License](#table-of-contents)

Licenced under:

[MIT](https://choosealicense.com/licenses/MIT)

![badge](https://img.shields.io/badge/license-MIT-green>)

## [Tests](#table-of-contents)

To test this app, clone the repository, open the file in your source-code editor, complete the installation and usage running the code `node server.js`. This will start the server and sync the Sequelize models to the MySQL database. You can then use your API development environment (for example Insomnia) to test the API routes using different HTTP request methods like get, post, put and delete.

## [Contact Me](#table-of-contents)

- [GitHub](https://github.com/cdrcar)

- [Email: carmela881@outlook.com](mailto:carmela881@outlook.com)
