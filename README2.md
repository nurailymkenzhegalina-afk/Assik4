# Bonus Task — Dijkstra’s Algorithm

## Overview

As a bonus task, Dijkstra’s Algorithm was implemented to calculate the shortest path from a starting vertex to all other vertices in the graph.

The graph was extended to support weighted edges.

## Changes Made

- Added weight field to the Edge class
- Updated adjacency list to store weights
- Implemented dijkstra(start) method
- Generated random edge weights from 1 to 10

## How Dijkstra’s Algorithm Works

1. Start from the selected vertex
2. Set all distances to infinity
3. Set starting vertex distance to 0
4. Find the nearest unvisited vertex
5. Update distances to neighbors
6. Repeat until all vertices are visited

## Time Complexity

:contentReference[oaicite:1]{index=1}

This implementation uses simple loops instead of a priority queue.

## Use Cases

- GPS navigation systems
- Network routing
- Shortest path problems
- Transportation systems

## Screenshots

Add screenshots showing:

- Weighted graph structure
- Dijkstra output
- Shortest path results