# Day 9 -- Node.js Modules, CommonJS and NPM

**Topic Covered:** Node.js Modules, Built-in and User-Defined Modules,
CommonJS, ES Modules, NPM and Package Management.

## Daily Training Diary

Today, I learned about the **module system in Node.js** and how it helps
organize an application into smaller, reusable and maintainable files. I
understood that modules allow developers to separate different
functionalities instead of writing the entire application in a single
file.

I studied the different types of Node.js modules:

1.  **Built-in Modules:** Modules provided by Node.js, such as `fs`,
    `path`, `http` and `os`, which can be used without installing
    additional packages.
2.  **User-Defined Modules:** Modules created by developers to organize
    application-specific functionality.
3.  **Third-Party Modules:** Packages developed by the community and
    installed through NPM.

I learned about the **CommonJS module system**, which is widely used in
Node.js applications. I practiced exporting functions and objects using
`module.exports` and importing them using `require()`. I was also
introduced to ES Modules, which use `export` and `import` statements.

Another important topic covered today was **NPM (Node Package
Manager)**. I learned how NPM is used to install, update and manage
project dependencies. I studied the purpose of `package.json`, which
contains project metadata, scripts and dependency information, and
`package-lock.json`, which records the resolved dependency versions to
support consistent installations.

I also practiced commonly used NPM commands, including `npm init`,
`npm install`, `npm uninstall` and `npm list`.

## Practical Learning

I created a basic Node.js project and initialized it using `npm init`. I
created separate JavaScript files, exported functions from one file and
imported them into another using the CommonJS syntax.

I also installed a package using NPM and observed how the dependency was
recorded in `package.json` and `package-lock.json`.

I related this learning to the Banking Ledger Management System. In the
project, separate modules can be created for authentication, account
management, transactions, database configuration and email services.
This modular structure makes the backend easier to develop, test and
maintain.

## Learning Outcomes

-   Understood the module system in Node.js.
-   Learned the difference between built-in, user-defined and
    third-party modules.
-   Practiced importing and exporting modules using CommonJS.
-   Gained an introduction to ES Modules.
-   Learned how to initialize a Node.js project using NPM.
-   Understood the purpose of `package.json` and `package-lock.json`.
-   Practiced installing and managing project dependencies.
-   Understood how modular development helps organize the Banking Ledger
    Management System.
