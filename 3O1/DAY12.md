# Class 12: CRUD

## [Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

1. In your own words, describe what each group of status code represents:

- 100’s = ( informational status codes) an initial part of the request was received and the client should continue.
- 200’s = (success codes) the request has been accepted, a new request has been created, or a certain problem was solved.
- 300’s = (redirection codes) the request had to be redirected
- 400’s = (client error codes) invalid requests from client to server
- 500’s = (server error codes) 

2. What is a status code 202?

Often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future. The response body should include an URL to the finished resource with some information about when it will be available, or an URL to some monitoring endpoint that tells the client when the resource is available.

3. What is a status code 308?

Permanent Redirect - This tells the client to use another URL to access the resource and not use the current URL anymore. It’s helpful when we have multiple endpoints for one resource, but don’t want to implement reading from all of them.

4. What code would you use if an update didn’t return data to a client?

204 No Content

5. What code would you use if a resource used to exist but no longer does?

410 Gone

6. What is the ‘Forbidden’ status code?

The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

## [Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

for more secure

2. What is middleware?

is software that provides common services and capabilities to applications outside of what's offered by the operating system

3. What does `app.use(express.json())` do?

`app.use()` allow us to use any middleware that we want which is essentially code that runs when server gets a request but before it gets passed to your routes, and `express.json()`lets our server accept JSON as a body

4. What does the /:id mean in a route?

means is a parameter that we can access by typing in request req.params.id, this will give us access to whatever the user passes after the first "/"

5. What is the difference between PUT and PATCH?

PATCH: when we went to update based on what the user passes to us.(update a specific information)

PUT: update all the information

6. How do you make a default value in a schema?

`default: [SOMETHING].now`

7. What does a 500 error status code mean?

is a generic error response. It means that the server encountered an unexpected condition that prevented it from fulfilling the request.

8. What is the difference between a status 200 and a status 201?

201 means successfuly creating an object (specific)

200 means everything was successful