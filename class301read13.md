# CRUD

## 1. In your own words, describe what each group of status code represents:
100’s =  Informational status.
200’s =   Success, request received.
300’s = Redirection - Requested resource isn't at the location anymore.
400’s = Client error - Client information/input is invalid.
500’s = Server error - Commonly referring to overloaded and/or servers not reachable. Sometimes from a client request.


## 2. What is a status code 202?
The request has been received but not yet acted upon.

## 3. What is a status code 308?
Permanent redirect - Resource lives at a different URL and we can tell the client what it is 

## 4. What code would you use if an update didn’t return data to a client?
A 204, 'No Content' error. For things like saving something they have just changed.

## 5. What code would you use if a resource used to exist but no longer does?
A 410 'Gone' error. It is similar to the 404, which is 'Not Found,' but it specifies that the system knows it was once in existence.

## 6. What is the ‘Forbidden’ status code?
403 'Forbidden.' This happens after authorization has been accepted, or if auth is not necessary

# Additional Resources #

## 1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?
We want to put something there that is not localhost and to protect our information.

## 2. What is middleware?
is software that provides common services and capabilities to applications outside of what's offered by the operating system.

## 3. What does app.use(express.json()) do?
app.use allows the server to accept middleware - this example allows the server to accept json as a body instead of a post element or git element.

## 4. What does the /:id mean in a route?
params object, with the name of the route parameter specified in the path as their respective keys

## 5. What is the difference beween PUT and PATCH?
Patch is only updating what the user passes- put would update all the information at once. Patch only updates what is given.

## 6. How do you make a defalut value in a schema?
You set it inside the Schema object as a key value pair with the key most likely being default:. In the example used in the video, it was default: Date.now. 

## 7. What does a 500 error status code mean?
Internal server error. Generic error, but indicates that there is a problem with the server

## 8. What is the difference between a status 200 and a status 201?
200 - request received and is processing. 201 - request received, was successful, and has result of created resource.
