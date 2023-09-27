## Your application or a server?

When you make an API call in WeWeb the request is made by your application (i.e. client-side request from the frontend, you're browser).

But sometimes, APIs only accept requests that come from a server (i.e. server-side requests from the backend).

When you enable this option, WeWeb will proxy the request to bypass CORS errors but the information will still be visible in the client. This option is not meant to keep private tokens private. You should never use private API keys in REST API calls made through the client.

Consider using this option if you run into a Network Error as it may be related to a CORS issue.
