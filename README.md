# Realtime Chat with ReactJS
The project is a multiroom Node.js chat web app. It allows users to chat online with each other by entering messages into a simple form. A message, once entered, is sent to all the other users in the same chat room. When starting the application, a user is automatically assigned a guest name, but it can be changed by entering a command. Chat commands are prefaced with a slash (/). Similarly, a user can enter a command to create a new chat room (or join it if it already exists). You can simply register by email and start chatting.

## Overview
#### Server
Runs on a NodeJs server. Uses socket.io library for communication and file system for storing the chats and users.

#### Client
Uses ReactJs as a javascript main framework and socket.io library for communication.
