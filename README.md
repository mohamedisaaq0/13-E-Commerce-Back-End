# 13: E-Commerce Back-End

Homework which requires you to make a backend service for an e-commerce application. This app runs with MySQL and express js.

- First update the .env file with your db info

- Install the dependancies

```sh
npm install
```

- Seed the database with

```sh
npm run seed
```

- Start the Server with

```sh
npm run start
```

Technical challenges include:

- Running express servers
- ORM Sequelize for MySQL
- API Routing
- route error handling
- Relational Models
- Database Seeding

![“GET tags,” “GET Categories,” and “GET All Products.”.](./assets/demo-01.gif)

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia:

![“GET tag by id,” “GET Category by ID,” and “GET One Product.”](./assets/demo-02.gif)

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia:

![“DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](./assets/demo-03.gif)
