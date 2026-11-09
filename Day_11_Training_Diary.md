# Day 11 -- Creating HTTP Servers Using Node.js

**Topic Covered:** HTTP Module, Server Creation, Request and Response
Objects, URL Handling and Request Processing.

## Daily Training Diary

Today, I learned how to create an HTTP server using the built-in `http`
module in Node.js. I understood that an HTTP server listens for incoming
client requests, processes them and sends appropriate responses back to
the client.

I studied how to import the HTTP module and use the
`http.createServer()` method to create a server. I learned that this
method accepts a callback function that receives two important objects:

1.  **Request (`req`) Object:** Contains information about the incoming
    request, such as the HTTP method, URL, headers and other request
    details.
2.  **Response (`res`) Object:** Provides methods and properties to
    construct and send a response to the client, including the response
    status code, headers and response body.

I also learned how to use `server.listen()` to start the server on a
specific port and how to handle different HTTP methods and URL paths
using conditional statements.

Another concept covered today was setting response headers and status
codes. I practiced returning plain-text and JSON responses and
understood how the server can provide different responses depending on
the client's request.

I also explored basic URL handling and learned how to identify the
requested route and query parameters.

## Practical Learning

I created a basic HTTP server using Node.js that listened on a local
port and returned different responses for different URL paths. I tested
the server by accessing it through a browser and sending HTTP requests.

I related this practical exercise to the Banking Ledger Management
System. For example, the server would receive requests for user
authentication, account creation, balance retrieval and fund transfers.
It would process these requests and return appropriate responses to the
client.

I also understood that the built-in HTTP module provides the foundation
for server communication, while Express.js simplifies routing,
middleware handling and API development.

## Learning Outcomes

-   Learned how to create an HTTP server using Node.js.
-   Understood the purpose of the `http` module and
    `http.createServer()`.
-   Learned about request and response objects.
-   Practiced handling HTTP methods and URL paths.
-   Understood how to set response headers and status codes.
-   Learned how to start a server using `server.listen()`.
-   Gained an understanding of how HTTP servers form the foundation of
    backend APIs.
