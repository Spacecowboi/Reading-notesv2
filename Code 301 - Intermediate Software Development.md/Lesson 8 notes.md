### API

1. What does REST stand for?

* "Representational State Transfer"

2. REST APIs are designed around a __

* "Resources, which are any kind of object, data, or service that can be accessed by the client."

3. What is an indentifier of a resource? Give an example.

* "A URI that uniquely identifies that resource." An example would be https://adventure-works.com/orders/1

4. What are the most common HTTP verbs?

* GET, POST, PUT, PATCH, DELETE

5. What should the URLs be based on?

*The URLS should be based on reference to what the application is designed around.

6. Give an example of a good URL

* https://www.example.com/products/electronics/computers

7. What does it mean to have a chatty web api?

* A client application taht sends multiple requests to find all of the data that is required. 

8. What status code does a successful GET request return?

* A representation of the resource at the specified URI. THe body of the response message contains the details of the requested resource.
* Returns HTTP status code 200 (ok)

9. What status code does an unsuccessful POST request return?

* Creates a new resource at the specified URI. The body of the request message provides the details of the new resource.
* Returns HTTP status code 201 (Created)

10. What status code does a successful PUT request return?

* This either creates or replaces the resource at the specified URI. The body of the request message specifies the resource to be created or updated.
* If the method creates a new resource, it returns 201 (Created) or if nothing was done: 204 (No content)

11. What status code does a successsful DELETE request return?

* If successful: 204 (No content) If not: 404 (Not Found)
* This removes the specified URI. 