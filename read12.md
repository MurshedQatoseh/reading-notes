# Crud #

**One of the foremost vital perspectives in databases are Making information, Perusing information, Overhauling information and Erasing information which is CRUD.** **In your claim words, depict what each bunch of status code speaks to:**

**100's = The request is recieved and the rerver will try to complete the request.**

**200's = It means that the request is succesfully completed.**

**300's = It tells the client that the resource they are requesting isn’t available at the expected location anymore.**

**400's = Invalid requests**

**500's = Error from the server side.**

### What is a status code 202? ###
***The client is informed by this code that although the request was legitimate, processing will take some time to complete.***

### What is a status code 308? ###

**This instructs the client to stop using the current URL and instead use a different one to access the resource.**

### What code would you use if an update didn't return data to a client? ###

**204 or 404**

### What code would you use if a resource used to exist but no longer does? ###

**409**

### What is the 'Forbidden' status code?  ###

**4.3**

### Why do we need to pull our MongoDB database string out of our server and put it into our .env? ###

**To be concealed so that no one else uses it and to make changing the service's deployment path simple.**

### What is middleware? ###

***is software that stands in the way of an operating system and the programs that execute on it. Middleware essentially serves as a hidden translation layer that facilitates data management and communication for remote applications.***

### What does app.use(express.json()) do? ###

***It parses incoming JSON requests and puts the parsed data in req.***

### What does the /:id mean in a route?###

**it's a dynamic route, so req.params.id will be whatever comes after summary/ in that specific request.**

### What is the difference between PUT and PATCH? ###

**When a client uses the PUT method to alter a resource, the entire resource is updated. PATCH is a method of resource modification where the client transmits updated partial data without changing the complete data.**

### How do you make a default value in a schema? ###

**You can specify default values for specific pathways in your schemas. The default will take effect if you create a new document without specifying that path.**

### What does a 500 error status code mean? ###

**May be a nonexclusive mistake reaction. It implies that the server experienced an startling condition that avoided it from satisfying the request.**

### What is the difference between a status 200 and a status 201? ###

**The 200 status code is by far the most common returned. It means, simply, that the request was received and understood and is being processed. A 201 status code indicates that a request was successful and as a result, a resource has been created.**
