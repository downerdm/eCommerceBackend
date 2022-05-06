# E-Commerce Back End

## The Task

Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence, understanding the fundamental architecture of these platforms will benefit you as a full-stack web developer.

The task was to build the back end for an e-commerce site by modifying starter code. 

I used the [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect the Express.js API to a MySQL database and the [dotenv](https://www.npmjs.com/package/dotenv) package to use environment variables to store sensitive data.

I used the `schema.sql` file in the `db` folder to create my database with MySQL shell commands.  

Models (categories, products, and tags) were created per the specs given in the homework assignment.  The appropriate associations were defined within the models.

I filled out the unfinished routes in `product-routes.js`, `tag-routes.js`, and `category-routes.js` to perform create, read, update, and delete operations using my Sequelize models.

I seeded the database.

The database is started using the `node server.js` command.

The original User Story and Acceptance Criteria were as follows:

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

## Walkthrough Videos

## Screenshots

Insomnia - GET command

![A user searches the eCommerce DB for all categories.](./assets/images/Insomnia_GET.png)

Insomnia - POST command

![A user makes a new category in the eCommerce DB .](./assets/images/Insomnia_POST.png)

## GitHub Repository Link

<https://github.com/downerdm/eCommerceBackend>

