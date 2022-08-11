# Class 08: APIs

## (API Design Best Practices)

1. What does REST stand for?
--> Representational State Transfer
2. REST APIs are designed around a resources.
3. What is an identifier of a resource? Give an example.
--> A resource has an identifier, which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be:
`https://adventure-works.com/orders/1`
4. What are the most common HTTP verbs?
--> GET, POST, PUT, PATCH, and DELETE.
5. What should the URIs be based on?
--> Based on nouns (the resource) and not verbs (the operations on the resource).
6. Give an example of a good URI.
--> `https://adventure-works.com/orders`
7. What does it mean to have a ‘chatty’ web API?
--> Is this a good or a bad thing? any API that requires consumer to do more than a single call to perform a single, common operation.It's a bad thing.
8. What status code does a successful GET request return? (200)OK
9. What status code does an unsuccessful GET request return? (404)Not Found/(204)No Content
10. What status code does a successful POST request return? (201)Created/(200)OK
11. What status code does a successful DELETE request return? (204)No Content
