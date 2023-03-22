# API Design

**REST**

Acronym: *RE*presentational *S*tate *T*ransfer

API design should center around the resources in use by the company. Resources should be composed of things, not actions.  

Important Note: REST is often empoyed with HTTP, perhaps most often, but REST does not necessarily depend on HTTP. 

REST resources are denoted by identifiers.

Identifiers are constructed as URI's (Uniform Resource Identifier) for identification purposes.04

An example:

http://example-store.com/orders/3

Common HTTP verbs: 

- GET 
- POST
- PUT
- DELETE
- PATCH

URI's can be defined in multiple ways.

Leonard Richardson defined the Maturity Model for URI construction in context of web API's:

0. Define one URI, and all operations are POST requests to this URI.
1. Create separate URIs for individual resources.
2. Use HTTP methods to define operations on resources.
3. Use hypermedia (HATEOAS, described below).

from https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design#organize-the-api-design-around-resources

A "chatty" web API uses many web requests for small sized resources.  This imposes a load on the system, so it is better to design API's with fewer requests and medium sized resources.  Larger resources can also compromise performance.

GET successful status code is 200 
GET unsuccessful status codes are varied...
404 is 'cannot be found'
204 is 'no content'
etc.

POST successful status code is 201
DELETE successful status code is 204, since there is no content after execution.



