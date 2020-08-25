# Nigiri IO
a reverse proxy / URL shortner
## What do we hope to accomplish: 
Build an app that will allow a user to connect, and input a webpage to shorten. 
The app will then generate a shortened random string (Ex GiantBlueBat) which will be uploaded to a database to connect the random string with the desired URL. 

When a second user connects to the shortened URL (Ex. Nigiri.io/GiantBlueBat) It will forward them to the originally submitted URL. 

## Features
[ ] Allow a user to store a webpage in the database by submiting it. 
    [ ] Build a form to collect the URL
    [ ] Connect the form to a servlet to host the form
    [ ] Connect the database to the servlet to store the submitted URL
    [ ] Build a generator for random strings. 

[ ] Allow a user to recall a stored webpage by visiting a specefic URL
    [ ] Build a servlet that takes the end of a URL
    [ ] Connect the servlet to a database that allows the original URL to be retrieved
    [ ] Forward the user from the shortened webpage to the original URL

## Possible Expansion Ideas
[ ] Provide logging details, IE number of times a page has been visited
[ ] Create a public API so a user can find information on which pages redirect where. 

