
# Rummy Game with Monte Carlo Tree Search (ISMCTS) - INFO6205 Final Project

This project implements a simplified Rummy game with decision-making powered by **Information Set Monte Carlo Tree Search (ISMCTS)**, designed for a **Data Structures and Algorithms** course. The goal is to simulate intelligent move planning without relying on a full AI system.

## 📚 Project Structure

The system is modularized into three main components:

### 1. **MonteCarloLogic**
Contains the core ISMCTS algorithm responsible for simulating possible moves and selecting the most promising one based on statistical evaluations.

- `ISMCTS`: Runs the ISMCTS simulations.
- `Node`: Represents a node in the MCTS tree.
- `AIArrayList`: Custom array list structure optimized for MCTS.
- `PerformanceTester`: Evaluates different iteration levels for performance comparison.

### 2. **Domain**
Represents the game logic and data structures.

- `State`: Maintains the current state of the game.
- `Player`, `Card`, `Suit`: Core entities in the game.
- `Move classes`: Define the types of actions players can take.
- `Meld classes`, `Layoff`: Handle meld combinations and additional moves.

### 3. **UI**
A simple user interface for observing gameplay between players and the Monte Carlo-based logic.
- `AIvsAI_UI`: Visualizes gameplay and simulations.

### 4. **Game Entrypoint**
- `PlayGame`: The main class that sets up and initiates the game.
