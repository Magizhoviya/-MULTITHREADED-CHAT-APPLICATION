# -MULTITHREADED-CHAT-APPLICATION

COMPANY: CODTECH IT SOLUTION

NAME: MAGIZHOVIYA S

INTERN ID: CT04DH1610

DOMAIN: JAVA PROGRAMMING

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH

# TASK DESCRIPTION

Objective:

The main objective of this task is to design and implement a Multithreaded Chat Application that allows multiple clients to connect to a server and communicate with each other in real-time. This task introduces you to the core concepts of multithreading, socket programming, and client-server architecture using Java (or another language). Through this project, you will understand how concurrent processing works and how to build scalable, real-time networked applications.

Task Overview:

In this task, you are required to build a simple console-based or GUI-based chat application that supports the following:

Server Side (Multithreaded Server):

The server listens for incoming connections from clients.

For each new client, the server spawns a new thread to handle communication independently.

The server should broadcast incoming messages from one client to all other connected clients.

Maintain a list of active users and handle client disconnections gracefully.

Client Side:

Each client can connect to the server by providing a username.

Clients can send messages to the chatroom and receive messages from other users in real time.

The client should keep sending and receiving messages simultaneously using threads (one thread for input, one for output).

Functional Requirements:

Real-time message delivery to all connected clients.

Thread-safe server logic to manage multiple clients.

Graceful shutdown of server and client.

Optional enhancements: private messaging, GUI using JavaFX or Swing, message timestamps, command support (/quit, /users, etc.)

Learning Outcomes:

Upon completion of this task, you will:

Understand the principles of multithreading and concurrent programming.

Learn about socket communication using TCP/IP protocols.

Be able to manage shared resources in a multi-client environment.

Develop client-server systems with real-time communication features.

Gain experience in exception handling, thread synchronization, and network programming.

Tools and Technologies Required:

Programming language: Java (with Socket, ServerSocket, Thread classes)

Any IDE like IntelliJ IDEA, Eclipse, or VS Code

Command-line terminal or optional GUI for testing

Internet/network access for local or remote testing

This project serves as a foundation for more advanced systems like real-time collaborative apps, multiplayer games, and messaging platforms. It helps in understanding how scalable systems manage concurrency and multiple user sessions efficiently.
