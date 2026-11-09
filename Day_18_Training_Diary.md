# Day 18 -- Introduction to Mongoose, Schema Design and Models

**Topic Covered:** Mongoose ODM, Schema Definition, Models, Data Types,
Validation, References and Middleware Hooks.

## Daily Training Diary

Today, I learned about **Mongoose**, an Object Data Modeling (ODM)
library used to work with MongoDB from Node.js applications. I
understood that Mongoose provides a structured way to define data
models, validate documents and perform database operations using
JavaScript.

I studied the concept of a **Mongoose Schema**, which defines the
structure and rules for documents in a MongoDB collection. I learned how
to specify fields, data types, required values, default values,
enumerations and validation rules.

I explored common Mongoose schema types, including `String`, `Number`,
`Boolean`, `Date`, `ObjectId` and `Array`. I also learned how to use
schema options such as `required`, `default`, `min`, `max`, `enum`,
`unique` and `select`.

Next, I learned about **Mongoose Models**, which are created from
schemas and provide methods for creating, retrieving, updating and
deleting documents. I understood how models act as an interface between
application code and MongoDB collections.

I was also introduced to references between documents using `ObjectId`
and the `ref` option. I learned that references can represent
relationships between collections, such as linking an account to its
owner or a transaction to the related accounts. I also studied the
purpose of `populate()` for retrieving referenced documents.

Another topic covered today was Mongoose middleware, also known as
hooks. I learned that hooks can execute logic before or after certain
model operations, such as saving a document. I understood how validation
and pre-save hooks can be used to apply application rules before data is
stored.

## Practical Learning

I practiced defining a Mongoose schema, creating a model and performing
basic database operations through that model. I also explored how to
define required fields, default values, enumerated values and references
between documents.

I related these concepts to the Banking Ledger Management System. The
project uses separate Mongoose models for users, accounts, transactions,
ledger entries and blacklisted tokens. For example, an account stores a
reference to its user, while a ledger entry stores references to its
account and transaction.

I also understood how schema validation and model hooks help maintain
consistent data. In the project, a pre-save hook is used to hash a
modified user password before it is stored in the database.

## Learning Outcomes

-   Understood the purpose of Mongoose as an ODM for MongoDB.
-   Learned how to define schemas and create models.
-   Practiced using Mongoose data types and schema validation options.
-   Understood document references using ObjectId and `ref`.
-   Learned how `populate()` retrieves referenced documents.
-   Gained an introduction to Mongoose middleware and pre-save hooks.
-   Understood how Mongoose models organize user, account, transaction
    and ledger data in the Banking Ledger Management System.
