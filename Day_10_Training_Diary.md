# Day 10 -- Node.js Core Modules

**Topic Covered:** File System (fs), Path, OS and Events Modules in
Node.js.

## Daily Training Diary

Today, I learned about the **core modules of Node.js**, which provide
built-in functionality for performing common system-level and
application tasks. I understood that these modules are included with
Node.js and can be imported directly without installing additional
packages.

I studied the following important core modules:

1.  **File System (`fs`) Module:** I learned how Node.js can interact
    with files and directories. I explored operations such as reading
    files, writing data, appending content and deleting files. I was
    introduced to both synchronous and asynchronous file system methods
    and understood why asynchronous methods are generally preferred in
    server applications.

2.  **Path (`path`) Module:** I learned how to work with file and
    directory paths in a platform-independent manner. I explored methods
    such as `path.join()`, `path.resolve()`, `path.basename()` and
    `path.extname()`.

3.  **Operating System (`os`) Module:** I studied how to retrieve
    information about the operating system and the computer environment.
    I explored methods such as `os.platform()`, `os.arch()`,
    `os.hostname()` and `os.freemem()`.

4.  **Events (`events`) Module:** I learned about event-driven
    programming in Node.js and how events can be emitted and handled
    using the `EventEmitter` class. I practiced using methods such as
    `on()` and `emit()` to register event listeners and trigger custom
    events.

I understood that these core modules help developers interact with the
system, manage files and organize event-driven application behavior.

## Practical Learning

I created small Node.js programs to read and write text files using the
File System module, construct file paths using the Path module and
retrieve system information using the OS module. I also implemented a
simple custom event using `EventEmitter`.

I related these concepts to the Banking Ledger Management System. For
example, the Path module can help manage file paths, while the Events
module can be used to understand event-driven application behavior. File
operations can also support tasks such as handling application-generated
reports or logs, although the project's main banking records are stored
in MongoDB.

## Learning Outcomes

-   Understood the purpose of Node.js core modules.
-   Learned basic file reading, writing and directory operations using
    `fs`.
-   Practiced handling file paths using the `path` module.
-   Learned how to retrieve system information using the `os` module.
-   Understood event-driven programming using `EventEmitter`.
-   Gained practical experience importing and using built-in Node.js
    modules.
-   Identified possible uses of these modules in backend application
    development.
