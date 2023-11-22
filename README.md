# tic-tac-toe-game
It is a Computer network security project in which we have used a concept of socket programming and python language.

INTRODUCTION:

The aim of this project was to implement a two-player Tic-Tac-Toe game using Python and socket programming as a practical application of concepts learned in the Computer Networks coursework. The project focused on creating a server-client architecture where two players could connect over a network and play the game.

TECHNOLOGIES USED:
Programming Language: Python
Libraries:`socket`, `pickle`
Concepts: Client-Server Architecture, Socket Programming


PROJECT OVERVIEW:

The project comprises two main components:

1. Server Script (`host.py`):
   - Handles the server-side operations.
   - Establishes a socket connection and listens for incoming client connections.
   - Controls the flow of the game, managing the logic, and facilitating communication between the players.
   - Implements the Tic-Tac-Toe game rules and functionalities.


2. Client Script (`client.py`):
   - Represents a player in the game.
   - Connects to the server using socket communication.
   - Interacts with the server to play the game by making moves and responding to prompts.

WORKFLOW:

1. Server-Side Operations:
 - Creates a socket, binds it to a specific address and port, and listens for incoming                connections.
   - Accepts client connections and initializes the game session.
   - Facilitates the game's logic by coordinating moves between players.
   - Manages game state, detects wins or draws, and handles rematch requests.

2. Client-Side Operations:
   - Connects to the server using socket communication.
   - Participates in the game by interacting with the server.
   - Sends moves to the server and receives game updates.
   - Responds to prompts for rematch requests.



CHALLENGES FACED:


Socket Communication: Understanding and implementing socket communication for exchanging game data between the server and clients.
Game Logic Implementation: Ensuring accurate game state management, win-draw detection, and coordinating moves between players.

CONCLUSION:

The project successfully demonstrated the implementation of a simple Tic-Tac-Toe game using socket programming in Python. It showcased the practical application of networking concepts learned in the Computer Networks coursework.

FUTURE WORK:

- User Interface: Incorporating a graphical user interface (GUI) for a more interactive gaming experience.
- Security Measures: Implementing secure communication channels for sensitive data exchange.
- Scalability: Extending the game to support multiple simultaneous game sessions or additional features.


