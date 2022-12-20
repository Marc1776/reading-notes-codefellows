# CRUD

## Why this is important

Error codes can help developers identify and locate problems that arise, whether it's user error, server error to help with debugging.

## Status Codes based on REST

1.  Status Codes:
    - 100's:  Informational:  usually tells client the header of the request has been recieved and server will attempt transmission demand
    - 200's:  Success:  indicates request was accepted for async, doesnt mean it was successfully processed, just met validation requirements 
    - 300's:  Redirecting: Requested resources are no longer at the expected location, new request must be made at new location
    - 400's:  Client Error:  Client has sent incorrect input ie wrong URL, missing authentication, timeouts; parameters should be verified before trying new request
    - 500's:  Server Error:  Can indicate overwhelmed or unreachable server, usually just retry request by client
  
2.  202 indicates a request met validation requirements at time of sending processing will finish in the future

3.  308 tells client to use another URL, current one is no good.

4.  Code 204

5.  410

6.  403

## Build a REST API

1.  So you can use a server that's not the local host

2.  Code that runs when the server gets a request but before it hits the routes

3.  Allows the server to accept json as a body

4.  Means that it is a parameter

5.  Put will update everything whereas patch will update only the new information

6.  Putting default in the object you want defaulted

7.  500 is an error on the server, not client error

8.  201 means that an object was successfully created.

## Things I want to know more about

The video moved a very high speed, lots of explanation, but trying to connect everything at his speed was difficult, need to revisit.

## References

[REST API buildout](https://www.youtube.com/watch?v=fgTGADljAeg&t=127s)
