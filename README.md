# Java Multi-Client Chat Application

This is a console-based multi-client chat application built using Java Socket Programming and Multithreading. The application follows a Client-Server architecture where multiple clients can connect to a central server and communicate in real time.

The server listens on port 1234 and handles multiple client connections simultaneously using threads. When one client sends a message, the server broadcasts it to all connected clients. This project demonstrates practical implementation of Java networking, multithreading, socket communication, and input/output stream handling.

---

## Technologies Used:

- Java
- Socket Programming
- Multithreading
- I/O Streams

---

## Project Structure:

ChatApplication/
│
├── Server.java
├── Client.java
└── README.md

---

## How It Works:

1. The server starts and listens on port 1234.
2. Clients connect to the server using localhost and the same port number.
3. Each client runs in a separate thread.
4. Messages sent by one client are broadcast to all connected clients.
5. Multiple users can chat simultaneously in real time.

---

## How To Run:

Step 1: Compile
javac Server.java
javac Client.java

or

javac *.java

Step 2: Run Server
java Server

You should see:
Server started on port 1234...

Step 3: Run Client (open a new terminal)
java Client

You can open multiple terminals and run multiple clients to test real-time chat functionality.

Sample Output:

Server:
Server started on port 1234...
New client connected

Client:
Enter your username:
Monty
Monty: Hello everyone!

---

## Features:

- Multi-client support
- Real-time message broadcasting
- Username-based messaging
- Thread-based connection handling
- Simple console interface

---

## Concepts Practiced:

- Java Networking
- Client-Server Architecture
- Multithreading
- Socket Communication
- Exception Handling

---

## Future Improvements:

- GUI version using JavaFX or Swing
- Private messaging
- File sharing
- Message encryption
- Cloud deployment

---

## Author:
Mayank Malviya
Aspiring Software Developer | Java Enthusiast

If you found this project helpful, consider giving it a star.
