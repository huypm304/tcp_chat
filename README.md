# TCP Client-Server Messaging (Python)

A simple TCP socket-based messaging system using Python that demonstrates basic networking, threading, and client-server communication.

---

## Features

- TCP/IP communication using Python sockets
- Multi-client handling with threading
- Fixed-length header protocol for message framing
- Graceful client disconnect with `!DISCONNECT` message

---

## How to Run

### Start the Server
```bash
python server.py
```

### Start the Client
```bash
python client.py
```

**Key Notes:**
1. **Order Matters**: Always start the server before the client.
2. **Separate Terminals**: Run the server and client in different terminal windows.
3. **Python 3 Users**: If your system defaults to Python 2, use:
   ```bash
   python3 server.py
   python3 client.py
   ```
**Example Workflow**:
1. Terminal 1 (Server):
   ```bash
   python server.py
   ```
2. Terminal 2 (Client):
   ```bash
   python client.py
   ```