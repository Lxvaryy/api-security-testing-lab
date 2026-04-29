# Burp Suite Analysis

## Overview

Burp Suite was used to intercept and analyze HTTP traffic between the browser and OWASP Juice Shop.

## Capturing Traffic

Traffic was captured using:
Proxy → HTTP History

## Filtering Requests

Search terms used:
- login
- user
- rest

## Login Request Identified

Endpoint:
POST /rest/user/login

Request body:
{
  "email": "TestEvary@google.com",
  "password": "12345678"
}

## Sending to Repeater

Right click → Send to Repeater

## Request Analysis

- Headers
- Cookies
- JSON payload

## Request Modification

Modified password and resent request.

Response:
Invalid email or password

## Key Takeaways

- API requests expose credentials
- Requests can be modified
- Burp Suite enables deep inspection
