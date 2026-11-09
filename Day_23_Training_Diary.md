# Day 23 -- Authorization Middleware and Token Blacklisting

**Topic Covered:** Authentication Middleware, Authorization, Role-Based
Access Control, System User Verification and JWT Token Blacklisting.

## Daily Training Diary

Today, I learned about the difference between **authentication and
authorization** in backend applications. I understood that
authentication verifies who a user is, while authorization determines
which resources or operations that authenticated user is allowed to
access.

I studied how authentication middleware works in Express.js. I learned
that middleware can extract a JWT from a request, verify its signature
and expiration, identify the associated user and attach the
authenticated user's information to the request object. If the token is
missing, invalid or expired, the middleware can reject the request
before it reaches the controller.

I also learned about **Role-Based Access Control (RBAC)**, in which
permissions are assigned according to a user's role or privileges. I
understood that protected operations should check the user's
authorization on the server rather than relying only on frontend
restrictions.

Another concept covered today was **JWT token blacklisting**. I learned
that a token may remain cryptographically valid until its expiration
time even after a user logs out. A blacklist provides a way to reject
tokens that have been explicitly revoked. I studied how a backend can
check whether a token exists in a blacklist before allowing access.

I was also introduced to the concept of a privileged system user. I
understood that certain administrative or system-level operations should
be accessible only to specially authorized identities and should have
separate authorization checks.

## Practical Learning

I explored how authentication middleware can protect account and
transaction routes in Express.js. I also studied how a separate
authorization middleware can verify whether a user has the required
system-user privilege.

I related these concepts to the Banking Ledger Management System. The
project uses authentication middleware to protect account and standard
transaction endpoints. It also uses a separate system-user middleware
for the initial-funds endpoint. During logout, the JWT is stored in a
blacklist collection, and authentication middleware checks the blacklist
when validating tokens. The blacklist records use a TTL index so that
expired revocation records can be removed automatically after the
configured period.

## Learning Outcomes

-   Understood the difference between authentication and authorization.
-   Learned how JWT authentication middleware protects Express routes.
-   Understood the principles of Role-Based Access Control.
-   Learned why privileged operations require separate authorization
    checks.
-   Understood the purpose of JWT token revocation and blacklisting.
-   Learned how a database-backed blacklist can reject revoked tokens.
-   Understood how system-user authorization is applied to initial
    funding in the Banking Ledger Management System.
