# Day 14 -- Middleware in Express.js

**Topic Covered:** Middleware Concept, Built-in Middleware, Custom
Middleware, Request Processing and Error Handling.

## Daily Training Diary

Today, I learned about **middleware in Express.js** and its role in
processing HTTP requests before they reach the final route handler. I
understood that middleware functions have access to the request object
(`req`), response object (`res`) and the `next()` function, which passes
control to the next middleware or route handler.

I studied how middleware can be used for tasks such as parsing request
bodies, logging requests, checking authentication, validating input and
handling errors. I also learned that middleware functions execute in the
order in which they are registered, so their placement in an Express
application is important.

I explored the different types of middleware:

1.  **Application-level Middleware:** Middleware registered on an
    Express application using `app.use()` or an HTTP method.
2.  **Router-level Middleware:** Middleware applied to a specific
    Express router using `router.use()`.
3.  **Built-in Middleware:** Middleware provided by Express, such as
    `express.json()` and `express.urlencoded()`.
4.  **Third-party Middleware:** External packages that provide
    additional functionality, such as `cors` and `cookie-parser`.
5.  **Error-handling Middleware:** Middleware designed to handle errors
    and send appropriate error responses. It uses four parameters:
    `(err, req, res, next)`.

I also learned how custom middleware can be created to perform specific
checks before allowing a request to continue. I understood the
importance of calling `next()` when a middleware function has completed
its work and needs to pass control forward.

## Practical Learning

I created a custom middleware function to log incoming request methods
and URLs. I also practiced applying middleware to routes and using
built-in JSON parsing middleware to process incoming request data.

I explored how middleware can be used in the Banking Ledger Management
System. For example, authentication middleware can verify a user's JWT
before allowing access to account and transaction routes. A separate
authorization middleware can check whether a user has the required
system-user privileges before accessing the initial-funds endpoint.

## Learning Outcomes

-   Understood the concept and working of middleware in Express.js.
-   Learned the different types of Express middleware.
-   Practiced using built-in and third-party middleware.
-   Learned to create custom middleware functions.
-   Understood the role of the `next()` function in request processing.
-   Gained an understanding of Express error-handling middleware.
-   Understood how authentication and authorization middleware protect
    banking API routes.
