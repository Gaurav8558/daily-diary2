# Day 25 -- MongoDB Transactions and Database Consistency

**Topic Covered:** MongoDB Sessions, Multi-Document Transactions,
Atomicity, Commit, Rollback and Transaction Consistency.

## Daily Training Diary

Today, I learned about **database transactions** and their importance in
applications that perform operations involving multiple database
records. I understood that a transaction groups related database
operations into a single logical unit so that the operations can be
committed together or rolled back if an error occurs.

I studied the concept of **ACID properties**, which describe important
characteristics of reliable database transactions:

1.  **Atomicity:** All operations in a transaction succeed together, or
    the transaction is rolled back.
2.  **Consistency:** A transaction should preserve the defined rules and
    constraints of the database.
3.  **Isolation:** Concurrent transactions should not interfere in ways
    that produce invalid results.
4.  **Durability:** Once a transaction is committed, its changes are
    persisted.

I learned how MongoDB supports multi-document transactions through
sessions. I studied how a session can be started, how a transaction is
begun within that session, and how database operations can be associated
with the session.

I also learned about the two important transaction outcomes:

-   **Commit:** Confirms the transaction and makes its changes
    permanent.
-   **Abort or Rollback:** Cancels the transaction so that its
    uncommitted changes are not applied.

I understood that transaction cleanup is also important. Applications
should handle errors, abort transactions when necessary and end sessions
after the operation has finished.

## Practical Learning

I reviewed how MongoDB sessions and transactions are used in the Banking
Ledger Management System. During a standard fund transfer, the backend
creates a transaction record, inserts a debit entry for the sender and a
credit entry for the receiver, updates the transaction status and
commits the database transaction.

I understood why these operations should be grouped together. If the
debit entry is created but the credit entry fails, committing only part
of the operation could result in an inconsistent ledger. A database
transaction helps ensure that the related changes are committed or
rolled back together.

I also learned that transaction support in MongoDB requires a deployment
configuration that supports multi-document transactions, such as a
replica set or a suitably configured sharded cluster.

## Learning Outcomes

-   Understood the purpose of database transactions.
-   Learned the ACID properties of reliable transactions.
-   Understood MongoDB sessions and multi-document transactions.
-   Learned how to commit or abort a transaction.
-   Understood the importance of error handling and session cleanup.
-   Learned how transactions help maintain consistency between debit and
    credit ledger entries.
-   Gained practical understanding of transaction processing in the
    Banking Ledger Management System.
