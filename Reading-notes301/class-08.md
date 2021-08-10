## 1. What does REST stand for?

 Representational State Transfer

## 2. REST APIs are designed around a ____.

resources, which are any kind of object, data, or service that can be accessed by the client.

## 3. What is an identifer of a resource? Give an example.

a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be:

**HTTP
https://adventure-works.com/orders/1**


## 4. What are the most common HTTP verbs?

the uniform interface includes using standard HTTP verbs to perform operations on resources. The most common operations are GET, POST, PUT, PATCH, and DELETE.


## 5. What should the URIs be based on?

A resource doesn't have to be based on a single physical data item. For example, an order resource might be implemented internally as several tables in a relational database, but presented to the client as a single entity.

## 6. Give an example of a good URI.

https://adventure-works.com/orders

## 7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

try to avoid "chatty" web APIs that expose a large number of small resources. Such an API may require a client application to send multiple requests to find all of the data that it requires , Its bad.

## 8. What status code does a successful GET request return?

 returns HTTP status code 200 
## 9. What status code does an unsuccessful GET request return?
return 404 (Not Found).

## 10.What status code does a successful POST request return?
it returns HTTP status code 201 (Created).

## 11. What status code does a successful DELETE request return?

 HTTP status code 204 (No Content)