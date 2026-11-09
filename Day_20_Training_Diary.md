# Day 20 -- REST API Architecture and Design Principles

**Topic Covered:** REST Architecture, RESTful API Principles, HTTP
Methods, Status Codes, Resource Naming and API Response Design.

## Daily Training Diary

Today, I learned about **REST (Representational State Transfer)** and
its role in designing web APIs. I understood that REST is an
architectural style for building services that allow clients and servers
to communicate through standard HTTP operations.

I studied the key principles commonly associated with RESTful API
design, including the client-server separation, stateless communication,
a consistent interface and the use of resources identified through URLs.
I understood that in a stateless API, each request should contain the
information required by the server to process it rather than relying on
stored client-session context.

I revised the commonly used HTTP methods and their purposes:

-   **GET:** Retrieves a resource or collection of resources.
-   **POST:** Creates a resource or performs an operation that is not
    simply a retrieval.
-   **PUT:** Replaces an existing resource.
-   **PATCH:** Applies a partial update to a resource.
-   **DELETE:** Removes a resource.

I also studied HTTP status codes and how they communicate the result of
an API request. I revised success codes such as `200 OK` and
`201 Created`, client-error codes such as `400 Bad Request`,
`401 Unauthorized`, `403 Forbidden` and `404 Not Found`, and the
server-error code `500 Internal Server Error`.

Another topic covered today was **API endpoint design**. I learned the
importance of using clear resource-based URLs, consistent naming
conventions, appropriate HTTP methods and predictable JSON response
structures. I also discussed how validation errors and operational
failures should be communicated through suitable status codes and error
messages.

## Practical Learning

I practiced planning REST API endpoints for common banking operations.
For example:

-   `POST /api/auth/register` -- Register a new user.
-   `POST /api/auth/login` -- Authenticate a user.
-   `POST /api/accounts` -- Create a bank account.
-   `GET /api/accounts` -- Retrieve the authenticated user's accounts.
-   `GET /api/accounts/balance/:accountId` -- Retrieve an account
    balance.
-   `POST /api/transactions` -- Initiate a fund transfer.

I also reviewed how the Banking Ledger Management System uses separate
route groups for authentication, accounts and transactions. This helped
me understand how REST principles can be applied to organize a backend
API.

## Learning Outcomes

-   Understood REST architecture and its purpose in backend development.
-   Learned the main principles of RESTful API design.
-   Revised HTTP methods and their appropriate use.
-   Understood HTTP status codes and response handling.
-   Learned resource-based endpoint naming and consistent API structure.
-   Practiced planning REST endpoints for banking operations.
-   Understood how REST API design organizes communication in the
    Banking Ledger Management System.
