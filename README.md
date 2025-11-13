# graph-algorithm-in-real-life-application

This repo contains Python implementations for four graph problems:

Social Network Friend Suggestion — BFS (friends of friends)
Route Finding (Google Maps) — Bellman-Ford (handles negative weights)
Emergency Response Route — Dijkstra (positive weights, min-heap)
Network Cable Installation — MST using Kruskal & Prim
Files:

graph_realworld.py # main implementations + demos
requirements.txt # optional extra libraries
How to run: $ python graph_realworld.py

Profiling:

The code measures execution time (time.perf_counter) and memory usage (tracemalloc snapshots).
For more detailed memory profiling, install memory_profiler and use as desired.
Author: Debasmita Palai
