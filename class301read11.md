# What is OAuth #

## 1. What is OAuth? ##
it is an authentication protocol that allows you to approve one application interacting with another on your behalf without giving away your password.

## 2. Give an example of what using OAuth would look like.
when we go to a site and sees things like 'Log in with Facebook' or 'Log in using Google.' These let a user not have to make a new login for the site.

## 3. How does OAuth work? What are the steps that it takes to authenticate the user?
The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.

The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.

The first site gives this token and secret to the initiating user’s client software.

The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).

If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.

The user approves (or their software silently approves) a particular transaction type at the first website.

The user is given an approved access token (notice it’s no longer a request token).

The user gives the approved access token to the first website.


## 4. What is OpenID?
OpenID is about authentication, OpenID is for humans logging into machines.
Authorization and Authentication flows

# Authorization and Authentication flows #

## 1. What is the difference between authorization and authentication?
-  Authentication: determines if users are who they say, done before authorization, transmits info through an ID token, challenges the user to provide credentials
-  Authorization: determines what users can or cannot access, completed after the authentication, transmits through an access token, verifies if access is given through policies and rules

## 2. What is Authorization Code Flow?
Exchanges an Authorization Code for a token. The app has to be server side.

## 3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
The PKCE-enhanced Authorization Code Flow introduces a secret created by the calling application that can be verified by the authorization server; this secret is called the Code Verifier.

## 4. What is Implicit Flow with Form Post?
This is a more outdated version of OAuth's code flow which may work at the bare basic level, and will not provide additional security measures, which can be an issue in some cases 

## 5. What is Client Credentials Flow?
In the client credentials flow, permissions are granted directly to the application itself by an administrator. 
## 6. What is Device Authorization Flow?
Device authorization flow is used to provide a better experience for devices that don't have an easy way to enter text.
## 7. What is Resource Owner Password Flow?
requests that users provide credentials (username and password), typically using an interactive form.