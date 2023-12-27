# Tic Tac Toe Game using Socket Programming

This project implements a simple Tic Tac Toe game using Socket programming. It allows two players to connect to a server and play the game remotely.

## Project Structure

- **server.py:** Server-side script that manages the game logic and communication with connected clients.
- **player.py:** Client-side script for each player, responsible for handling user input and communicating with the server.

## How to Play

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/tic-tac-toe-socket.git
   cd tic-tac-toe-socket

2. **Check IP address of your server:**
   ```bash
   ipconfig

3. **Modify address in server.py for host variable to match the IP address of the server**

4. **Run server.py first on the host device**
   ```bash
   python server.py

5. **Run player.py on two separate terminals or two different devices**
   ```bash
   python player.py

That's it. Enjoy your game!
