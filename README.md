# 2D Modular Game Engine

Welcome to the 2D Modular Game Engine project! This repository contains the source code for a flexible and modular game engine designed for 2D games. This is a project for our OOP class. A modular 2D game engine built in Java, designed for learning and experimenting with game development concepts. This project demonstrates entity management, tile-based levels, custom graphics rendering, and basic networking.

## 🎮 Features

- **Entity System**: Create and manage various game entities (players, mobs, etc.).
- **Tile-Based Levels**: Load and render levels from images for easy editing.
- **Custom Graphics Engine**: Low-level rendering with color and sprite management.
- **Basic Networking**: Supports multiplayer via simple client-server architecture.
- **Input Handling**: Responsive keyboard input for player control.

## 🗂️ Project Structure

```
2D-modular-game-engine/
├── src/
│ └── ca/group01/game/
│ ├── entities/ # Entity, Mob, Player, etc.
│ ├── gfx/ # Colours, Font, Screen, etc.
│ ├── level/ # Level logic and tiles
│ ├── net/ # Networking (client, server, packets)
│ ├── Game.java
│ ├── GameLauncher.java
│ └── InputHandler.java
├── res/
│ ├── levels/ # Level images
│ └── sprite_sheet.png # Spritesheet for graphics
├── LICENSE
└── README.md
```

## 🛠️ Technologies Used

- **Java**: Core language for engine and game logic
- **Custom Graphics**: Manual pixel manipulation and rendering
- **Basic Networking**: Java Sockets for multiplayer

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