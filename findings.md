\# Findings



\## Sensitive Data Exposure

Login requests contained email and password in JSON format.



\## API Endpoint Exposure

Endpoint:

/rest/user/login



Can be accessed directly.



\## Request Manipulation

Requests can be modified using Burp Repeater.



\## Server Response Behavior

Server returned:

"Invalid email or password"



\## Security Implications

\- APIs should use HTTPS to protect data

\- Input validation is necessary

\- Authentication must be secure

