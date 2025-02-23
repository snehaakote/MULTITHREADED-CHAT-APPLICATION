# MULTITHREADED-CHAT-APPLICATION
Company: Codtech IT Solutions
Name: Sneha Akote
Intern ID: CT08RLO 
Domain: Java 
Duration: 4 weeks 
Mentor: Neela Santosh 
Description:
The Multithreaded Chat Application is a Java-based network communication system that allows multiple users to chat with each other in real-time. It uses a client-server architecture, where a central server manages connections and message broadcasting. Each client runs independently and communicates with the server using sockets and multithreading, enabling simultaneous conversations among multiple users.

Project Objectives
Develop a multi-client chat system using Java sockets and multithreading.
Allow real-time message broadcasting to all connected users.
Ensure smooth client-server communication with efficient threading.
Implement graceful client disconnection handling.
Provide a simple and scalable design that can be extended with additional features.
System Architecture
1. Server-Client Communication Model
A server listens on a predefined port for incoming client connections.
When a client connects, the server assigns it a dedicated thread for handling communication.
Messages sent by a client are broadcast to all other connected clients.
Clients can send and receive messages in real time.
2. Multithreading Mechanism
The server uses multiple threads to handle different clients concurrently.
Each client connection is managed by a separate thread to ensure responsiveness.
The server maintains a list of active clients and manages their communication efficiently.
Technical Details
1. Technologies Used
Programming Language: Java
Networking: Java Sockets (ServerSocket, Socket)
Multithreading: Java Threads (Runnable, Thread)
I/O Handling: BufferedReader, PrintWriter
2. Functional Components
Server
Listens for incoming client connections.
Assigns a dedicated thread to each client.
Maintains a list of connected clients.
Broadcasts messages to all clients.
Client
Connects to the server.
Sends messages to the server.
Listens for and displays incoming messages from other users.
Features
✅ Multi-Client Support – Multiple clients can chat simultaneously.
✅ Real-Time Communication – Messages are instantly delivered to all users.
✅ Thread Management – Each client runs in its own thread for efficiency.
✅ Message Broadcasting – Server ensures all clients receive messages.
✅ Error Handling – Graceful handling of client disconnections.

Future Enhancements
🚀 Graphical User Interface (GUI) using Java Swing or JavaFX.
🔒 User Authentication – Implement login and registration.
📜 Chat History Storage using a database.
📡 Encryption – Secure communication using SSL/TLS.
Output:
![Image](https://github.com/user-attachments/assets/bacca2ec-8e84-4606-b6b7-ec2a6f74a456)
