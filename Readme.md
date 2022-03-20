# API

## postman

API: is a interface to a server which has some data

### postman

postman is a tool for interacting with web based api. Api is just like an outlet that the server offers. just like we plug we used postman to get data(electricity) but instead of using physical cable we use internet

Before using the api read the documentation about the api, what information it has, how to interact with it, doc explains how to use it

go to workspace of the postman
workspace-->myworkspace
open a new tab
paste the address (if you want to check if everything is working write "/status" after the link) if everything is fine the status will be 'ok'
hit the send button

### HTTP : Hypertext Transfer Protocol

https: hypertext transfer protocol secure

In our communication between client and server we are using HTTP

#### the message that goes from client to the server is called "Request"

#### and what is coming back from the server is called "Response"

The upper part of the postman is "Request" section
The lower part is about "Response"

The response contains some Status code, Headers(Headers are meta information, additional information)

we can save the requests in postman.
we have to provide a collection in which we want to store the requests

We can also state some query parameters also if the API allows

key:value pair

path variables

#### Post Request

With Post we send data

with post request we have to supply a body

To post something into the api we have to be authenticated

To authenticate user we have been given a end point. In this case it is api-clients
so by writing it with url/api-clients
we have to add values in json format by going to body-->raw dropdown to json

we can use postman console to debug the requests and responses

#### Patch

update something in the posted data
update an existing order. Require authentication

#### Delete

Delete an existing order, Requires authentication

The request body needs to be empty
