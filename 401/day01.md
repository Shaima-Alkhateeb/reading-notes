# Express

## What's the difference between PUT and PATCH?

PUT is a method of modifying resource where the client sends data that updates the entire resource . PATCH is a method of modifying resources where the client sends partial data that is to be updated without modifying the entire data.


## Provide links to 3 services or tools that allow you to "mock" an API for development like json-server

1. Nock
2. MockServer
3. Beeceptor

## Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?

### **Client error responses (400–499)**

- 400 Malformed parameters or other bad request.
- 401 Unauthorized
- 402 Payment Required
- 403 Forbidden
- 404 Not Found
- 405 Method Not Allowed

### **Server error responses (500–599)**

- 500 Internal Server Error
- 501 Not Implemented
- 502 Bad Gateway
- 503 Service Unavailable
- 504 Gateway Timeout
- 505 HTTP Version Not Supported

## Compare and contrast SOAP and ReST

| SOAP | ReST |
| ----------- | ----------- |
| Protocol | Architecture |
| Function driven | Data driven |
| Needs more bandwidth | Only needs minimum bandwidth |
| Cannot use REST | Can use SOAP |
| Only works in XML | Works in different data formats such as HTML, JSON, XML, and plain text |
| Supports HTTP and SMTP protocols | Only requires HTTP |
| Stricter rules to follow | Easier for developers to suggest recommendations |
| Requires advanced security, but can define it, too | Relies on undelerlying network which can be less secure |
