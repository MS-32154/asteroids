# Asteroids

A classic Asteroids game implementation built with Python and Pygame.

## Features

- Classic arcade-style gameplay
- Asteroid splitting mechanics
- Continuous asteroid spawning
- Collision detection
- Game state and event logging

## Requirements

- Python 3.13+
- Pygame 2.6.1

## Installation

```bash
# Install dependencies
pip install -r requirements.txt

# Or using uv
uv sync
```

## How to Play

```bash
python main.py
```

### Controls

- **W/S** - Move forward/backward
- **A/D** - Rotate left/right
- **Space** - Shoot

### Objective

Destroy asteroids while avoiding collisions. When shot, larger asteroids split into smaller ones.

## Project Structure

- `main.py` - Game loop and collision detection
- `player.py` - Player ship controls
- `asteroid.py` - Asteroid behavior and splitting logic
- `asteroidfield.py` - Asteroid spawning system
- `shot.py` - Projectile mechanics
- `circleshape.py` - Base class for game objects
- `logger.py` - Game state and event logging

## Development

This project was built as part of the Boot.dev curriculum.

Game state snapshots and events are logged to `game_state.jsonl` and `game_events.jsonl` for analysis.