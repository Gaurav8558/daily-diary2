# Day 12 -- Introduction to Express.js and Server Configuration

**Topic Covered:** Express.js Introduction, Installation, Project Setup,
Application Configuration and Server Creation.

## Daily Training Diary

Today, I learned about **Express.js**, a lightweight and flexible web
application framework built on top of Node.js. I understood that
Express.js simplifies backend development by providing features for
routing, middleware integration, request handling and response
management.

I studied the advantages of using Express.js instead of handling every
request manually through Node.js's built-in HTTP module. I learned that
Express provides a simpler way to define API endpoints and organize
server-side application logic.

I was introduced to the process of setting up an Express.js project. I
learned how to initialize a Node.js project using NPM, install Express
using `npm install express` and import the framework into a JavaScript
file using the CommonJS `require()` syntax.

I also learned how to create an Express application using `express()`,
configure the server and start listening for incoming requests using
`app.listen()`. I explored the use of `express.json()` middleware to
parse incoming JSON request bodies and understood why request parsing is
important when building REST APIs.

Furthermore, I learned how to configure basic server settings, define a
simple route and send responses using methods such as `res.send()` and
`res.json()`.

## Practical Learning

I created a new Node.js project, initialized it with NPM and installed
Express.js. I configured a basic Express server and created a simple
test endpoint that returned a response when accessed through a browser
or an API client.

I also practiced enabling JSON request parsing and understood how
Express.js receives and processes client requests.

I related this setup to the Banking Ledger Management System. Express.js
would serve as the main backend framework for exposing authentication,
account and transaction APIs. The application configuration would also
provide a place to configure middleware and mount different route
groups.

## Learning Outcomes

-   Understood the purpose and advantages of Express.js.
-   Learned how to initialize a Node.js project and install Express.
-   Practiced creating an Express application using `express()`.
-   Learned how to configure and start a server using `app.listen()`.
-   Understood JSON request parsing using `express.json()`.
-   Practiced defining a basic route and sending HTTP responses.
-   Understood the role of Express.js in developing the Banking Ledger
    Management System.
