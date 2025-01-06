# Match-3 Game (SFML)

This is a simple **Match-3 Game** implemented using the **SFML (Simple and Fast Multimedia Library)** in C++. The game involves matching similar colored gems on a 2D grid, with the goal of swapping gems to form matching sets of three or more.

## Project Overview

The game uses SFML to render a grid of gems and allows the player to click and swap gems to form matches. When a match is formed, the gems disappear, and new gems fall from the top to fill in the gaps. The game keeps track of the player's score and updates it based on the number of matches made.

### Key Features:
- Swap adjacent gems to form matches.
- Grid-based gameplay (8x8 grid).
- Animation for gem movement and disappearing after a match.
- Simple scoring system.
- Basic visual effects (gems and background).

## Issue Solved

This project solves the challenge of implementing a simple puzzle game, allowing users to interact with a 2D grid, swap items, and visualize the changes. It demonstrates handling grid-based logic, animations, and UI elements in C++ using SFML.

## Libraries/Packages

- **SFML**: For handling graphics, window creation, input handling, and multimedia.
- **C++ Standard Library**: For general-purpose functionality like random number generation, time handling, etc.

## Instructions to Run the Code

1. **Dependencies**:
   - Install SFML. Follow the official [SFML installation guide](https://www.sfml-dev.org/tutorials/2.5/).
   - Ensure you have a C++ compiler that supports C++11 or later.

2. **Setup**:
   - Download or clone this repository to your local machine.
   - Place the following assets in the respective directories:
     - `images/background.png`: The background texture.
     - `images/gems.png`: A sprite sheet of the gems (used for the grid).
     - `arial.ttf`: A font for displaying the score.

3. **Building**:
   - Compile the source code using a C++ compiler.
   - Link against the SFML libraries (Graphics, Window, and System).

4. **Running**:
   - Execute the compiled program, and the game window will open, allowing you to play the Match-3 game.

## Screenshots

![Game Screenshot](images/screenshot1.png)
*Game with gems on the grid.*

![Score Display](images/screenshot2.png)
*Updated score display after a match is made.*

## Improvements and Outcomes:
- **Animations** for gem movement and match removal.
- **Grid management** that ensures newly matched gems are replaced correctly.
- **Swap logic** to allow interaction between adjacent gems and detect matches.

---

**Enjoy the Game!**
