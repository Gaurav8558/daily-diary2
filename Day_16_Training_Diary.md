# Day 16 -- MongoDB Collections, Documents and CRUD Operations

**Topic Covered:** MongoDB Database Structure, Collections, Documents,
CRUD Operations and Database Connectivity.

## Daily Training Diary

Today, I learned about the basic structure of MongoDB and how data is
stored and managed in a NoSQL database. I revised the concepts of
databases, collections and documents and understood how they work
together to organize application data.

I learned that a **database** contains collections, while a
**collection** contains individual documents. Each document stores
information in a BSON format using field-value pairs. Unlike a
traditional relational table, documents in a collection can have
flexible structures, although applications commonly follow consistent
data models.

I studied the four basic **CRUD operations** used to manage database
records:

1.  **Create:** Used to insert new documents into a collection. I
    learned about methods such as `insertOne()` and `insertMany()`.
2.  **Read:** Used to retrieve documents from a collection. I practiced
    understanding methods such as `find()` and `findOne()`, along with
    basic filtering.
3.  **Update:** Used to modify existing documents. I learned about
    `updateOne()` and `updateMany()` and the use of update operators
    such as `$set`.
4.  **Delete:** Used to remove documents from a collection. I studied
    methods such as `deleteOne()` and `deleteMany()`.

I also learned about MongoDB query filters and how conditions can be
used to retrieve specific records. I was introduced to MongoDB database
connectivity and understood that a backend application needs a
connection to the database before it can perform data operations.

## Practical Learning

I practiced basic MongoDB operations by creating a sample database and
collection, inserting documents, retrieving records, updating field
values and deleting selected documents.

I related these operations to the Banking Ledger Management System. For
example, user registration requires creating a user record, account
listing requires reading account records, and account status management
may require updating an account document. I also understood that
transaction and ledger records need to be stored and retrieved carefully
to maintain an accurate transaction history.

## Learning Outcomes

-   Understood MongoDB databases, collections and documents.
-   Learned how MongoDB stores document-based data.
-   Practiced Create, Read, Update and Delete operations.
-   Learned basic query filtering and update operators.
-   Understood the importance of database connectivity in backend
    applications.
-   Identified how CRUD operations support user, account and transaction
    management in the Banking Ledger Management System.
