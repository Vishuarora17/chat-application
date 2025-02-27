# Java Chat Application

A real-time chat application built using Java sockets, supporting multiple clients for seamless communication.

## Features
- Real-time messaging between clients
- Multi-client support using threading
- User-friendly console-based UI
- Server-client architecture
- Efficient and scalable design

## Technologies Used
- Java (Sockets, Threads)
- Networking APIs

## Installation & Setup
### Prerequisites
- Java Development Kit (JDK) installed
- Any Java IDE (Eclipse, IntelliJ IDEA, or VS Code) or command-line setup

### Steps to Run
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/chat-application.git
   cd chat-application
   ```
2. **Compile the Java files:**
   ```bash
   javac Server.java Client.java
   ```
3. **Run the Server:**
   ```bash
   java Server
   ```
4. **Run the Client (Multiple instances can be started):**
   ```bash
   java Client
   ```

## How It Works
1. The server listens for incoming client connections.
2. Clients connect to the server and start exchanging messages.
3. The server manages message broadcasting among all connected clients.

## Future Enhancements
- Graphical User Interface (GUI)
- End-to-end encryption
- File sharing support

## Contributing
Contributions are welcome! Feel free to submit a pull request.


## Author
Vishvesh arora
