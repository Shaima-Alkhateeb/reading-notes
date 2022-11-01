# What is the OSI Model ?

- Open Systems Interconnection (OSI)
- is a conceptual framework that is used to describe how a network functions(helped standardize the way computer systems send information to each other).
- It is a tool for understanding how networks function.

## What is the meaning of layer and What are the 7 Layers of Networking ?

**A layer**
is a way of categorizing and grouping functionality and behavior on and of a network


1. Please | **Physical Layer**
2. Do | **Data Link Layer**
3. Not | **Network Layer**
4. Tell (the) | **Transport Layer**
5. Secret | **Session Layer**
6. Password (to) | **Presentation Layer**
7. Anyone | **Application Layer**


# Socket.IO :

### What is Socket.IO ?

Socket.IO is a library that enables low-latency, bidirectional and event-based communication between a client and a server.

### What is Socket.io Library ?
It is a library which enables real-time and full duplex communication between the Client and the Web servers.
It uses the WebSocket protocol to provide the interface. Generally, it is divided into two parts, each of which use WebSockets, but also provide additional functionality such as broadcasting, namespacing, and other means of segmenting connected clients into groups.

**Server Side:** It is the library for Node.js that serves as "hub" or "traffic cop"
**Client Side:** it is the library that runs inside the browser or a "satellite" server that connects to a "hub"

#### server
```
server.on('connection', (socket) => {
  // When clients "emit" an event called 'some-event', this code on the server handles it
  socket.on('some-event',  (payload) => {
    // do something with the event
  }
})
```

#### client
```
// When anyone "emits" this code on the client handles it
client.on('cool-thing-happened', (payload) => {
  // do something with the event
})
```
