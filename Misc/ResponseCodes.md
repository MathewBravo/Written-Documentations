# HTTP Response Status Codes CHEAT SHEET

## 100's
  - **100 Continue**
    - Indicated everything is good and you can continue.
  - **101 Switching Protocols**
    - Indicates a protocol to which the server switches. 
  - **103 Early Hints**
    - Information response status code. 

## 200's
  - **200 OK**
    - Success status response code indicates that the request has succeeded.
  - **201 Created**
    - Success status response code indicates that the request has succeeded and has led to the creation of a resource. 
  - **202 Accepted**
    - Response status code indicates that the request has been accepted for processing, but the processing has not been completed.
  - **203 Non-Authoritatic Info**
    - Response status indicates that the request was successful but the enclosed payload has been modified.
  - **204 No Content**
    - Response code indicates that a request has succeeded, but that the client doesn't need to navigate away from its current page.
  - **205 Reset Content**
    - Response status tells the client to reset the document view, so for example to clear the content of a form, reset a canvas state, or to refresh the UI.
  - **206 Partial Content**
    - Response code indicates that the request has succeeded and the body contains the requested ranges of data.
    
## 300's
  - **300 Multiple Choices**
    - Indicates that the request has more than one possible responses. 
  - **301 Moved Permanently**
    - Indicates that the requested resource has been definitively moved to the URL.
  - **302 Found**
    - Indicates that the resource requested has been temporarily moved to the URL.
  - **303 See Other**
    - Indicates that the redirects don't link to the requested resource itself, but to another page.
  - **304 Not Modified**
    - Indicates that there is no need to retransmit the requested resources.
  - **307 Temporary Redirect**
    - Indicates that the resource requested has been temporarily moved to the URL. Unlike **302** **307** guarantees that the method and the body will not be changed when the redirected request is made.
  - **308 Permanent Redirect**
    - Indicates that the resource requested has been definitively moved to the URL. Unliked **301** the request method and the body will not be altered, whereas **301** may incorrectly sometimes be changed to a GET method.
## 400's
  - **400 Bad Request**
    - Indicates that the server cannot or will not process the request.
  - **401 Unauthorized**
    - Indicates that the client request has not been completed because it lacks valid authentication credentials for the requested resource.
  - **402 Payment Required**
    - Status code was created to enable digital cash or (micro) payment systems and would indicate that the requested content is not available until the client makes a payment. **NON STANDARD**
  - **403 Forbidden**
    - Indicates that the server understands the request but refuses to authorize it.
  - **404 Not Found**
    - Indicates that the server cannot find the requested resource.
  - **405 Method Not Allowed**
    - Indicates that the server knows the request method, but the target resource doesn't support this method.
  - **406 Not Acceptable**
    - Indicates that the server cannot produce a response matching the list of acceptable values defined in the request's proactive content negotiation headers.
  - **407 Proxy Authentication Required**
    - Indicates that the request has not been applied because it lacks valid authentication credentials for a proxy server. 
  - **408 Request Timeout**
    - Response status code means that the server would like to shut down this unused connection.
  - **409 Conflict**
    - Indicates a request conflict with the current state of the target resource.
  - **410 Gone**
    - Indicates that access to the target resource is no longer available at the origin server.
  - **411 Length Required**
    - Indicates that the server refuses to accept the request without a defined Content-Length header.
  - **412 Precondition Failed**
    - Indicates that access to the target resource has been denied. This happens with conditional requests on methods other than GET or HEAD when the condition defined by the If-Unmodified-Since or If-None-Match headers is not fulfilled.
  - **413 Payload Too Large**
    - Indicates that the request entity is larger than limits defined by server.
  - **414 URI Too Long**
    - Indicates that the URI requested by the client is longer than the server is willing to interpret.
  - **415 Unsupported Media Type**
    - Indicates that the server refuses to accept the request because the payload format is in an unsupported format.
  - **416 Range Not Satisfiable**
    - Indicates that a server cannot serve the requested ranges.
  - **417 Expectation Failed**
    - Indicates that the expectation given in the request's Expect header could not be met.
  - **418 I'm a teapot**
    - Reference to Hyper Text Coffee Pot Control Protocol defined in April Fools' jokes in 1998 and 2014.
  - **422 Unprocessable Entity**
    - Indicates that the server understands the content type of the request entity, and the syntax of the request entity is correct, but it was unable to process the contained instructions.
  - **425 Too Early**
    - Indicates that the server is unwilling to risk processing a request that might be replayed, which creates the potential for a replay attack.
  - **426 Upgrade Required**
    - Indicates that the server refuses to perform the request using the current protocol but might be willing to do so after the client upgrades to a different protocol.
  - **428 Precondition Required**
    - Indicates that the server requires the request to be conditional.
  - **429 Too Many Requests**
    - Indicates the user has sent too many requests in a given amount of time ("rate limiting").
  - **431 Request Header Fields Too Large**
    - Indicates that the server refuses to process the request because the request's HTTP headers are too long.
  - **451 Unavailable For Legal Reasons**
    - Indicates that the user requested a resource that is not available due to legal reasons, such as a web page for which a legal action has been issued.

## 500's
  - **500 Internal Server Error**
    - Indicates that the server encountered an unexpected condition that prevented it from fulfilling the request.
  - **501 Not Implemented**
    - Server error response code means that the server does not support the functionality required to fulfill the request.
  - **502 Bad Gateway**
    - Indicates that the server, while acting as a gateway or proxy, received an invalid response from the upstream server.
  - **503 Service Unavailable**
    - Indicates that the server is not ready to handle the request. 
  - **504 Gateway Timeout**
    - Indicates that the server, while acting as a gateway or proxy, did not get a response in time from the upstream server that it needed in order to complete the request. 
  - **505 HTTP Version Not Supported**
    - Indicates that the HTTP version used in the request is not supported by the server.
  - **506 Variant Also Negotiates**
    - This protocol enables a client to retrieve the best variant of a given resource, where the server supports multiple variants.
  - **507 Insufficient Storage**
    - Indicates that a method could not be performed because the server cannot store the representation needed to successfully complete the request.
  - **508 Loop Detected**
    - Indicates that the server terminated an operation because it encountered an infinite loop while processing a request.
  - **510 Not Extended**
    - The server received a request that contains an extension declaration, that describes the extension to be used, but any described extensions are not supported for the request.
  - **511 Network Authentication Required**
    - Indicates that the client needs to authenticate to gain network access.



