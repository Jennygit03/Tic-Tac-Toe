# Tic-Tac-Toe (C++ Console Game)

This is a simple console-based **Tic-Tac-Toe** game written in C++. It allows a human player to play against a basic computer opponent that makes random moves.

## How to Play
- The board is represented by a 3x3 grid with positions numbered 1 to 9.
- The player plays as `'X'`, and the computer plays as `'O'`.
- Players take turns placing their symbol on an empty spot.
- The game ends when either player wins or the board is full (tie).

## Features
- Simple terminal interface.
- Input validation (prevents choosing taken/invalid spots).
- Computer opponent with random move logic.
- Win and tie detection.

## Build & Run

### Requirements
- C++ compiler (e.g., `g++`)
- C++11 or later

### Compile
```bash
g++ -o tictactoe tictactoe.cpp
./tictactoe
