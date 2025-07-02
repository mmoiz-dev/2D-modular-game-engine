# 2D Modular Game Engine

Welcome to the 2D Modular Game Engine project! This repository contains the source code for a flexible and modular game engine designed for 2D games. This is a project for our OOP class. A modular 2D game engine built in Java, designed for learning and experimenting with game development concepts. This project demonstrates entity management, tile-based levels, custom graphics rendering, and basic networking.

## 🎮 Features

- **Entities**: Base classes for different types of game entities, including players and mobs.
- **Level Management**: Tools for managing and loading levels with tile-based graphics.
- **Graphics Rendering**: Handles rendering of game objects and UI elements with support for spritesheets.
- **Networking**: Basic client-server networking capabilities for multiplayer support.
- **Input Handling**: Keyboard input management for player interactions.
- **Window Handling**: Manages the game window, supporting window events and resizing.
- **Custom Graphics Engine**: Low-level rendering with color and sprite management.

## 🗂️ Project Structure

```
2d-modular-game-engine
├── res
│   ├── levels
│   │   ├── small_test_level.png
│   │   └── water_test_level.png
│   └── spritesheet.png
├── src
│   └── ca
│       └── group1
│           └── game
│               ├── entities
│               │   ├── Entity.java
│               │   ├── Mob.java
│               │   ├── Player.java
│               │   └── PlayerMP.java
│               ├── gfx
│               │   ├── Colours.java
│               │   ├── Font.java
│               │   ├── Screen.java
│               │   └── SpriteSheet.java
│               ├── level
│               │   ├── tiles
│               │   │   ├── AnimatedTile.java
│               │   │   ├── BasicSolidTile.java
│               │   │   ├── BasicTile.java
│               │   │   └── Tile.java
│               │   └── Level.java
│               ├── net
│               │   ├── packets
│               │   │   ├── Packet.java
│               │   │   ├── Packet00Login.java
│               │   │   ├── Packet01Disconnect.java
│               │   │   └── Packet02Move.java
│               │   ├── GameClient.java
│               │   └── GameServer.java
│               ├── Game.java
│               ├── GameLauncher.java
│               ├── InputHandler.java
│               └── WindowHandler.java
├── LICENSE
└── README.md
```
## 🛠️ Technologies Used

- **Java**: Core language for engine and game logic
- **Custom Graphics**: Manual pixel manipulation and rendering
- **Basic Networking**: Java Sockets for multiplayer

## Prerequisites
- Java Development Kit (JDK) 8 or higher
- IDE (e.g., IntelliJ IDEA, Eclipse, VSCode)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/mmoiz-dev/2d-modular-game-engine.git
   ```
2. Navigate to the project directory:
   ```bash
   cd 2d-modular-game-engine
   ```
3. Compile the engine:
   ```bash
   javac -d bin src/**/*.java
   ```

## 📝 How to Run

1. Compile the Java source files in `src/`.
2. Run `GameLauncher.java` to start the game.
3. Use the keyboard to control the player and explore the level.

## 📚 What I Learned

- Game loop and rendering techniques
- Entity-component design patterns
- Level loading from images
- Basic networking with Java sockets
- Handling user input in games

## 🤝 Contributing

This project is for learning purposes, but feel free to fork and experiment!

## 📖 Credits

Inspired by classic 2D games and built for educational purposes.

---

*Built with ❤️ by Muhammad Moiz*
