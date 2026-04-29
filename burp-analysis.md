\# Burp Suite Analysis



\## Overview

Burp Suite was used to intercept and analyze HTTP traffic between the browser and OWASP Juice Shop.



\## Capturing Traffic

Traffic was captured using Burp Suite proxy.



Navigation:

Proxy → HTTP History



This section displays all requests sent from the browser.



\## Filtering Requests

Due to high traffic volume, filters were used.



Search terms:

\- login

\- user

\- rest



This helped isolate the login request.



\## Identifying Login Request

The login request endpoint:



POST /rest/user/login



The request contained JSON data:

{

&#x20; "email": "TestEvary@google.com",

&#x20; "password": "12345678"

}



\## Sending to Repeater

Steps:

\- Right click request

\- Click "Send to Repeater"



\## Inspecting Request

The request includes:

\- Headers

\- Cookies

\- JSON body



\## Modifying Request

The password value was modified and sent again.



Server response:

"Invalid email or password"



This demonstrates how attackers can manipulate requests before they reach the server.



\## Key Takeaways

\- Credentials can be exposed in API requests

\- Requests can be intercepted and modified

\- Burp Suite allows deep analysis of web traffic

