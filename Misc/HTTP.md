# All Things HTTP

Hypertext Transfer Protocol, app-layer protocol to help transmitting HTML(and others). It is the main communication platform between web client and servers. It uses a client-server model, which can be seen below.

![image](https://user-images.githubusercontent.com/24599282/176496298-512788a9-7599-481f-89b1-ecc15d16c038.png)

Http does not keep any state between requests making it a stateless protocol. This allows data transfers between client and server to be handled in isolation.
Clients and servers communicate by exchanging individual messages (as opposed to a stream of data). The messages sent by the client, usually a Web browser, are called requests and the messages sent by the server as an answer are called responses.

## Response Codes

Can be found in their own [documentation](

## HTTP Request Methods

### CONNECT
  Starts the communication between the cleint and the requested resource.
### DELETE
  Deletes the given resource.
### GET
  Requests a specified resource.
### HEAD
  Requests the headers for a specified response, useful to getting headers of a response without the body. 
### OPTIONS
  Requests permitted communication options for a given URL or server.
### PATCH
  Request method applies partial modifications to a resource. Works similar to an UPDATE.
### POST
  Sends data to the server. Can create the same resource multiple times unlike PUT which is [idempotent](https://developer.mozilla.org/en-US/docs/Glossary/Idempotent).
### PUT
  Request method creates a new resource or replaces a representation of the target resource with the request payload.
### TRACE
  Performs a message loop-back test along the path to the target resource, providing a useful debugging mechanism.
## HTTP Caching 

Caching is a way of storing previous responses for future requests. Allowing for a high amount of reusability. 

### Types of Caches

  - Private Caches
    - These are a type of cache that is representative of one singular client. Useful for storing personalized responses for specific users. For use a ```private``` directive must be specified. 
  - Shared Cache 
    - Used to store responses that are shared among users a Shared Cache is typically borken into two types of caches.
      - Proxy Caches
      - Managed caches

## HTTP Headers

A method of communication that allows client and server to send information via requests and responses. 

### Context

Headers come in 4 groups according to context

 - Request Headers:
    - Holds information both about the requested resource from the server and who client who is requesting the resource.     
 - Response Headers:
    - Holds information about the responses location and also information about the server that is providing the response. 
 - Representation Headers:
    - Holds information about the body of the resource.
 - Payload Headers:
    - Holds information about payload data, including content length and the encoding used for transport.

### Documentation

Additional information on HTTP Headers can be found [here](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers)
