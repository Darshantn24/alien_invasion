# Alien Invasion

A 2D arcade shooting game built with Python and Pygame. Control a spaceship, shoot incoming aliens, earn points, and survive increasingly challenging levels.

## About the Project

Alien Invasion is a Python game project based on object-oriented programming and the Pygame library. It demonstrates game loops, keyboard input, sprite management, collision detection, scoring, and game-state management.

## Requirements

- Python 3.13 or a compatible version supported by your installed Pygame release
- Pygame 2.6.1

## Installation & Setup

1. Clone this repository:

   ```bash
   git clone YOUR_GITHUB_REPOSITORY_URL
   cd alien_invasion
   ```

2. Create a virtual environment:

   ```bash
   python -m venv .venv
   ```

3. Activate it on Windows PowerShell:

   ```powershell
   .\.venv\Scripts\Activate.ps1
   ```

4. Install dependencies:

   ```bash
   python -m pip install -r requirements.txt
   ```

5. Run the game:

   ```bash
   python alien_invasion.py
   ```

## How to Play

- Use the left and right arrow keys to move the ship.
- Use the spacebar to fire bullets.
- Use the game's start button to begin or restart, if supported by the current version.
- Shoot aliens to earn points and advance through levels.

*Update these controls to match the actual game implementation.*

## Project Structure

- `alien_invasion.py` — Main game controller and game loop.
- `settings.py` — Game configuration and difficulty settings.
- `ship.py` — Player spaceship behavior.
- `alien.py` — Alien behavior.
- `bullet.py` — Projectile behavior.
- `game_stats.py` — Score, level, and game-state tracking.
- `button.py` — Interactive button behavior.
- `images/` — Image assets used by the game.
- `requirements.txt` — Python dependency versions.
- `.gitignore` — Files and folders excluded from Git.

## License

Add a license if you decide to distribute the project publicly.
