# HybridZero

A hybrid approach combining AlphaZero's deep reinforcement learning with heuristic methods for enhanced performance in various environments.

## Overview
This project explores the integration of traditional heuristic search methods with modern deep reinforcement learning approaches, specifically AlphaZero's architecture, to create more efficient and robust solutions for different control and planning problems.

## Projects

### CartPole-AlphaZero
Implementation of the AlphaZero algorithm to control the CartPole environment from Gymnasium.

**Features:**
* Deep neural network for policy and value prediction
* Monte Carlo Tree Search (MCTS) for action selection
* Training pipeline adapted for the CartPole environment

### FrozenLake-HeuristicGBFS
A Greedy Best-First Search (GBFS) agent for the FrozenLake environment, enhanced with neural network predictions.

**Features:**
* Hybrid heuristic function: `H(s) = V(s) + SimulationResult(s)`
* Neural network value predictions
* Forward simulation for improved state evaluation
* Priority-based exploration using GBFS

## Future Developments
- [ ] Additional environments
- [ ] More hybrid approaches
- [ ] Performance comparisons
- [ ] Extended documentation

## Contributing
Feel free to contribute or suggest new environments for testing this hybrid approach.

## License
[To be added]
