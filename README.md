# Noughts And Crosses (Android)

A Noughts and Crosses (Tic-Tac-Toe) game for Android, written in Java.

## Features
- Play as O against the computer (X)
- Three difficulty levels:
  - **Easy**: random moves
  - **Medium**: wins or blocks when it can, otherwise random
  - **Hard**: unbeatable minimax AI
- Scoreboard for wins, losses and draws, saved between sessions
- The starting player alternates each game
- Winning line highlight and move animations
- Game state survives configuration changes

## Project structure
- `GameEngine.java`: game rules and AI, with no Android code
- `MainActivity.java`: UI and game flow
- `res/`: layout, colors, strings and drawables

## Requirements
- Android Studio
- minSdk 24

## Run
Open the project in Android Studio, let Gradle sync, then press Run.
