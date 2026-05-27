# Snake Game in Java

A classic Snake Game developed using Java Swing and AWT.  
This project recreates the traditional Snake arcade game where the player controls a snake, collects apples, grows in length, and avoids collisions with walls and itself.

---

## Description

This Snake Game is built with Java Swing for the graphical interface and uses keyboard controls for movement.

### Gameplay Features

- Smooth snake movement
- Random apple spawning
- Snake growth after eating apples
- Collision detection
- Game Over screen
- Simple sprite-based graphics
- Real-time game loop using Swing Timer

The project is beginner-friendly and demonstrates:

- Java OOP concepts
- Event handling
- Swing graphics rendering
- Keyboard listeners
- Timers and animation loops

---

## Project Structure

```text
SnakeGame/
│
├── src/
│   ├── com/
│   │   └── zetcode/
│   │       ├── Snake.java
│   │       └── Board.java
│   │
│   └── resources/
│       ├── apple.png
│       ├── dot.png
│       └── head.png
│
├── Screenshot (2).png
├── snake_game.mp4
└── README.md
```

---

## Technologies Used

- Java
- Java Swing
- AWT Graphics

---

## How to Run

### Step 1 — Clone the Repository

```bash
git clone https://github.com/vishnuvardhan-14/snake-game-using-java.git
```

---

### Step 2 — Open the Project

Open the project in any Java IDE:

- IntelliJ IDEA
- Eclipse
- NetBeans
- VS Code

---

### Step 3 — Compile the Project

Navigate to the `src` directory and compile:

```bash
javac com/zetcode/*.java
```

---

### Step 4 — Run the Game

```bash
java com.zetcode.Snake
```

---

## Controls

| Key | Action |
|------|--------|
| ↑ | Move Up |
| ↓ | Move Down |
| ← | Move Left |
| → | Move Right |

---

## Code Overview

### Snake.java

Responsible for:

- Creating the game window
- Launching the application
- Initializing the board

### Board.java

Handles:

- Snake movement
- Apple spawning
- Collision detection
- Keyboard input
- Rendering graphics
- Game loop timing

---

## Resources

Place these images inside:

```text
src/resources/
```

Required assets:

- `apple.png`
- `dot.png`
- `head.png`

---

## Outcomes

By building this project, you will learn:

- How to build GUI applications using Java Swing
- How game loops work using Swing Timer
- Event-driven programming in Java
- Keyboard input handling
- Collision detection techniques
- Basic 2D game development concepts
- Object-Oriented Programming in Java

---

## Screenshot

![Snake Game Screenshot](Screenshot%20(2).png)

---

## Gameplay Video

[▶ Watch Gameplay Video](snake_game.mp4)

---

## Author

GitHub: https://github.com/vishnuvardhan-14
