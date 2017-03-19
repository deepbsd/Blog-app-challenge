# Blog API Challenge

I am mistakenly calling this the Blog App Challenge.  That probably comes later.  This is actually building an API.  
But it's a good start.

In order to test this, you need to be running a local server with npm installed.  npm install will 
be required.  I'm requiring nodemon, json-body-parser, uuid, and express of course.  A few others.  Check the 
packages.json for more info.

By default the server runs on port 8080.  Calls to the '/' endpoint will be routed to '/blog-posts' and handled
at that point.  You'll probably need Postman or something similar to test this.
