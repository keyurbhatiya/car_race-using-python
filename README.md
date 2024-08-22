
# Racing Game

## Overview
This is a 2D top-down racing game built using Python and Pygame. The game allows the player to race against a computer-controlled car on a track. The game features multiple levels with increasing difficulty.

## Features
- **Player Control:** The player can control a car using the keyboard to navigate the track.
- **Computer AI:** A computer-controlled car follows a predefined path on the track.
- **Multiple Levels:** The game consists of 10 levels, each with increasing difficulty.
- **Collision Detection:** The game includes collision detection with the track border and a finish line.
- **Dynamic Speed:** Both player and computer cars have adjustable speed depending on the level.
- **Simple UI:** Display of current level, time elapsed, and player velocity.

## Installation

### Requirements
- Python 3.x
- Pygame

### Installation Steps
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/racing-game.git
   cd racing-game
   ```

2. **Install Pygame:**
   If you don't have Pygame installed, you can install it via pip:
   ```bash
   pip install pygame
   ```

3. **Run the Game:**
   ```bash
   python main.py
   ```

## Game Controls
- **W:** Accelerate forward
- **S:** Move backward
- **A (Left Arrow):** Turn left
- **D (Right Arrow):** Turn right

## File Structure
```
racing-game/
│
├── imgs/                  # Game assets (images)
│   ├── grass.jpg
│   ├── track.png
│   ├── track-border.png
│   ├── finish.png
│   ├── red-car.png
│   └── green-car.png
│
├── utils.py               # Utility functions for the game
├── main.py                # Main game code
└── README.md              # Project documentation
```

## Game Assets
The `imgs` folder contains all the necessary images for the game. Ensure these files are in place:
- `grass.jpg`: Background grass image
- `track.png`: The main racing track
- `track-border.png`: The track border for collision detection
- `finish.png`: The finish line image
- `red-car.png`: The player's car
- `green-car.png`: The computer's car

## How to Play
- **Starting the Game:** Run the game and press any key to start the first level.
- **Goal:** Reach the finish line before the computer car does. If you collide with the track border, your car will bounce back. Avoid collisions and complete the race as quickly as possible.
- **Advancing Levels:** Each time you finish a race, you'll advance to the next level, with the computer car getting slightly faster.

