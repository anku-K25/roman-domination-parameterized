# Parameterized Algorithms for Roman Domination

## Overview
This repository contains experimental Python implementations supporting my research on **Roman Domination** algorithms for restricted graph classes. The primary focus is analyzing the computational bottleneck at "Join Nodes" in standard tree decompositions, as identified in *Fernau et al. (2008)*.

## Research Context
Standard dynamic programming for Roman Domination operates in $\mathcal{O}(5^{tw})$ time on chordal graphs. My current research explores replacing **Treewidth (tw)** with **Distance to Block Graph** as the structural parameter to reduce the state space complexity at join nodes.

## Current Modules
- **`main.py`**: Includes utility functions for:
  - Generating random chordal graph structures.
  - Verifying chordality properties using `networkx`.
  - Approximating treewidth to benchmark structural complexity.

## Roadmap
- [x] Basic structural verification for Chordal Graphs.
- [ ] Implementation of the Roman $\{i,j\}$-dominating function.
- [ ] Benchmarking state-space size: Treewidth vs. Block Graph Distance.

## Dependencies
- Python 3.8+
- NetworkX
- Matplotlib
