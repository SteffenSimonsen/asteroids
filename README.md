# Asteroids Game

A classic Asteroids arcade game implementation in Python using Pygame.

## Features

- **Player Ship**: Triangle-shaped ship with rotation and thrust controls
- **Asteroids**: Randomly spawning asteroids that split when shot
- **Shooting**: Fire projectiles to destroy asteroids
- **Collision Detection**: Game over when player hits asteroid

## Controls

- **A/D**: Rotate ship left/right  
- **W/S**: Move forward/backward
- **Space**: Shoot

## Requirements

- Python 3.x
- Pygame 2.6.1

## Installation

```bash
pip install -r requirements.txt
```

## Run the Game

```bash
python main.py
```

## Game Mechanics

- Asteroids spawn from screen edges at random intervals
- Large asteroids split into smaller ones when shot
- Smallest asteroids are destroyed completely
- Player loses when colliding with any asteroid

Enjoy blasting asteroids! 🚀
