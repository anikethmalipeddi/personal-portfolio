# Personal portfolio

My homepage at [anikethmalipeddi.com](https://anikethmalipeddi.com), with a small pathfinding experiment built in JavaScript and WebGL. Canvas provides a fallback when WebGL is unavailable.

## Preview

```sh
python3 -m http.server 4173
```

Open http://localhost:4173. There are no build steps or package dependencies; the page loads its fonts from Google Fonts.

The experiment compares routes from A*, Dijkstra, Theta*, and RRT*. The animation is paced for readability, so it is not a speed benchmark. Focus the scene and use 1–2 to select dots or 3–6 to select objects, then move them with the arrow keys.

## Deploy

Hosted on Vercel as `anikethmalipeddi`, with automatic deployments from `main`. For a new deployment, use the Other framework preset and serve the repository root.
