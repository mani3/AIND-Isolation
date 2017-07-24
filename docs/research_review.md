# Research Review

- [AlphaGo](https://storage.googleapis.com/deepmind-media/alphago/AlphaGoNaturePaper.pdf) by the DeepMind Team.

## Summary

AlphaGo is a game AI for Go. AlphaGo uses a combination of `value networks`, `policy networks` and Monte Carlo tree search as a evoluation function. `value networks` is a network that evaluates the board of the Go and evaluates which player is winning. `policy networkds` is the best choice network and will evaluate which selection is best in this state of the Go. Using Monte Carlo tree search, simulation of random selection is performed, and evaluation functions of value networks and policy networks are used. The neural network of these two networks first supervised learning, and then reinforcement learning is performed.
