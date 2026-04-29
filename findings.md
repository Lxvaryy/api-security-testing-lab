# Findings

## Credential Exposure

Login request contained:
- email
- password

## API Endpoint

POST /rest/user/login

## Request Manipulation

Requests can be modified using Burp Repeater

## Server Response

Invalid email or password

## Security Implications

- APIs should enforce HTTPS
- Input validation is critical
- Authentication must be secured
