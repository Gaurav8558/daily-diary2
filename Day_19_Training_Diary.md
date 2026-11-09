# Day 19 -- Integrating MongoDB with Node.js and Express.js

**Topic Covered:** MongoDB Connectivity Using Mongoose, Database
Configuration, User Registration, Login and Account Management APIs.

## Daily Training Diary

Today, I learned how to integrate **MongoDB with a Node.js and
Express.js application** using Mongoose. I understood that a backend
application needs a database connection to store and retrieve
information required by its business logic.

I studied how to configure a MongoDB connection using Mongoose and how
to use `mongoose.connect()` with a connection string. I learned about
keeping database configuration separate from the main application code
so that the connection logic can be maintained independently.

I was introduced to the use of environment variables for storing
configuration values such as the MongoDB connection string. I understood
that sensitive configuration details should not be hard-coded into the
source code or committed to a public repository.

I also learned how controllers interact with Mongoose models to perform
database operations. I studied how an Express route receives a request,
passes it to a controller and how the controller validates the input,
communicates with the database and sends a response.

During the session, I explored the basic workflow of user registration
and login APIs. I understood how registration involves accepting user
details and creating a user record, while login involves retrieving the
user and verifying the supplied credentials. I was also introduced to
account management APIs for creating accounts, listing a user's accounts
and retrieving account information.

## Practical Learning

I practiced configuring a MongoDB connection in a Node.js application
and using Mongoose models to create and retrieve records. I also
explored how Express routes and controllers can be connected to database
operations.

I related these concepts to the Banking Ledger Management System. The
project connects to MongoDB through a separate database configuration
file and uses Mongoose models for users and accounts. Its authentication
routes handle registration and login, while account routes support
account creation, listing and balance retrieval for the authenticated
user.

## Learning Outcomes

-   Understood how to connect MongoDB with Node.js using Mongoose.
-   Learned to separate database configuration from application logic.
-   Understood the use of environment variables for configuration.
-   Learned how Express routes, controllers and models work together.
-   Gained an understanding of user registration and login workflows.
-   Learned the basic structure of account management APIs.
-   Understood how MongoDB integration supports the Banking Ledger
    Management System.
