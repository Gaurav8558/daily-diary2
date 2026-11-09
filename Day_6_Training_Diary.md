# Day 6 -- Asynchronous JavaScript and Event Loop

**Topic Covered:** Synchronous and Asynchronous JavaScript, Callbacks,
Promises, Async/Await and Event Loop.

## Daily Training Diary

Today, I learned about asynchronous JavaScript and its importance in
backend development. I understood the difference between synchronous and
asynchronous execution. In synchronous execution, statements are
processed one after another, whereas asynchronous operations allow the
program to continue executing other tasks while waiting for operations
such as database queries, file access or network requests to complete.

I studied **callbacks**, which are functions passed as arguments to
other functions and executed after a particular operation is completed.
I also learned about the limitations of deeply nested callbacks,
commonly known as callback hell, which can make code difficult to read
and maintain.

Next, I studied **Promises**, which represent the eventual completion or
failure of an asynchronous operation. I learned about the three Promise
states: pending, fulfilled and rejected. I practiced using `.then()`,
`.catch()` and `.finally()` to handle Promise results and errors.

I also learned about **async and await**, which provide a cleaner way to
write asynchronous code. An `async` function returns a Promise, while
the `await` keyword pauses execution within that function until a
Promise settles. I practiced using `try...catch` blocks to handle errors
in asynchronous operations.

Finally, I studied the **JavaScript Event Loop** and its role in
coordinating the call stack, task queues and asynchronous callbacks. I
understood at a basic level how Node.js can handle non-blocking
operations without waiting for every task to finish sequentially.

## Practical Learning

I practiced creating asynchronous functions, handling Promise results
and managing errors using `async/await` and `try...catch`.

I related these concepts to the Banking Ledger Management System.
Operations such as connecting to MongoDB, retrieving account details,
saving transactions and sending email notifications involve asynchronous
processing. Using `async/await` helps write these operations in a
readable manner while handling possible failures appropriately.

## Learning Outcomes

-   Understood synchronous and asynchronous JavaScript execution.
-   Learned the use of callbacks and the limitations of callback
    nesting.
-   Understood Promise states and Promise handling methods.
-   Practiced writing asynchronous functions using `async/await`.
-   Learned to handle asynchronous errors using `try...catch`.
-   Gained an understanding of the Node.js Event Loop and non-blocking
    operations.
-   Understood why asynchronous programming is important for database
    and API operations.
