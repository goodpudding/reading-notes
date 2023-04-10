# Bearer Authorization

## Intro to JWT

* *What is a JSON Web Token (JWT)?*

  * They I'm thinking of it is like the ORCA card to get on the light rail. I want to use that special way of verifying that I'm allowed to ride the train before I get on.
* *When should we use JSON Web Tokens?*

  *Any time you need to Authorize or when exchanging information.

* *Claims are expected in which structural component of a JWT?*

  * Its expected in the payload

## Are JWTs Secure?

* *If I get a JWT and I can decode the payload, how can we call that secure?*

  *Decoding isn't the same as decrypting.
* *If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.*

  * The secret
* *Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.*

  * If you are trying to send a secret message, then you want to send the message and the secret together, because the computer will scramble them together in a special way and the only way to decode it is to knoww what that secret was.

## JWTs Explained

* *Why use JWT?*

  * They are stateless, secure and can be used cross-platform.
* *JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.*

  * Back to the ORCA card analogy, its like using your card vs carrying a big jar of pennies in to pay for you ticket.
* *What are the three components (the structure) of a JWT signature?*

  * Encoded header, encoded payload and the keys that it needs.
