### Description

This is a simple WebSockets demo. The original code can be found at https://codepen.io/matt-west/pen/tHlBb

### Steps to test the demo

1. Start a simple http server from the project root. 
```python3 -m http.server```
2. This starts the server on 8000 by default. Open the URL localhost:8000. This will create a WS connection.
4. Enter a message and it will be replayed back via the WS.