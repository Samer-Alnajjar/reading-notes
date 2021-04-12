**Monday-12/4/2021**

**This is what I learned in class 401_13:**

![Image of socket.io](https://avinetworks.com/wp-content/uploads/2020/03/packet-switching-diagram.png)

![Image of server](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c9/Client-server-model.svg/1200px-Client-server-model.svg.png)

1. What does it mean that web sockets are bidirectional? Why is this useful?

    The bidirectional port is an 8-bit port capable of transmitting between 75 and 300 KBps.it is useful because it allows data to be sent and received on the same channel.

2. UDP is often refereed to as a connection less protocol. Why is this?

    Yes, Because it can serve it's own client code through socket.io.

3. What happens when a client emits an event?

    The server take that emitted message with the payload and respond with and action or another emit message.

4. What happens when a server emits an event?

    The client receive this emit and respond to it with an action.

5. What happens if a client “misses” an event?

    The application will still run.

6. How can we mitigate this?

    Check that each events have their own handler.


-------------------------------------------------------------

## Vocabulary Terms

**Socket**: Sockets allow communication between two different processes on the same or different machines.

**Web Socket**: WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection.

**Socket.io**:is a library that enables real-time, bidirectional and event-based communication between the browser and the server.

**Client**: client is a piece of computer hardware or software that accesses a service made available by a server as part of the client–server model of computer networks.

**Server**: server is a piece of computer hardware or software that provides functionality for other programs or devices.

**OSI Model**: The Open Systems Interconnection model is a conceptual model that characterises and standardises the communication functions of a telecommunication or computing system without regard to its underlying internal structure and technology.

**TCP Model**: The Internet protocol suite is the conceptual model and set of communications protocols used in the Internet and similar computer networks.

**TCP**: The Transmission Control Protocol (TCP) is one of the main protocols of the Internet protocol suite.

**UDP**: User Datagram Protocol (UDP) – a communications protocol that facilitates the exchange of messages between computing devices in a network.

**Packets**:  a packet is a small segment of a larger message. Data sent over computer networks*, such as the Internet, is divided into packets.



----------------------------------------------
## Preparation Materials

- To create a chat example please follow the example in this link:

[chat example](https://socket.io/get-started/chat/)



- Rooms and Namespace:

![Image of Rooms](https://socket.io/images/rooms.png)

![Image of Namespaces](https://socket.io/images/rooms-redis.png)

- Socket.io emit cheat sheet:

[Image of cheat sheet](https://socket.io/docs/v3/emit-cheatsheet/index.html)
