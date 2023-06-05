# Console Hex interface with MCTS and Leaf Parallelization

## Overview
This repository contains an implementation of a [Monte Carlo Tree Search (MCTS)](Monte Carlo Tree Search (MCTS)) agent with optional [leaf parallelization](https://en.wikipedia.org/wiki/Monte_Carlo_tree_search#:~:text=Leaf%20parallelization) for the board game of [Hex](https://en.wikipedia.org/wiki/Hex_(board_game)) with a variable board size in a console interface with customizable MCTS hyperparameters using standard C++ 14 libraries. It supports the user playing against an MCTS agent, pitting 2 MCTS agents, or a mode where the user is responsible for the moves of both players. If the agent is used in single-threaded mode, it can output a detailed log of how a move is picked using each MCTS iteration.
