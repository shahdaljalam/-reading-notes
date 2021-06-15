# Notes on API design best practices #

- What does REST stand for?
REST : Representational State Transfer - an architectural approach to designing web services, a style for building distributed systems based on hypermedia.

- REST APIs are designed around a __.
Resources, which are any kind of object, data, or service that can be accessed by the client.

- What is an identifer of a resource? Give an example.

An identifier of a resource is something extra built into a URI that gives extra information.

- What are the most common HTTP verbs?

1. GET

2. POST requests create resources.

3. PUT requests updates existing or creates resources.

4. PATCH partial updates to existing resources.

5. DELETE

- What should the URIs be based on?
- Give an example of a good URI.

: https://adventure-works.com/orders 

- What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

 the abundance of requests being sent through a small number of resources. bad

- What status code does a successful 'GET' request return?

Status code 200 (OK)


- What status code does an unsuccessful 'GET' request return?

Status code 404 (not found)


- What status code does a successful 'POST' request return?

Status code 201 (created)


- What status code does a successful 'DELETE' request return?
Status code 404 (indicating that a process has been successfully handled)