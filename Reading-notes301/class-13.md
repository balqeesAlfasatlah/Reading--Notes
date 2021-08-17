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


## 5. What is the ‘Forbidden’ status code?
403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

