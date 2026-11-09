# Day 22 -- Password Hashing and JWT Authentication

**Topic Covered:** Password Security, Bcrypt Hashing, Authentication
Workflow, JSON Web Tokens (JWT) and Token Verification.

## Daily Training Diary

Today, I learned about user authentication and the importance of
protecting sensitive information in backend applications. I understood
that authentication is the process of verifying a user's identity before
allowing access to protected services.

I studied **password hashing** and learned why passwords should not be
stored as plain text in a database. I was introduced to the Bcrypt
hashing algorithm and practiced understanding how it converts a password
into a one-way hash. I learned that Bcrypt uses a salt and a
configurable work factor to make password guessing more difficult.

I also studied how password verification works. Instead of decrypting a
stored password, the application compares the password entered during
login with the stored hash using a password comparison function.

Next, I learned about **JSON Web Tokens (JWT)**, which are commonly used
to represent authentication claims between a client and a server. I
studied the general structure of a JWT, which consists of a header,
payload and signature. I understood that the token can be signed using a
secret key and later verified by the backend.

I learned about the typical authentication workflow:

1.  A user submits registration details.
2.  The backend validates the information and securely hashes the
    password.
3.  The user record is stored in the database.
4.  During login, the backend verifies the supplied password against the
    stored hash.
5.  If the credentials are valid, the backend generates a JWT.
6.  The client sends the token with subsequent requests to access
    protected endpoints.
7.  The backend verifies the token before allowing access.

I also learned that JWT payloads are encoded rather than encrypted by
default, so sensitive information such as passwords must never be
included in them.

## Practical Learning

I practiced generating password hashes using Bcrypt and comparing
entered passwords with stored hashes. I also explored creating and
verifying JWTs using the `jsonwebtoken` package.

I related these concepts to the Banking Ledger Management System. Its
user model uses Bcrypt to hash modified passwords before saving them.
The authentication controller verifies credentials during login and
generates a JWT with a configured lifetime. The token can then be used
to authenticate requests to protected account and transaction routes.

## Learning Outcomes

-   Understood the difference between authentication and general access
    control.
-   Learned why passwords should be hashed instead of stored as plain
    text.
-   Practiced password hashing and comparison using Bcrypt.
-   Understood the structure and purpose of JSON Web Tokens.
-   Learned how to generate and verify JWTs.
-   Understood the registration and login authentication workflow.
-   Learned how JWT authentication protects banking account and
    transaction APIs.
