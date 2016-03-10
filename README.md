# sockex
remote execute javascript code in a client's browser

alter the page to need in ```index.html```, then run server with
```
node server.js
```
while clients access page (default port 4000), send a post request with payload
```
curl -d "window.open(url);" localhost:4000
```
