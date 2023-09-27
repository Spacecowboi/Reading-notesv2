# Intro to JWT

1. What is a JSON Web Token?

* "an open standard that defines a compact and self-contained way for securely trasmitting information between parteis as a JSON object."

2. When should we use JSON Web Tokens?

* Authorization (The most common scenario)
* Information Exchange 

3. Claims are expected in which structural component of a JWT?

* The payload

### Are JWTs Secure?

1. If I get a JWT and I can decode the payload, how can we call that secure?

* Because at the end of the day the payload is encrypted, no matter what, and only the receiver has the pass/key for the payload.

2. If sending a JWT, what must sender and receiver both know? Hint, it's appended in the signature.

* They both need to know the secret

3. Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

* Concatenated means to string together two or more types/bits of information. The secret can be sent and received securely via the secret that both the sender and receiver share, and the key that the receiver has.

### Videos

1. Why use JWT?

* They are a secure way to send information between two parties (encryption)

2. JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

* It's like a sealed briefcase with the locking mechanisms on the outside. Except you and the person you are giving the case to has the key so it is only able to open by them.

3. What are the three components (the structure) of a JWT signature?

* Header, Payload, Signature.