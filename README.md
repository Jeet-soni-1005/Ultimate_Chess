# Online Chess Platform

An online chess platform where users can play chess instantly without the hassle of logging in or signing up. Players are automatically matched when they connect to the website, and spectators can watch live games if all rooms are full.

## Features

- **No Login or Signup:** Just open the website and start playing!
- **Instant Matching:** Get automatically paired with an opponent if one is available.
- **Spectator Mode:** If a game is in progress, others can watch the match live.
- **Real-Time Communication:** Powered by WebSockets for seamless, real-time gameplay and updates.
- **Open Source:** This project is open-source and contributions are welcome!

## Tech Stack

- **Node.js**: Backend server for managing game rooms and players.
- **Chess.js**: Game engine for handling chess logic and enforcing rules.
- **EJS**: Templating engine for rendering HTML pages.
- **Socket.io**: For real-time, bi-directional communication between the server and clients.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/online-chess-platform.git
    cd online-chess-platform
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Run the application**:
    ```bash
    npm start
    ```

4. **Visit the application** in your browser at `http://localhost:3000`.

## How to Play

1. Visit the website.
2. If there is an available opponent, you will be automatically paired.
3. If two players are already playing, you can watch the game in spectator mode.
4. Enjoy the game!

## Project Structure

