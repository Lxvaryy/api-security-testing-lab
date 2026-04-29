\# API Testing with Postman



\## Overview

Postman was used to send API requests and analyze responses.



\## GET Request

Endpoint:

https://jsonplaceholder.typicode.com/posts



Used to retrieve data.



\## POST Request

Endpoint:

https://jsonplaceholder.typicode.com/posts



Body:

{

&#x20; "title": "Evary testing",

&#x20; "body": "learning api security",

&#x20; "userId": 1

}



Response returns a created object.



\## PUT Request

Endpoint:

https://jsonplaceholder.typicode.com/posts/1



Body:

{

&#x20; "id": 1,

&#x20; "title": "Evary testing 2",

&#x20; "body": "updated by Evary",

&#x20; "userId": 1

}



Response returns updated data.



\## Key Learnings

\- GET retrieves data

\- POST creates data

\- PUT updates data

\- APIs use JSON structure



\## Security Perspective

Understanding APIs helps identify:

\- exposed endpoints

\- weak validation

\- insecure data handling

