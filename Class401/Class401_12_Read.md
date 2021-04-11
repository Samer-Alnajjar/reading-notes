**Sunday-11/4/2021**

**This is what I learned in class 401_12:**

![Image of AC](https://lh3.googleusercontent.com/proxy/chfZI67zPW0iScc2KOeydBgQaSGLY83bXjnOhZXvdyxgnxb2U-rExQn1R8DgUKkPraMLOAJxiRGna3Dzyf95vNsSgOjYT3ktiqTjrAqc4Ks-Si7kM24EtYd6UiJ5P1sxYQI4yJCBbP21Tw)

![Image of Event](https://upload.wikimedia.org/wikipedia/commons/c/cb/Event_driven_programming_Simply_Explained.jpg)

1. What is the benefit of transforming data into packets?

    Because when sending data as a large block and for some reason the data is not received, we will have to send the whole data again, but when sending the data as packets, so if the a packet is not received, we will have to resend that packet again.

2. UDP is often refereed to as a connectionless protocol. Why is this?

    UDP is a connectionless protocol. It is known as a datagram protocol because it is analogous to sending a letter where you don't acknowledge receipt. Examples of applications that use connectionless transport services are broadcasting and tftp .

3. Can a socket server application have multiple socket connections?

    Yes, it can handle up to 65535.

4. Can a socket connection application be connected to multiple socket servers?

    Yes.

5. Can an application be both a socket server and a socket connection?

    Yes, [Link](https://www.quora.com/Can-you-make-a-client-socket-and-a-server-socket-in-one)

-------------------------
## Vocabulary Terms

**Observer Pattern**: The observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.

**listener** : An event listener is a procedure or function in a computer program that waits for an event to occur

**Event handlers** : In programming and software design, an event is an action or occurrence recognized by software, often originating asynchronously from the external environment, that may be handled by the software.

**Event-driven programming** : is when a program is designed to respond to user engagement in various forms.

**Event Loop** : In computer science, the event loop is a programming construct or design pattern that waits for and dispatches events or messages in a program.

**Event Queue** is to synchronize the different servers when a change has occurred in the Sitecore Back Office.

**call stack** is a stack data structure that stores information about the active subroutines of a computer program.

**Emit/Raise/Trigger** in event-driven programming, emit sends a message to trigger a response and raise an event

**Subscribe** is a method that listens for a specific event that is raised by an event publisher.

**database** is a data structure that stores organized information.

-----------------------------------------------------------------------------

## Preview

- Which 3 things had you heard about previously and now have better clarity on?
      - Middleware
      - NodeJS
      - basic auth

- Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
      - Socketio
      - Authorization
      - Event driving programming
-------------------------------------------------------------------------
## Additional Resources

  - **OSI Model** (Open Systems Interconnection Model) is a conceptual framework used to describe the functions of a networking system.

![Image of OSI](https://miro.medium.com/max/891/1*QgyDWZRA-eY7bo04M6E_hw.png)


  - TCP HandShake
  
    TCP 3-way handshake is a process which is used in a TCP/IP network to make a connection between the server and client. It is a three-step process that requires both the client and server to exchange synchronization and acknowledgment packets before the real data communication process starts.

    ![Image of TCP](https://media.geeksforgeeks.org/wp-content/uploads/TCP-connection-1.png)

  - **WebSocket** is a computer communications protocol, providing full-duplex communication channels over a single TCP connection. The WebSocket protocol was standardized by the IETF as RFC 6455 in 2011, and the WebSocket API in Web IDL is being standardized by the W3C.
  - **Socket.IO** enables real-time bidirectional event-based communication. It works on every platform, browser or device, focusing equally on reliability and speed. Socket.IO is built on top of the WebSockets API (Client side) and Node.js. It is one of the most depended upon library on npm (Node Package Manager).
  - **WebSocket** :
    - It is the protocol that is established over the TCP connection.
    - 	It provides full-duplex communication on TCP connections.
    - Proxy and load balancer is not supported in WebSocket.
    - It doesn’t support broadcasting.
    - 	It doesn’t have a fallback option.
  - **Socket.io** :
    - It is the library to work with WebSocket
    - Provides the event-based communication between browser and server.
    - A connection can be established in the presence of proxies and load balancers.
    - It supports broadcasting.
    - It supports fallback options.