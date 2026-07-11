# Pacman-Game
A JavaScript Pac-Man game with multiple AI modes, difficulty levels, and configurable ghost count.
# Pac-Man Game

A single-file Pac-Man game built with HTML, CSS, and JavaScript. It features multiple AI modes, difficulty levels, adjustable ghost count, power pellets, sound effects, and optional speech feedback.

## Features

- Three difficulty levels: Easy, Medium, and High  
  - Different player and ghost speeds  
  - Different scoring multipliers and power durations
- Multiple Pac-Man AI modes:
  - Random
  - Dot-seeking
  - Ghost-avoiding
  - A* pathfinding
  - Rule-based (default)
  - Reinforcement learning (placeholder)
- Adjustable ghost count (1–5) with named ghosts: Blinky, Pinky, Inky, Clyde, Sue
- Classic maze layouts tailored to each difficulty
- Power pellets that temporarily let you capture ghosts
- On-screen score, status messages, and overlay for start/win/loss
- Basic sound effects using `AudioContext`
- Optional speech via `speechSynthesis`
- Keyboard controls: arrow keys or WASD to move, `R` to restart

## How to run

1. Save the game code as `pacman.html`.
2. Place `pacman.html` in a folder (e.g. `pacman-game`).
3. Open `pacman.html` in any modern browser (Chrome, Firefox, Edge, etc.).
4. Use the controls at the top to change:
   - Difficulty
   - AI mode
   - Ghost count
5. Use arrow keys or WASD to move.
6. Press `R` or click **Restart** to restart the game.

## Project structure

```text
pacman-game/
  pacman.html      # Main game file (HTML + CSS + JS)
  README.md        # This file
  .gitignore       # Git ignore rules
```

All game logic is contained in `pacman.html`, making it easy to run and share.

## Future enhancements

Possible improvements:

- Implement full AI modes:
  - Complete dot-seeking with A* or Dijkstra
  - Ghost-avoiding that biases movement away from nearest ghost
  - A reinforcement learning agent (e.g. Q-learning or small neural net)
- Collect gameplay data:
  - Log moves, scores, and outcomes to a CSV
  - Analyze which AI modes or difficulty settings lead to higher scores
- Add a simple training UI:
  - Let an RL agent play many games in the background
  - Visualize learning curves (score over time)

## License

This project is provided as-is for learning and personal use. You can modify and distribute it under your own terms.
