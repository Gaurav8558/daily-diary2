# Day 28 -- API Testing, Debugging and Final Project Review

**Topic Covered:** API Testing with Postman, Request and Response
Validation, Debugging, Error Handling, Documentation and Project Review.

## Daily Training Diary

Today was the final day of my four-week industrial training in Backend
Development using Node.js. I focused on reviewing the Banking Ledger
Management System, testing its APIs and understanding the importance of
debugging and documentation before completing a backend project.

I learned how **Postman** can be used to test REST APIs without
requiring a frontend application. I revised how to create requests using
HTTP methods such as GET and POST, configure request headers, provide
JSON request bodies, attach authentication tokens and inspect server
responses.

I also studied the importance of checking HTTP status codes and response
data. Successful requests should return an appropriate success status
and useful response, while invalid input, missing authentication,
unavailable resources and server errors should be handled clearly. I
understood that testing should cover both expected successful operations
and failure scenarios.

I revised common backend debugging practices, including reading terminal
error messages, checking request data, tracing the flow between routes
and controllers, inspecting database records and reviewing asynchronous
operations. I also learned that useful error handling should provide
understandable responses without exposing sensitive internal
information.

## Practical Learning

I reviewed and tested the main API groups of the Banking Ledger
Management System:

-   **Authentication APIs:** Registration, login and logout.
-   **Account APIs:** Account creation, account listing and balance
    retrieval.
-   **Transaction APIs:** Fund transfers and system-authorized initial
    funding.

For protected endpoints, I reviewed how to include the authentication
token in the request and verify that unauthenticated requests are
rejected. I also considered validation scenarios such as missing fields,
invalid account identifiers, incorrect credentials, insufficient balance
and repeated transaction requests.

During the final review, I revisited the project's use of Express,
MongoDB, Mongoose, JWT, Bcrypt, Nodemailer and ledger-based balance
calculation. I understood how transaction records and debit-credit
ledger entries support the tracking of banking operations.

I also recognized that API testing does not automatically prove that a
system is production-ready. Further work can include broader automated
tests, stronger input and ownership validation, improved transaction
cleanup, security configuration and deployment checks.

## Learning Outcomes

-   Learned to test REST APIs using Postman.
-   Practised configuring HTTP methods, headers, JSON bodies and
    authentication tokens.
-   Understood how to validate API responses and HTTP status codes.
-   Learned to investigate backend errors through logs and request-flow
    analysis.
-   Reviewed authentication, account and transaction endpoints.
-   Understood the importance of testing failure scenarios and duplicate
    requests.
-   Revised the complete architecture and technologies used in the
    Banking Ledger Management System.
-   Completed the four-week industrial training diary and consolidated
    my backend development knowledge.

## Overall Training Summary

During these four weeks, I progressed from JavaScript fundamentals to
Node.js backend development, Express routing and middleware, MongoDB and
Mongoose, REST API development, authentication and authorization,
ledger-based transaction processing, database transactions, email
integration and API testing.

The training helped me understand how individual backend concepts are
combined to build a structured application. Working with the Banking
Ledger Management System gave me practical exposure to backend
architecture, API workflows, database operations and the importance of
maintaining reliable financial records.
