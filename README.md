# Asteroids

A classic arcade-style game where you pilot a spaceship to destroy asteroids and survive waves of increasing difficulty.

## Features

- **Spaceship Control**: Rotate, accelerate, and fire weapons
- **Asteroid Physics**: Realistic trajectory and collision detection
- **Progressive Difficulty**: Waves increase in challenge
- **Score Tracking**: Track your high score

## Getting Started

### Prerequisites

- Python 3.8+
- Pygame

### Installation

```bash
git clone <repository-url>
cd Asteroids
pip install -r requirements.txt
```

### Running the Game

```bash
python main.py
```

## Controls

- **Arrow Keys**: Rotate and thrust
- **Spacebar**: Fire
- **ESC**: Quit

## How to Play

1. Destroy all asteroids on screen to advance
2. Avoid collisions with asteroids and enemies
3. Survive as long as possible for high scores

## Project Structure

```
├── main.py
├── game/
│   ├── player.py
│   ├── asteroid.py
│   └── collision.py
├── requirements.txt
└── README.md
```

## License

MIT License
