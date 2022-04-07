## Your application or a server?

By default, API requests in WeWeb are made by your application (i.e. client-side requests from the frontend).

But sometimes, APIs only accept requests that come from a server (i.e. server-side requests from the backend).

When you enable this option, WeWeb will make the request via a dedicated server. We won’t save or look at the data going through this server.

Consider using this option if you run into a Network Error as it may be related to a CORS issue.
