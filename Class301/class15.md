## * Authentication*

### What is OAuth?

* *What is OAuth?*

OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.


* *Give an example of what using OAuth would look like.*

When you click sign in on a website and you are able to sign in using google

* *How does OAuth work? What are the steps that it takes to authenticate the user?*

So the site that you are using to sign in with, ie google, would sign into whavever website on your behalf. It creates a sercret key then passes it threw the user. The site you are signing in verifies that the token you have and the token google gave them matches. Then it does a threeway handshake and everything is good to go.

* *What is OpenID?*

Its similar to OAuth, but is about authentication versus authorization. 

### Authorization and Authentication flows

* *What is the difference between authorization and authentication?*

Authentication verifies the identity of a user or service, and authorization determines their access rights.

* *What is Authorization Code Flow?*

It is the flow that authorization takes from when a user submits the request. 


* *What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?*

Its aurhorization code flow but ading code request and code challenge. 

* *What is Implicit Flow with Form Post?*

It seems like it takes a lot of steps out of the authorization process.

* *What is Client Credentials Flow?*

This is like blizzards authentication. The user enters a username and password, then the server generates and sends a key and the user enters the key.

* *What is Device Authorization Flow?*

I think this is how you sign into netflix on your new roku. You are are signed into your account and the connect device via link.

* *What is Resource Owner Password Flow?*

That seems like Client credentials, but with slightly different steps. 
