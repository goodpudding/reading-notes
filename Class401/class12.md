# Socket.io

## Web Sockets

* *What is a Web Socket?*

  * <p>A WebSocket is a communication technology that enables two-way communication between a client (usually a web browser) and a server over a single, long-lived connection. It allows data to be exchanged in real-time without the need for constantly refreshing a web page or making multiple requests. WebSockets are often used in web applications for live updates, chat systems, and real-time notifications.</p>
* *Describe the Web Socket request/response handshake and what happens once the connection is established.*

  * <p> Web socket uses TCP or 3 way handshake connection. The first handshake is when the first client says to the second client "I will send some data". The second handshake is when the second client replies "Okay, ready to recieve". Then the first one says "Sending my data" and the sends the data. This is different than UDP which just says YOLO, FULL SEND THAT DATA</p>
* *Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.*

  * request

## Socket.io Tutorial

* *What does the event handler io.on() do?*

  * Enables realtime bidirectinoal event-based communication
* *Describe some possible proof of life or proof that the code works as expected*

  * IMs, Push notifications, online gaming
* *What does socket.emit() do?*

  * <p>socket.emit() is a function in the Socket.IO library that sends a message from the server to a connected client or from the client to the server. It takes an event name and optional data as arguments, allowing for custom events and data exchange between the two parties.</p>

## Socket.io vs Web Sockets

* *What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).*

  * WebSocket is the proctol on which Socket.IO is built on. You can create your own library, but Socket.IO makes is super easy to use.
* *When would you use Socket.IO?*

  * If you are looking for an easy way to have peer-to-peer connection with scaling and browser compatibility, then you want to use socket.io
* *When would you use WebSockets?*
  
  * If you want to create a light solution without all the bells and whistles and know exactly where you're connecting, then use websockets.

## Videos

## OSI Model Explained

* *What are a couple of key takeaways from this video?*

  * <p>Since I was in networking before, I always thought of the osi model from bottom up, because that's how we would troublshoot things, so its interesting flipping it and thinking from the application down.</p>
* *TCP Handshakes Explained*

* *Translate the gist of this video to a non-technical friend*

  * <p> Web socket uses TCP or 3 way handshake connection. The first handshake is when the first client says to the second client "I will send some data". The second handshake is when the second client replies "Okay, ready to recieve". Then the first one says "Sending my data" and the sends the data. This is different than UDP which just says YOLO, FULL SEND THAT DATA</p>
