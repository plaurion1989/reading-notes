## Status Codes for REST

* In your own words, describe what each group of status code represents:

- 100’s = request recieved, but may fail.
- 200’s = request succeded
- 300’s = path not found
- 400’s = request invalid
- 500’s = server request failed

* What is a status code 202?

Accepted.

* What is a status code 308?

Redirect. URL change

* What code would you use if an update didn’t return data to a client?

Code 204 No Content

* What code would you use if a resource used to exist but no longer does?

Code 204 No Content

* What is the ‘Forbidden’ status code?

Code 403

## Build A REST API

* Why do we need to pull our MongoDB database string out of our server and put it into our .env?

When we deploy we are going to change our url and for security reasons.

* What is middleware?

code that runs between the app and the database.

* What does app.use(express.json()) do?

allows json data to be accepted as .body

* What does the /:id mean in a route?

it is an identifying parameter specific to the targeted element

* What is the difference beween PUT and PATCH?

Put creates new data from model, Patch updates data selectively

* How do you make a default value in a schema?

default:  
that should do it.

* What does a 500 error status code mean?

internal server error

* What is the difference between a status 200 and a status 201?

201: sucessful creation of a single object. 200: generic success

[Back to Main Page](../README.md)