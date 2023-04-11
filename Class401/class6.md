#  Authentication

## Securing Passwords

* *Explain to a non-technical friend how you would safely hash and store a password.*
 
  * You know those old cereal box decrypter rings? When you create a password, that password is turned into a hash, which is basically those decrypter rings, but extremely complex.
* *What is Bcrypt?*

  * Bcrypt is a algorithm that has adaptive hash functionality, so its more resilient to things like brute force attacks.
* *Why might you use something like Bcrypt?*

  * Because simple hashing is pretty easy to brute force with todays hardware. 
## Basic Auth

* *What is Basic Authentication?*

  * It is a methor for an HTTP user agent that allows you to provide a username and password when making a request.
* *What properties are necessary in the header of a Basic Auth request?*

  * Cache Credentials
* *How are username:password in Basic Auth encoded?*

  * Base64
## OWASP auth cheatsheet

* *Define the authentication process to a non-technical recruiter.*

  * Its signing in with a user name and password.
* *How should your error messaging respond (both HTTP and HTML)? Why?*

  * I believe you want an HTML error code so that the user would know something was incorrect and an HTTP error to keep the error obsure from bots trying to brute force.
* *Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.*

  * Sure
