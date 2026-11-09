# Day 13 -- Express.js Routing and Request Handling

**Topic Covered:** Express.js Routing, Route Parameters, Query
Parameters, Request Objects and Response Handling.

## Daily Training Diary

Today, I learned about **routing in Express.js** and how it is used to
define the endpoints through which clients interact with a backend
application. I understood that a route specifies how the server responds
to a particular HTTP method and URL path.

I studied how to define routes using methods such as `app.get()`,
`app.post()`, `app.put()`, `app.patch()` and `app.delete()`. I learned
that these methods correspond to common HTTP operations and are used to
create REST API endpoints.

I also learned about different ways of passing information through URLs:

1.  **Route Parameters:** These are named values included as part of the
    URL path. For example, `/accounts/:accountId` can be used to
    identify a particular account. Express makes these values available
    through `req.params`.

2.  **Query Parameters:** These are key-value pairs included after a
    question mark in the URL. For example, `/transactions?type=credit`
    can be used to request transactions of a particular type. Express
    makes these values available through `req.query`.

3.  **Request Body:** This contains data sent by the client, generally
    in JSON format for POST or update requests. The parsed data can be
    accessed through `req.body` when the appropriate middleware is
    configured.

I also studied the request and response objects in Express.js. I learned
how to access request information and send responses using methods such
as `res.status()`, `res.json()` and `res.send()`.

## Practical Learning

I created different Express.js routes to handle GET and POST requests. I
practiced accessing route parameters, reading query parameters and
extracting JSON data from request bodies.

I related these concepts to the Banking Ledger Management System. For
example, a route such as `GET /api/accounts/balance/:accountId` can
retrieve the balance of a selected account. Query parameters can be used
to filter transaction records, while POST requests can accept the
details required to initiate a fund transfer.

## Learning Outcomes

-   Understood the purpose of routing in Express.js.
-   Learned to define routes for different HTTP methods.
-   Practiced accessing route parameters through `req.params`.
-   Learned to read query parameters through `req.query`.
-   Understood how to access JSON request data through `req.body`.
-   Practiced sending responses with status codes and JSON data.
-   Understood how API routes are structured in the Banking Ledger
    Management System.
