# Racer Game (Java)

A Java-based racer game featuring responsive keyboard controls, moving obstacles, and collectible items. The game is built using a modular object-oriented architecture with shared interfaces to ensure consistent collision handling and real-time updates.

---

## Demo (Gameplay Video)

- RacerGame! 2025-10-15 18-48-40.mp4  
  *(Upload this video to the repository or link a hosted version here for easy viewing.)*

---

## Features

- Responsive real-time player controls
- Moving obstacles with collision detection and response
- Collectible items (coins) to encourage interactive gameplay
- Tuned obstacle speed for fair and enjoyable difficulty
- Robust handling of edge cases to prevent unintended object behavior

---

## Project Structure (High-Level)

The project follows a clean object-oriented design with small, focused classes:

- **Car** – Player-controlled entity handling movement and input
- **Obstacle** – Moving hazards with collision behavior
- **Coin** – Collectible entity with collision behavior
- **Collidable (interface)** – Standardizes collision detection and response across all game objects
- **Updatable (interface)** – Enables frame-by-frame updates for dynamic objects

This structure improves maintainability and makes it easy to extend the game with new mechanics.

---

## Technologies & Concepts Demonstrated

- Java fundamentals (collections, input handling, basic geometry)
- Object-Oriented Programming (interfaces, encapsulation, modular design)
- Inner classes and lambda expressions
- Git and GitHub collaboration (commits, pushes, pulls, resolving merge issues)
- VS Code for development and debugging

---

## How to Run

### Option 1: Run in an IDE (Recommended)
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_RACERGAME_REPO.git
