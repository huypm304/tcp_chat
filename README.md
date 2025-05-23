# TCP Client-Server Messaging (Python)

A simple TCP socket-based messaging system using Python that demonstrates basic networking, threading, and client-server communication.

---

## Features

- TCP/IP communication using Python sockets
- Multi-client handling with threading
- Fixed-length header protocol for message framing
- Graceful client disconnect with `!DISCONNECT` message

---

## File Structure

├── server.py # Server-side code
├── client.py # Client-side code
└── README.md # This file

## How to Run

1. Start the server:
```bash
python server.py