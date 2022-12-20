# Authentication

## Why this is important

Cyber crime is a major source of revenue for criminals and wrecks havoc on businesses and users.  Authorization and Authentication practices are in place to help prevent that havoc.

## O Auth

1.  Open-standard authorization: allows a single credential log in to access multiple servers and services without sharing the single credential 

2.  Logging into one website, then go to another website that authenticates the user then the previous site logs you on after using permission from the second site.

3.  > The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
    The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
    The first site gives this token and secret to the initiating user’s client software.
    The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
    If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
    The user approves (or their software silently approves) a particular transaction type at the first website.
    The user is given an approved access token (notice it’s no longer a request token).
    The user gives the approved access token to the first website.
    The first website gives the access token to the second website as proof of authentication on behalf of the user.
    The second website lets the first website access their site on behalf of the user.
    The user sees a successfully completed transaction occurring.
    OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons).  [How it works](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)
    
4.  OpenID is for authenticating a human to a machine, logging in.

## Authorization and authentication flows

1.  Authentication is verifying someone is who they say they are, log in credentials; authorization is being allowed to do things or access areas based on that.

2.  Authorization code flow is how code moves back and forth from user to app to authO to API

3.  The PKCE adds an extra layer of security by preventing an attacker from being able to exchange an authorization code for a token without a code verifier.

4.  A shortened authorization process that is used when an API with access tokens is not needed.

5.  Client credentials flow is used for machine to machine applications and authenticates and authorizes an app instead of a user.

6.  Device authorization is for a user to authorize a device; for input-constrained devices

7.  Resource owner password flow directly handles a user's password through the use of a form input.

## Things I want to know more about

This was a whole heck of a lot to take in.  

## References and links

[A&A flows](https://auth0.com/docs/get-started/authentication-and-authorization-flow)
