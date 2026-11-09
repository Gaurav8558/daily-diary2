# Day 26 -- Email Integration Using Nodemailer and Gmail OAuth2

**Topic Covered:** Email Notifications, Nodemailer, SMTP, Gmail OAuth2
Authentication and Email Service Integration.

## Daily Training Diary

Today, I learned how backend applications send automated emails and how
email notifications can improve communication with users. I studied
**Nodemailer**, a Node.js library used to send emails through an email
transport service.

I learned the basic parts of an email-sending process:

-   **Transport configuration:** Defines the service and authentication
    details used to send an email.
-   **Sender and recipient:** Identifies the email account sending the
    message and the intended recipient.
-   **Subject:** Describes the purpose of the email.
-   **Message content:** Contains the notification text or HTML.
-   **Send operation:** Uses Nodemailer's `sendMail()` method to submit
    the message.

I also studied SMTP, which is a commonly used protocol for sending
email. In addition, I learned the purpose of **OAuth 2.0**. Instead of
relying only on a regular account password, OAuth 2.0 allows an
application to obtain an access token after authorization. I explored
how Gmail OAuth2 credentials, such as a client ID, client secret,
refresh token and access token, can be used when configuring an email
transport.

I understood that credentials and tokens must be kept outside source
code and protected from unauthorized access. I also learned that email
delivery can fail because of authentication problems, network issues or
provider restrictions, so applications should handle sending errors
appropriately.

## Practical Learning

I reviewed the email service in the Banking Ledger Management System.
The project contains an `email.service.js` module that uses Nodemailer
and Gmail OAuth2 configuration to send emails.

I connected this learning to banking-related notifications. For example,
an application can send a confirmation email after user registration or
notify a user about an account-related event. Email functionality is
kept in a separate service so that controllers can call the service
without containing all the email transport configuration themselves.

I also learned to distinguish between successfully submitting an email
through Nodemailer and confirming that it has reached the recipient's
inbox. The email provider may still process, delay or reject a message
after submission.

## Learning Outcomes

-   Understood the role of email notifications in backend applications.
-   Learned the basic working of Nodemailer.
-   Understood SMTP and email transport configuration.
-   Learned the purpose of Gmail OAuth2 authentication.
-   Identified the credentials required for OAuth2-based email
    configuration.
-   Understood why sensitive email credentials and tokens must be
    protected.
-   Learned how a separate email service can be integrated into the
    Banking Ledger Management System.
