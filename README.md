﻿# Python-Socket
 This Python program is a simple client-server communication script using sockets. The server creates a socket, binds it to a specific IP address and port, and listens for incoming connections. When a client connects, the server creates a new thread to handle the communication with that client. The client, in turn, connects to the server, sends a message, and then sends a disconnect message.

**Simple Python Socket Communication**

This repository contains a basic Python client-server communication script using sockets. The program establishes a server that listens for incoming connections and creates a new thread to handle each client. The client connects to the server, sends a message, and then sends a disconnect message to terminate the connection.

Instructions:
Run the server script to start listening for incoming connections.
Run the client script to connect to the server and send a message.
The server will display the received message and the client will disconnect.
Usage:
Server:

python server.py
Client:

python client.py
Customization:
Modify the SERVER variable in the client script to specify the server's IP address.
