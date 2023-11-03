# API Integration

1. Explain the difference between a query string paramater and a path parameter
 
* A query string parameter is added to the end of a URL after a question mark and is used for providing additional information or options, while a path parameter is part of the URL's path and directly identifies specific elements in the URL's structure, typically representing resources or endpoints.

2. What would our API URL with a path id paramater be given the following information:

Domain: http://our-site.com
v3
model name: stuff
id: things

* http://our-site.com/v3/stuff/things

3. We have created a dynamic API with an "interface". Describe how that interface works to a non-technical friend.

* It's like ordering from Amazon. You are able to tell Amazon what you want, and it gets it for you, then sends it to you without you having to go to the store to get it yourself.

# Review Auth Server Build

1. Describe how you would use middleware to implement basic and bearer auth

* You build middleware functions. For basic auth the middleware checks the username/pass and if it's correct, gives access to the application. For bearer, it's validating a token from the request.

2. Describe the handshake necessary to implement OAuth

* The app get an access token from a service provider to access a users data (with their consent of course) without actually sharing the users info.

3. Describe how Role Based Access Control works to a non-technical friend

* Literally its like dungeons and dragons. Or an RPG. You need a tank, a healer, a ranged damage dealer, and a melee damage dealer. Each of them have their own roles to fulfill, just like RBAC.

