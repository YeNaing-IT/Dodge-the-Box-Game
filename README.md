# 📦 Dodge the Box Game

**Dodge the Box Game** is a simple 2D arcade-style game developed in **Unity** where the player moves left and right to avoid falling boxes.

The objective is to survive for as long as possible by reacting quickly and dodging incoming obstacles.

This project was created to practice fundamental Unity concepts such as player movement, touch/mouse input, physics, collision detection, obstacle spawning, and C# scripting.

## 🎮 Gameplay

The player is positioned near the bottom of the screen while boxes fall from above.

Move the player to the **left or right** to avoid being hit by the falling boxes.

The longer you survive, the better your performance.

### Objective

- Move left and right
- Watch the falling boxes
- Avoid collisions
- Survive as long as possible

## ✨ Features

- 📦 Falling box obstacles
- 🏃 Left and right player movement
- 📱 Touch-based controls
- 🖱️ Mouse input support for testing
- 💥 Collision detection
- ⚙️ 2D physics
- 🎮 Simple arcade gameplay
- 💻 Gameplay logic written in C#

## 🛠️ Built With

- **Unity**
- **C#**
- **Unity 2D**
- **Rigidbody2D**
- **Collider2D**

## 🎮 Controls

| Action | Control |
|---|---|
| Move Left | Tap / Click the left side of the screen |
| Move Right | Tap / Click the right side of the screen |

The controls are designed to work well with both mouse input during development and touch input on mobile devices.

## 🧠 How the Game Works

The main gameplay loop is simple:

```text
Boxes Spawn
     ↓
Boxes Fall Down
     ↓
Player Moves Left / Right
     ↓
Avoid Collision
     ↓
Continue Surviving
```

If the player collides with a falling box, the game can detect the collision and trigger the appropriate game-over behaviour.

## 🧠 Unity Concepts Demonstrated

This project demonstrates several fundamental Unity concepts:

- `Rigidbody2D`
- `Collider2D`
- 2D physics
- Touch input
- Mouse input
- Player movement
- Collision detection
- Object spawning
- GameObject management
- C# scripting
- Basic mobile game controls

## 🎯 Game Design

The gameplay is intentionally simple and focuses on player reaction time.

The player must constantly observe the falling obstacles and decide whether to move left or right.

As the game becomes faster or more obstacles appear, the player needs quicker reactions to survive.
