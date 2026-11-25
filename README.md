# Neon Hunt Game

## Overview
Neon Hunt is a strategic grid-based game in which the player, known as the Hacker, must escape a neon-themed environment while avoiding the Cyber Beast, an adversarial monster controlled by the game. This project implements an intelligent game-playing agent in Python that makes strategic decisions using Minimax, Alpha-Beta Pruning, and Heuristic Evaluation.

The objective is to reach the exit safely or survive until the end of the level. The Hacker must make strategic decisions while the Cyber Beast attempts to intercept and capture the player.

This project focuses on developing an intelligent AI agent capable of making decisions autonomously by analyzing possible future game states and selecting optimal moves.

## Key Features
+ **Heuristic Evaluation**: Evaluates game states based on factors such as distance to the exit, proximity to the monster, and available escape routes.
+ **Minimax Algorithm**: Implements depth-limited adversarial search to select strategic moves by considering both the player's and the monster's decisions.
+ **Alpha-Beta Pruning**: Optimizes the Minimax search by eliminating branches that cannot influence the final decision.
+ **Intelligent Move Selection**: Evaluates legal player movements and selects the most promising action.
+ **Dynamic Decision-Making**: Makes decisions based on the current game state rather than relying on predefined movement paths.
+ **Search Statistics**: Tracks explored states and pruned branches to help analyze AI performance.

## Game Controls & Configuration
The game interface provides several options for configuring and testing the AI:

| Option | Description |
|--------|-------------|
| Player | Switches between Human and Student AI |
| Monster | Selects the monster difficulty: Easy, Normal, Hard, or Boss |
| Depth | Controls the search depth of the AI|
| Alpha-Beta | Enables or disables Alpha-Beta Pruning |
| Ghost Trail | Displays recent movement paths |
| Speed | Adjusts automatic gameplay speed |

The game also provides the following controls:
+ **STEP**: Executes one player move.
+ **ROUND**: Executes one complete round (player followed by monster).
+ **AUTO**: Runs the game automatically.
+ **RESET**: Restarts the current level.
+ **NEXT**: Proceeds to the next level.

## Requirements
+ Python 3.x

## Project Structure
```
├── neon_hunt/
│   ├── ai/
│   |   ├── __init__.py
│   |   ├── instructor_monster_ai.py
│   |   ├── student_player_ai.py
│   |   └── student_support.py
│   ├── assetes/
│   |   ├── characters/
│   |   ├── effects/
│   |   ├── obstacles/
│   |   ├── titles/
│   |   └── ui/
│   ├── __init__.py
│   ├── app.py
│   ├── config.py
│   ├── engine.py
│   ├── levels.py
│   └── state.py
├── main.py
├── run_linux.sh
├── run_windows.bat
├── .gitignore
└── README.md
```

## Course Information
+ **Course**: Fundamentals and Applications of Artificial Intelligence
+ **Instructor**: Dr. Marzieh Hosseini
+ **Teaching Assistants**: Marzieh Karami, Masih Roughani, Fatemeh Sayadzade
+ **Semester**: Spring 2026 (1404-1405)
+ **Department**: Faculty of Computer Engineering, University of Isfahan
