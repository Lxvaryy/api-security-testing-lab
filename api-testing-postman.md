# API Testing with Postman

## Overview

Postman was used to test API endpoints and understand how different HTTP methods work. This helped simulate real-world API interactions outside of the browser.

## GET Request

Endpoint:
https://jsonplaceholder.typicode.com/posts

This request retrieves data from the server.

Result:
- A list of posts is returned in JSON format

## POST Request

Endpoint:
https://jsonplaceholder.typicode.com/posts

Body:
{
  "id": 1,
  "title": "Evary testing",
  "body": "learning api security",
  "userId": 1
}

This request creates new data on the server.

Result:
- A new object is returned with a generated ID

## PUT Request

Endpoint:
https://jsonplaceholder.typicode.com/posts/1

Body:
{
  "id": 1,
  "title": "Evary testing 2",
  "body": "updated by Evary",
  "userId": 1
}

This request updates existing data.

Result:
- The updated object is returned

## Key Learnings

- GET retrieves data from a server
- POST sends data to create new resources
- PUT updates existing resources
- APIs communicate using JSON format

## Security Insight

Understanding API behavior is important for identifying:

- exposed endpoints
- weak authentication
- improper input validation
- insecure data handling

Postman allows testers to simulate requests and analyze how the server responds, which is essential for API security testing.
