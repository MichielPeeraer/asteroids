# Asteroids

Classic Asteroids game implemented in Python using Pygame.

## Features
- Player spaceship with rotation, movement, and shooting
- Asteroids that split when shot
- Collision detection and game over logic
- Simple, clean code structure

## Prerequisites
- Python 3.10+ (recommended: 3.12+)
- [Pygame](https://www.pygame.org/) (installed automatically via dependencies)
- Unix-like shell (e.g. bash, zsh) or compatible terminal

## Installation
1. Clone this repository:
	```sh
	git clone https://github.com/yourusername/asteroids.git
	cd asteroids
	```
2. (Optional) Create and activate a virtual environment:
	```sh
	python3 -m venv .venv
	source .venv/bin/activate
	```
3. Install dependencies:
	```sh
	pip install -r requirements.txt
	# or, if using pyproject.toml:
	pip install .
	```

## Running the Game
Run the main script:
```sh
python main.py
```

## Controls
- **W**: Thrust forward
- **A/D**: Rotate left/right
- **Space**: Shoot
- **Esc**: Quit

## Project Structure
- `main.py` — Game entry point
- `player.py` — Player spaceship logic
- `asteroid.py` — Asteroid logic
- `asteroidfield.py` — Asteroid spawning
- `shot.py` — Bullet logic
- `circleshape.py` — Base class for circular game objects
- `constants.py` — Game constants
- `logger.py` — Logging utilities

## License
MIT License. See LICENSE file for details.