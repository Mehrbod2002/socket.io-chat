# socket.io-chat
Socket.io chat Voice Image File - Nginx , Node.JS , Express , Redis With Front.End sample
## Introduction
Code is performed by Socket.io to event listener and emiting messages in server-side and front-end languages .
It used JWT to confirm connections status and validating token and intention was as middleware worker NOT AS AN ENGINE .
Wish use as Engine ? Use Adaptor in Socket.io and set your validators in VALIDATE_TOKEN.js as well set your own configurations in nginx and signature.js
which work as middleware to confirm users connections.
Also it used for sending image ... and buffer messages which controls by REDIS.
Main Stream is controlled by Pure MySql on DATABASE.JS.
Middleware functions are defined on SIGNATURE.js

### Perform test on Index2.html 

## Initiate 

``` bash
cd /chat && npm install && npm start 
```
or run as pm2 
``` bash
pm2 start socket.js && pm2 start app.js
```

## Double-check on logs for exceeded emitting .
