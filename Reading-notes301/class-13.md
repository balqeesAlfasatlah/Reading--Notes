## 1. In your own words, describe what each group of status code represents:

100’s = informational status codes
200’s = success codes
300’s = redirection codes
400’s = client error codes
500’s = server error codes

## 2. What is a status code 202?

Accepted - Often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future. The response body should include an URL to the finished resource with some information about when it will be available, or an URL to some monitoring endpoint that tells the client when the resource is available.


## 3. What is a status code 308?
See Other - Like the 202 code but using a Location header field in response to informing the client about the location of the created resource or an endpoint that lets the client check for the status of the creation process. Some clients follow the status codes of the Redirect-class automatically. This code is usually only used for POST requests.

## 4. What code would you use if an update didn’t return data to a client?
204 No Content

## 5. What code would you use if a resource used to exist but no longer does? 
405

## 6. What is the ‘Forbidden’ status code?
403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

## 7. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

cause when we working on the code  locally , we store the data as local environment variable and this add security

## 8. What is middleware?

is software that lies between an operating system and the applications running on it. Essentially functioning as hidden translation layer, middleware enables communication and data management for distributed applications.

## 9. What does app.use(express.json()) do?
this set up the server to accept JSOn

## 10. What does the /:id mean in a route?
whatever we passed after the first slash is and id
## 11 .What is the difference beween PUT and PATCH?
patch is only for update what the user pass(update whats given) , but put update all the info at once

## 12. How do you make a defalut value in a schema?
in curly brackets we add the information for specific kay and value pair in a schema.

## 13. What does a 500 error status code mean?

there has been an error on the server

## 14 .What is the difference between a status 200 and a status 201?
201 is successful created object and its more specific.
200 mean everything was successful
