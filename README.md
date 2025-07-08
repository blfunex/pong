# [PONG](https://blfunex.github.io/pong/)

A clone of the classic arcade game PONG, built using the HTML5 Canvas API and TypeScript.

This is a single-player implementation where the user controls the right paddle with the mouse. The left paddle is controlled by an AI whose responsiveness dynamically increases as its score gets higher. The game ends when one player reaches a score of 10.

## Roadmap

This project is a complete implementation of a basic PONG game. The following is a list of potential features and improvements for future development.

### Features & Improvements

- [x] **Basic Pong Gameplay**
  - [x] Added left CPU paddle that moves automatically based on the ball's position.
  - [x] Implemented ball movement and collision detection with paddles and walls.
  - [x] Scoring system that tracks player and AI scores.
  - [x] Game over condition when one player reaches a predefined score.
- [x] **Basic "Game Loop"**
  - [x] Player can restart after game over by clicking.

### Core Gameplay Enhancements

- [ ] **Implement Sound Effects**
  - [ ] Sound for ball hitting a paddle
  - [ ] Sound for ball hitting a wall
  - [ ] Sound for scoring a point
- [ ] **Add New Game Modes**
  - [ ] Two-Player mode (local keyboard controls for both paddles)
  - [ ] "Wall" practice mode (single player hitting a ball against a wall)
- [ ] **Introduce Power-ups**
  - [ ] Multi-ball event
  - [ ] Temporary speed boost/slow for the ball
  - [ ] Temporary size increase/decrease for the paddle

### UI & Player Experience

- [ ] **Create a Main Menu / Start Screen**
  - [ ] Include a "Start Game" button
  - [ ] Add a difficulty selection for the AI (e.g., Easy, Medium, Hard)
- [ ] **Implement a Pause Menu**
  - [ ] Allow the player to pause and resume the game (e.g., with the `P` or `Escape` key)
- [ ] **Add More Input Options**
  - [ ] Full keyboard controls for player paddle movement (`W`/`S` or Arrow Keys)
- [ ] **Add Game Configuration Options**
  - [ ] Allow players to set the winning score
  - [ ] Add options to change the color theme of the game

### Visual Polish ("Juice")

- [ ] **Add Particle Effects**
  - [ ] Sparks on ball/paddle collision
  - [ ] A subtle trail renderer behind the ball

### Technical & Code Quality

- [ ] **Refactor Input Handling**
  - [ ] Create a centralized `InputManager` class to handle all keyboard/mouse events, decoupling it from game objects.
- [ ] **Better code organization**
  - [ ] Create a game loop manager to handle the game state and timing.
  - [ ] Create a rendering toolkit to manage canvas rendering and animations.
  - [ ] Extract utility functions into a separate module for better organization.
