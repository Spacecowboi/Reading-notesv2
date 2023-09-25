# Securing Passwords

1. Explain to a non-technical friend how you would safely hash and store a password

* Imagine you have a really long, obnoxious password that you made for your Google account. Now, maybe you want to add another "layer" of complexity to this password, how would you do that? Hashing. Hashing is basically turning that password you originally made into a mixed up, scrambled-eggs version of itself. 

2. What is Bcrypt?

* According to the article, Bcrypt is an adaptive hash function based on the Blowfish symmetric block cipher cryptographic algorithim and introduces a work factor (also known as a security factor), which allows you to determine how expensive the hash function will be.

3. Why might you use something like Bcrypt?

* As an extended measure of security. Bcrypt would be adding another "layer" or shell to your exiting hashed password, making brute force attacks much slower and difficult to succeed, if at all.

## Basic Auth

1. What is Basic Authentication?

* "A method for an HTTP user agent (web browser) to provide a username and password when making a request"

2. What properties are necessary in the header of a Basic Auth request?

* Typically an Authorization: Basic <credentials>, where credentials is the Base64 encoding of ID and password joined by a single colon :

3. How are username:password in Basic Auth encoded?

* They are both encoded using Base64

## OWASP auth cheatsheet

1. Define the authentication process to a non-technical recruiter.

* Authentication is basically a verification process. If you're at the airport, you have to show your ID to the TSA agents before you are allowed through security to arrive at your gate. Authentication works the same way with a users credentials.

2. How should your error messaging respond (both HTTP and HTML)? Why?

* For HTTP: Errors messages should be sending out 200-400 codes with different statuses, HTML error messages should be the messages that are displayed to the user. These can be custom messages or more generic messages.
