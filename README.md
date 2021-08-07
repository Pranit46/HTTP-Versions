# HTTP-Versions

## HTTP/0.9 - The one-line protocol
  
  1) Initial version of HTTP - a simple client-server, request-response, telenet-friendly protocol
  2) Methods supported: GET only
  3) Response type: hypertext only
  4) Connection nature: terminated immediately after the response
  5) No HTTP headers (cannot transfer other content type files), No status/error codes, No URLs, No versioning

## HTTP/1.0 - Building extensibility

  1) It comes in May 1996
  2) This is the first protocol revision to specify its version in communications 
  3) Still in wide use, especially by proxy servers
  
  
## HTTP/1.1 - The standardized protocol

  1) It comes in June 1999
  2) Current version, persistent connections enabled by default and works well with proxies.
  3) Supports request pipelining Allows multiple requests to be sent at the same time.
  4) Allows the server to prepare for the workload and potentially transfer the requested.


## HTTP/1.2 - A protocol for greater performance

    The HTTP/1.2 protocol has several prime differences from the HTTP/1.1 version:

     1) It is a binary protocol rather than text. It can no longer be read and created manually. Despite this hurdle, improved optimization techniques can now be implemented.
     2) It is a multiplexed protocol. Parallel requests can be handled over the same connection, removing the order and blocking constraints of the HTTP/1.x protocol.
     3) It compresses headers. As these are often similar among a set of requests, this removes duplication and overhead of data transmitted.
     4) It allows a server to populate data in a client cache, in advance of it being required, through a mechanism called the server push.
