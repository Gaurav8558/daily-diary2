# Day 21 -- Developing RESTful APIs Using Express.js and MongoDB

**Topic Covered:** REST API Implementation, Express Routes, Controllers,
Mongoose Models, Request Validation and API Testing.

## Daily Training Diary

Today, I learned how to develop RESTful APIs by integrating **Express.js
with MongoDB using Mongoose**. I understood how the concepts studied in
the previous sessions come together to build backend services that
receive client requests, execute application logic and interact with a
database.

I revised the role of routes, controllers and models in a backend
application. I learned that routes define the API endpoints, controllers
handle incoming requests and coordinate the required operations, and
Mongoose models provide an interface for interacting with MongoDB
collections.

I studied the process of developing an API step by step:

1.  Define an endpoint with the appropriate HTTP method and URL.
2.  Read the required information from route parameters, query
    parameters or the request body.
3.  Validate the incoming data and check required conditions.
4.  Perform the required operation through a Mongoose model.
5.  Return a suitable JSON response with an appropriate HTTP status
    code.
6.  Handle errors so that unsuccessful operations produce meaningful
    responses.

I also learned the importance of separating route definitions from
controller logic. This makes the code easier to understand, maintain and
extend as an application grows.

## Practical Learning

I practiced creating Express routes and connecting them to controller
functions that performed database operations using Mongoose. I worked
with examples of creating and retrieving records and reviewed how to
return JSON responses with appropriate status codes.

As part of the Banking Ledger Management System, I studied the
implementation of account-related APIs. The system provides an endpoint
to create a bank account, an endpoint to list accounts belonging to the
authenticated user and an endpoint to retrieve the balance of a selected
account.

I also reviewed how transaction-related endpoints are organized
separately from authentication and account routes. This helped me
understand how different modules can work together while keeping the
backend structure organized.

## Learning Outcomes

-   Understood how Express.js and MongoDB are integrated to develop REST
    APIs.
-   Learned the relationship between routes, controllers and Mongoose
    models.
-   Practiced handling request data and returning JSON responses.
-   Understood the importance of input validation and error handling.
-   Learned how to organize API endpoints into separate route groups.
-   Gained practical understanding of account management API
    development.
-   Understood how RESTful APIs support the Banking Ledger Management
    System.

## Week 3 Summary

During the third week, I learned database fundamentals, MongoDB
operations, Mongoose schema design, database connectivity and REST API
development. I also studied how these concepts are applied to user
management, account management and transaction-related functionality in
the Banking Ledger Management System.
