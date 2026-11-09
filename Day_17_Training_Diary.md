# Day 17 -- MongoDB Queries, Filtering and Data Manipulation

**Topic Covered:** MongoDB Query Operators, Filtering, Sorting,
Projection, Updating and Deleting Documents.

## Daily Training Diary

Today, I learned about querying and manipulating data in MongoDB. I
understood that database queries allow an application to retrieve
specific documents based on conditions instead of fetching every record
from a collection.

I studied how to apply **query filters** to retrieve documents that
match particular criteria. I learned about comparison operators such as:

-   `$eq`: Matches values equal to a specified value.
-   `$ne`: Matches values not equal to a specified value.
-   `$gt` and `$gte`: Match values greater than, or greater than or
    equal to, a specified value.
-   `$lt` and `$lte`: Match values less than, or less than or equal to,
    a specified value.
-   `$in`: Matches any value from a specified list.

I also learned about logical operators such as `$and`, `$or` and `$not`,
which help combine or modify query conditions.

Another topic covered today was **sorting and projection**. I learned
how the `sort()` method arranges query results in ascending or
descending order and how projection selects only the required fields
from documents. I also explored the use of `limit()` and `skip()` for
controlling the number of returned records and implementing basic
pagination.

I revised update and delete operations and learned how query conditions
can be used to modify or remove selected documents. I also discussed the
importance of creating suitable indexes to improve query performance
when working with frequently accessed fields.

## Practical Learning

I practiced writing MongoDB queries to retrieve documents based on
different conditions, sort results, select specific fields and update
records. I also experimented with limiting query results and combining
multiple filter conditions.

I related these concepts to the Banking Ledger Management System. For
example, account records can be filtered by account status, and
transaction records can be queried by account ID or transaction type.
Sorting can help display recent transactions first, while projection can
return only the fields required for a particular API response.

## Learning Outcomes

-   Learned how to filter MongoDB documents using query conditions.
-   Understood comparison and logical query operators.
-   Practiced sorting and selecting specific document fields.
-   Learned the purpose of `limit()` and `skip()` for result pagination.
-   Revised conditional update and delete operations.
-   Gained an understanding of indexes and query performance.
-   Understood how MongoDB queries support account and transaction
    retrieval in the Banking Ledger Management System.
