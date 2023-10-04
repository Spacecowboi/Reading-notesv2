# Socket.io

### Web Sockets

1. What is a web socket?

* "A Web Socket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection."

2. Describe the Web Socket request/response handshake and what happens once the connection is established.
 
* First the client sends a "handshake" request to a server. Then, if the server supports WebSocket and accepts it, the server responds with an HTTP status code (switching protocols). Once that handshake is established and successful, the WebSocket connection is established and both client and server can send data to each other, full-duplex style.

3. Web Sockets provide a standardized way for the server to send content to a client without first receiving a __ from that client.

* request

### Socket.io Tutorial

1. What does the event handler io.on() do?

* It defines event handlers for events that take place within the Socket.IO application. 

2. Describe some possible proof of life or proof that the code works as expected.

* Maybe logging connects and disconnects when the user engages with the application. Or logging real-time data transfers as they happen.

3. What does socket.emit() do?

* It sends an event from the client to the server or vice versa. It lets you send data and trigger events that are handled by the recipient. 

### Socket.io vs Web Sockets

1. What is the difference between WebSocket and Socket.IO?

* WebSocket is low-level and standardized protocol for communication, while Socket.IO is a much higher-level library that provides a variety of transport mecahnisms for data, allowing for better browser support and ease of use.

2. When would you use Socket.IO?

* If I wanted simple and easy solutions for real-time communication, particularly if it's browser-based. 

3. When would you use WebSockets?

* If I need finer control and I need to work directly with the WebSocket protocol, then native WebSockets offer the lowest-level control and MAXIMUM performance.