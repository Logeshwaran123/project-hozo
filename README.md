# HOZO APP - Project

This project a simple hotel food ordering application that can enable the customers to order and send reviews. Also, this application has the management part from the Admin side benefits like managing employees, foods, delivery persons and order history tracking.

## TOPICS COVERED

- **_Fundamentals of Back End Development_**

  Backend development is the building process of actual business logic of one's application, being out of scope from the user. Here in our application we are meant to use NODE JS with Express to build our server, MongoDB with Mongoose as our DB.

- **_Node JS App_**

  Node is basically a runtime environment that makes it possible to write JS code outside the web browser. It is completely runs on the basis event loop and made of callback functions. Such that it is working with the Google Chrome's V8 engine for running the scripts.

- **_Express Framework_**

  It is simply a framework, but it is more powerful on running the application in our application and does the same things to be done by NodeJS. Express is build with 100% of NodeJS, but it it makes the development process more easier and working with them made very simple.

- **_REST API with Express and MongoDB_**

  According to business daily,
  API stands for Application Programming Interface. These are intermediaries that allow two different applications to communicate with each other. They are considered to be the building blocks of application cohesivity.

  REST API - Representational State Transfer (REST) is an architectural style that defines a set of constraints to be used for creating web services. REST API is a way of accessing web services in a simple and flexible way without having any processing. The above definitions is from the geeks for geeks website.

- **_Mongoose and Advance Data Modelling_**
- **_Advance Modules [Email, Payments, Notifications]_**
- **_Deployment using Heroku and GitHub_**

## MODULES

Two major sub divisions of the App are given as follows,

- USER MODULE

  - Reviews [FOOD, HOTEL, DELIVERY PERSON]

  The user or the customer of the hotel must be able to be post their review every order. Review about the Food, Hotel and Delivery person let the users to share their suggestions or opinions to build a bridge between their customers and have many real-time possible data abstract from the customers.

  - Place Order

  To place order in the website, the following steps need to be done,
  Order initiation

  - Cancel Order **NOTE: This is a future enhancement.**
  - View Food
  - Order History
  - Profile Updation

  **NOTE**:

  1. Here in profile updations the Address of the user's delivery and communication address is crucial, because of this customers address must contain one delivery address on placing every order. Either in the registration of the User this field need to be updated or by the time of ordering food.
  1. Other Info's such as UserName, Bio and What is food to them? are important questions to be handled.

- ADMIN MODULE
  - Food
  - Employee
  - Delivery Person
  - Order Details

## PROCESS

The below process will be explained using the Flow-Chart diagram in [https://www.draw.io]

- User Registration / Sign Up
- Add or Update Food
- Employee Registration and Update employee details
- Placing Order
- Order History | Status
