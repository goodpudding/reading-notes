# Message Queues

## Socket.io Chat Example

* *Explain to a non-technical recruiter what the Chat Example (above) does.*

  * The chat example is an instant messanger
* *What proof of life are we getting on the backend from the above app?*

  * users connecting and disconnecting
* *Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?*

  * io.broadcast()
## Rooms

* *What is a room and how might a room be useful?*

  * Think of like a zoom call. The zoom call would be the namespace and if we created breakout rooms for people to work together, those break out rooms are rooms in socket.io.
* *How do you join a room?*

  * io.on("connection", (socket) => {
  socket.join("some room");
});
* *how do you leave a room?*

  * For example − To leave room 'room-1',

    socket.leave("room-"+roomno);
## Namespaces

* *What is a Namespace and what does it allow you to do?*

  * A name space is basically like a route in express. It's a way of accessing a path of information or funcionality.
* *Each namespace potentially has its own what? (hint: 3 things)*

  * event handlers, rooms, middleware
* *Discuss a possible use case for separate namespaces*

  * Thinking in like gaming applications, you could the seperate namespaces to access different game modes like ranked, normals, custom, etc.
