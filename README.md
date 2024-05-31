Instructions on how to run the chat application.


# Simple Java Chat Application

This is a simple online chat application built using Java. The application allows multiple users to connect to a central server, send messages, and receive messages from other users.

## Requirements

- Java JDK
- Text editor or IDE

## How to Run

1. **Compile the Java files**:
   Open your terminal or command prompt and navigate to the directory containing `ChatServer.java` and `ChatClient.java`. Run the following command to compile the files:

   ```sh
   javac ChatServer.java ChatClient.java
   ```

    
Start the server: In the terminal, start the chat server with the following command:

```shell
java ChatServer
```

You should see the message Chat server started....

Start the clients:
Open new terminal windows for each client and run the following command to start a client:

```shell
java ChatClient
```

Each client will receive a welcome message and can start sending messages.

Send and receive messages:
Type messages in the client terminal and press Enter to send. The server will broadcast the messages to all connected clients.

Exit the chat:
Type exit and press Enter to disconnect a client from the server.