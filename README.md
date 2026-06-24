# CarLeague

A physics-based 3D vehicle soccer game built in Unity — inspired by Rocket League.
Two players (or 1 vs AI) compete to score 3 goals first.

## Gameplay
- **Movement:** Realistic vehicle physics with inertia, weight, Boost and Dash
- **AI Opponent:** Actively seeks the ball and defends the goal
- **Match System:** First to 3 goals wins; auto-reset after each goal
- **Post-match:** Score summary and restart option

## Built With
- Unity 2022 / C#
- Custom scripts: `PlayerController`, `AIController`, `ScoreManager`, `ResetPlayers`, `MenuManager`
- External assets: vehicle models (Lightning Poly), stadium (Football Essentials)

## What I Implemented
- Vehicle physics controller with boost and dash mechanics
- AI behavior — ball tracking and goal defense logic
- Goal detection, score tracking, and automatic player reset
- UI system: main menu, pause menu, end-game screen

## How to Play
1. Clone the repo
2. Open in Unity 2022.3 LTS via Unity Hub
3. Open `MainScene` and press Play
