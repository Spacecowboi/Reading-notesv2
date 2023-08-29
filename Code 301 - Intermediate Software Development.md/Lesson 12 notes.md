# CRUD

### Status Codes Based on REST Methods

1. In your own words, describe what each group of status codes represents:

* 100's = "Hey look, we got your request! We'll try and get something going for ya just sit tight."
* 200's = "We got your request and everything seems good to go! Here's what you asked for, enjoy the rest of your day!"
* 300's = "Uh, well, we don't exactly know what or where your request is but we're still working on it. Please be patient."
* 400's = "WHADDAYA TALKING BOUT EH?! I AINT GOT A REQUEST!! MAYBE CHECK YA INPUT HUH?!"
* 500's = "This is entirely the server's fault."

2. What is a status code 202?

* This means that the request has been accepted for processing, but the processing hasn't been completed.

3. What is a status code 308?

* This is a "permanent" redirect. It means that the URL the client is trying to gain access to has been permanently moved to a new URL.

4. What code would you use if an update didn't return data to a client?

* Status code 204 - No Content

5. What code would you use if a resource used to exist but no longer does?

* This is 410, gone. I don't know where it's at.

6. What is the 'Forbidden' status code?

* 403 = F O R B I D D E N. 

### Build a REST API with Node.js, Express & MongoDB

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

* Storing it in .env makes it far more secure as .env is a hidden file.

2. What is middleware? 

* A type of software that provides services to software applications beyond those available from the operating system.

3. What does app.use(express.json()) do?

* It parses incoming JSON requests and makes the data available to whatever application requested it.

4. What does the /:id mean in a route?

* This is like a placeholder/dynamic paramter because it can change. 

5. What is the difference between PUT and PATCH?

* PUT is a method of modifying resources where the client sends data taht updates the entire resource. PATCH is a method of modifying resources where the client sends partial data that is to be updated without modifying the entire data.

6. How do you make a default value in a schema?

* You use the "default" keyword.

7. What does a 500 error status code mean?

* The server encountered an unexpected condition that prevented it from fulfilling the request.

8. What is the difference between a status code 200 and status 201?

* This means that the request was receieved, understood, processed. (200) The opposite (201), means the request was successful and a resource was created as a result.

