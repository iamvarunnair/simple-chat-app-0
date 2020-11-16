# Simple Chat application

A simple chat application build using nodejs, express and socket.io following a [blog article](https://tsh.io/blog/socket-io-tutorial-real-time-communication/).

-   Server side code is in index.js which also serves public folder for client using express.
-   Client side code is in public which is server on server start.
-   Connects to socket when url is opened in browser.
-   Each browser tab generates a new random user.
-   Shows active users.
-   Shows all messages sent.

### Tech

-   [Nodejs](nodejs.org)
-   [Express](expressjs.com)
-   [Socket.io](socket.io)

### Installation

```sh
$ npm i
$ npm start
```

**Careful of the version mismatch, if all else fail this has worked with**

```sh
        "express": "^4.17.1",
        "socket.io": "^3.0.1"
        node -v v14.15.0
        <script src="/socket.io/socket.io.js"></script>
        // socket in frontend
```
