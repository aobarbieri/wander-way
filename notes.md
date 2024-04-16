## The Principals of REST (Representational State Transfer) Architecture

1 - Separate API into logical resources.
Resource: object or representation of something which has data associated to it.

2 - Expose structured, resource-based URLs.
Example: https://www.wanderway.com/tours

3 - Use HTTP methods (verbs).
/tours instead of /getTour

POST -> Create,
GET -> Read,
PUT (send the entire object) and PATCH (only part of the object that has been changed) -> Update,
DELETE -> Delete.

4 - Send data as JSON.
Data format that looks like a JS object. All key-value pairs must be type String.

5 - Be stateless.
Stateless RESTful API: All state is handled on the client. Each request mustt contain all the information necessary to process a certain request. The server should NOT have to remember previous requests.
