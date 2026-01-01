# dynamic-graph-summaries
Minimal experiments on graph summaries and regime detection in dynamic graphs.
# Dynamic Graph Summaries (Minimal Experiments)

This repository explores how different graph-level summaries behave
under temporal evolution and structural regime changes.

## Core Question
Which graph summaries behave like system-level state variables
in dynamic, non-stationary graph systems?

## Experiment
- System: Streaming graph with a structural regime change
- Summaries:
  - Average degree
  - Clustering coefficient
  - Algebraic connectivity (λ₂)

The summaries respond differently despite identical underlying dynamics.

## Files
- `` — main Colab notebook
- `figures/` — output plots (if any)

## Status
Exploratory and diagnostic.
Serves as groundwork for further task-based analysis.
