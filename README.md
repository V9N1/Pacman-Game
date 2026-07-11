**Pac‑Man Game**
A browser‑based Pac‑Man implementation developed using HTML, CSS, and JavaScript. The project is contained within a single file, making it easy to run, share, and extend. It includes multiple AI modes, adjustable difficulty settings, configurable ghost behavior, and optional audio and speech feedback.

**Features**
Difficulty Levels
The game provides three difficulty options—Easy, Medium, and High—each modifying core gameplay parameters such as:

Player and ghost movement speed

Scoring multipliers

Power pellet duration

Maze layout complexity

**Pac‑Man AI Modes**
Several AI modes are available for automated gameplay or experimentation:

Random

Dot‑seeking

Ghost‑avoiding

A\* pathfinding

Rule‑based (default)

Reinforcement learning (placeholder)

Ghost Configuration
Users may select between 1 and 5 ghosts, each represented by classic character names:
Blinky, Pinky, Inky, Clyde, and Sue.

****Core Gameplay Elements****
Classic maze layouts tailored to difficulty

Power pellets enabling temporary ghost capture

On‑screen score and status indicators

Start, win, and loss overlays

Basic sound effects via AudioContext

Optional speech output using speechSynthesis

Keyboard controls: Arrow keys, WASD, and R to restart

****How to Run****
Save the game file as pacman.html.

Place it in a folder (e.g., pacman-game/).

Open pacman.html in any modern browser (Chrome, Firefox, Edge, etc.).

Use the interface controls to adjust:

Difficulty

AI mode

Ghost count

Begin playing using keyboard controls.

****Project Structure****
Code
pacman-game/
  pacman.html      # Main game file (HTML, CSS, and JavaScript)
  README.md        # Project documentation
  .gitignore       # Git ignore rules
All game logic is contained within pacman.html, ensuring a minimal and portable project structure.

****Future Enhancements****
Potential improvements include:

AI Development
Full implementation of dot‑seeking using A* or Dijkstra

Enhanced ghost‑avoidance logic

A functional reinforcement learning agent (e.g., Q‑learning or a lightweight neural network)

Gameplay Data Collection
Logging moves, scores, and outcomes to CSV

Comparative analysis of AI modes and difficulty settings

****Training Interface****
A dedicated UI for reinforcement learning experiments

Visualization of learning progress (e.g., score trends over time)

****License****
This project is provided as‑is for educational and personal use. You may modify and distribute it under your preferred terms.
