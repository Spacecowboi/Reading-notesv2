# OAuth, Authorization and Authentication Flows

### Oauth

1. What is OAuth?

* "OAuth allows websites and services to share assets among users. It is widely accepted, but be aware of its vulnerabilities."


2. Give an example of what using OAuth would look like

* "The simplest example of OAuth is when you go to log onto a website and it offers one or more opportunites to log on using another website's/service's logon. You then click on the button linked to the other website, the other website authenticates you, and the website you were originally connecting to logs you on itself afterward using permission gained from the second website."

3. How does OAuth work? What are the steps that it takes to authenticate the user?

* The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
* The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
* The first site gives this token and secret to the initiating user’s client software.
* The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
* If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
* The user approves (or their software silently approves) a particular transaction type at the first website.
* The user is given an approved access token (notice it’s no longer a request token).
* The user gives the approved access token to the first website.
* The first website gives the access token to the second website as proof of authentication on behalf of the user.
* The second website lets the first website access their site on behalf of the user.
* The user sees a successfully completed transaction occurring.

^ **Procured from the article*

4. What is OpenID?

* "OpenID is for humans logging into machines". It is purely about authentication, verification of information.


### Authorization and Authetnication Flows

1. What is the difference between authorization and authentication?

* Authentication is basically verifying someones identity. Authorization is verifying *permissions*.

2. What is Authorization Code Flow?

* A hell of a lot of information, so to keep it short and sweet - It is a protocol used server-side in some applications to get access tokens by getting an authorization code from an authorization server, which they trade for the token, giving the application the ability to interact with the resources that the user requested.

3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

* "The PKCE-ehnanced Authorization Code Flow introduces a secret created by the calling application that can be verified by the authorization server; this secret is called the Code Verifier. Additionally, the calling app creates a transform value of the Code Verifier called the Code Challenge and sends this value over HTTPS to retrieve an Authorization Code. This way, a malicious attacker can only intercept the Authorization Code, and they cannot exchange it for a token without the Code Verifier."

4. What is Implicit Flow with Form Post?

* It is an alternative to the Authorization Code Flow, intended for public clients, or applications which are unable to securely styore Client Secrets.

5. What is Client Credentials Flow?

* "The Client Credentials Flow involves an application exchanging its application credentials, such as client ID and client secrets, for an access token."

6. What is Device Authorization Flow?

* "Rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device. This avoids a poor user experience for devices that do not have an easy way to enter text information."

7. What is Resource Owner Password Flow?

* This flow requests that users provide credentials using an interactive form.