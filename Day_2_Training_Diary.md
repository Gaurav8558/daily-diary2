# Day 2 -- Introduction to HTTP Protocol and Request-Response Cycle

**Topic Covered:** HTTP Protocol, HTTP Methods, Request-Response Cycle,
HTTP Status Codes and API Communication.

## Daily Training Diary

Today, I learned about the **HTTP (Hypertext Transfer Protocol)** and
its importance in communication between clients and backend servers. I
understood that HTTP is an application-layer protocol used by web
applications to exchange data between a client and a server.

I studied the **HTTP Request-Response Cycle**, which explains how a
client sends a request to a server and how the server processes that
request before returning a response.

I learned about the main components of an HTTP request:

1.  **Request Method:** Defines the type of operation the client wants
    to perform.
2.  **URL:** Specifies the resource or endpoint being accessed.
3.  **Headers:** Contain additional information such as content type and
    authentication tokens.
4.  **Request Body:** Contains data sent to the server, generally in
    JSON format for REST APIs.

I also studied the commonly used HTTP methods:

-   **GET:** Used to retrieve information from the server.
-   **POST:** Used to create new resources or submit data.
-   **PUT:** Used to update an existing resource.
-   **PATCH:** Used to partially update a resource.
-   **DELETE:** Used to remove a resource.

Furthermore, I learned about HTTP status codes and their categories:

-   **200 -- OK:** Request completed successfully.
-   **201 -- Created:** A new resource was created successfully.
-   **400 -- Bad Request:** The request contains invalid or incomplete
    data.
-   **401 -- Unauthorized:** Authentication is required or has failed.
-   **403 -- Forbidden:** The client does not have permission to access
    a resource.
-   **404 -- Not Found:** The requested resource does not exist.
-   **500 -- Internal Server Error:** An unexpected server-side error
    occurred.

## Practical Learning

I explored how HTTP methods and status codes would be used in the
Banking Ledger Management System. For example, a GET request would
retrieve account details, a POST request would initiate a fund transfer,
and appropriate status codes would communicate whether the operation was
successful or failed.

I also understood how APIs act as an interface between the frontend and
backend, allowing clients to interact with banking services without
directly accessing the database.

## Learning Outcomes

-   Understood the HTTP protocol and its role in backend development.
-   Learned the structure of HTTP requests and responses.
-   Studied commonly used HTTP methods and their purposes.
-   Understood different HTTP status codes and their meanings.
-   Learned how REST APIs facilitate communication between clients and
    servers.
