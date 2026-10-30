# Aniketh Malipeddi — portfolio

Personal portfolio with a WebGL pathfinding experiment and a Canvas fallback. Built with HTML, CSS, and JavaScript; no build step or dependencies.

## Preview

Run `python3 -m http.server 4173` and visit http://localhost:4173.

## Deploy

Import this repository into Vercel with Framework Preset **Other**, no build command, and the repository root as the output directory. Commits to `main` deploy automatically once connected.

The experiment compares route lengths across A*, Dijkstra, Theta*, and RRT*. Animation budgets are intentionally paced and do not measure execution speed. Keyboard controls are described below the scene.
