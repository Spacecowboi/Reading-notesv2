# Message Queues

### Socket.io Chat

1. Explain to a non-technical recruiter waht the Chat Example does.

* The example shows a web app that allows users to talk with each other in real-time.

2. What proof of life are we getting on the backend from the above app?

* When the message is sent, it's being broadcast to all users. Thus, proof of life.

3. Socket.IO gives us the iO.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

* socket.broadcast.emit(). This will send that message to everyone except the socket sending the broadcast message.

### Rooms

1. What is a room and how might a room be useful?

* "An arbitrary channel that sockets can *join* and *leave*. It can be used to broadcast events to a subset of clients

2. How do you join a room?

* call join = .join()

3. How do you leave a room?

* socket.on('disconnect', ())

### Namespaces

1. What is a Namespace and what does it allow you to do?

* "A communication channel that allows you to split the logic of your application over a single shared connection(multiplexing)."

2. Each namespace potentially has its own what?

* Event Handlers, Rooms, Middlewares.

3. Discuss a possible use case for separate namespaces

* From the article: "You want to create a special namespace that only authorized users have access to, so the logic related to those users is separated from the rest of the application"