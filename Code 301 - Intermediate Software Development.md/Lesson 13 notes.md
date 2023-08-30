# CRUD

### The Basics

1. Which HTTP method would you use to update a record through an API?

* PUT

2. Which REST methods require an ID parameter?

* Both Update (PUT) and DELETE.

### Speed Coding

1. What's the relationship between REST and CRUD?

* REST and CRUD are both used in API design. The relationship is that the HTTP methods that we use in REST affect the CRUD operations.

2. If you had to describe the process of creating a RESTful API in 5 steps, what would they be?

* Identify your libraries and resources. Resources in this instance are things like users, etc.
* Once we've defined the resource, we have to define the end-points. So where are we getting every instance of each resource is the next question that gets answered.
* Third is defining what methods get used to get those resources. SO GET,POST, etc, in relation to each endpoint.
* Then we have to write all of the code that is going to handle the requests. So parsing data, JSON-ifying things, etc.
* Last is testing the API with a REST client like Thunder Client.