# Taxi Fleet Simulator

A taxi fleet management simulator built in Python for the Artificial Intelligence course at the University of Minho. Real map data is loaded via OSMnx and NetworkX to model a city graph, where a fleet of taxis is dispatched to handle incoming ride requests using and comparing several graph search algorithms.

## Algorithms implemented

- DFS (Depth-First Search)
- BFS (Breadth-First Search)
- Greedy Best-First Search
- A\* (A-Star)
- Dijkstra

## Features

- Animated simulation with a graphical visualizer
- Benchmark mode to compare algorithm performance (path cost, execution time)
- Fleet analysis tool to compare taxi efficiency across routes
- Dynamic edge weights to simulate traffic conditions
- Request generator to simulate incoming ride demand

## Tech stack

Python, NetworkX, OSMnx, Matplotlib.

## Run locally

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python main.py
```

## Team

- Carlos Cunha
- David Sousa e Silva
- Francisco Maia
- Tomás Barroso Ramalhete
