# Authentication with Auth0

* What is OAuth?

an open-standard authorization protocol that allows unrelated servers to interact with one another without sharing credentials.

* Give an example of what using OAuth would look like.

your app's login button sends the user to the auth0 login site, the user inputs credentials that would allow access to your site then sends them back to your app.

* How does OAuth work? What are the steps that it takes to authenticate the user?

- your app connects to auth0 on behalf of the user.

- auth0 generates a one time token unique to the user.

- your app gives the token to the user's client software

- client's software presents the token to auth0

- the user gets an approved access token from auth0 and gives it to your app

- your app sends that access token to auth0

- auth0 lets your user access your app.

* What is Open ID?

it is another third-party authentication source.

* What is the difference between authorization and authentication?

Authentication is for machines to access a server, while authentication is the approval process.

* What is Authorization Code Flow?

the exchange of authorization for an access token.

* What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

similar but with extra security measures like sending a password in exchange for tokens.

* What is Implicit Flow with Form Post?

its used for public apps that cant store information securely.

* What is Client Credentials Flow?

Authorizing machine to machine interaction, authorizing the app instead of the user.

* What is Device Authorization Flow?

A link that takes the user from the site and sends them into an authentication site to authorize their device.

* What is Resource Owner Password Flow?

cridential creation like Username and Password in some kind of form.

[Back to Main Page](../README.md)