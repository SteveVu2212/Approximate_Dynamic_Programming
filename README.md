# Approximate_Dynamic_Programming

## Authors

Farias, V., Saure, D., & Weintraub, G. Y. (2012). An approximate dynamic programming approach to solving dynamic oligopoly models. The RAND Journal of Economics, 43(2), 253-282.

Steve Vu

## Introduction

The project aims at replicating the approximate dynamic programming (ADP) approach, first introduced by Farias et al. (2012). The approach was designed to solve the fundamental issue of dynamic programming, the curse of dimensionality.

In the project, the ADP approach is applied to solve for the approximate Markov perfect equilibrium (MPE) in the context of dynamic oligopoly models. In the model, each firm is distinguished by an individual state at every point in time. The value of the individual state represents the firm's capacity. The industry state is a vector encoding the number of firms with each possible value of the individual state variable. Assuming its competitors follow a prescribed strategy, a given firm must, at each point in time, select an action to maximize its expected discounted profits. The firm's subsequent state is determined by its current individual state, its chosen action, and a random shock.

Let N and X denote the number of firms and individual states in the market. The curse of dimensionality is unfolded by the following measurement of the size of the state space.

$$
|X| \binom{N + |X| - 1}{N - 1}
$$

## Outcome

![](https://github.com/SteveVu2212/Approximate_Dynamic_Programming/blob/main/outcomes/investment%20function.png)

![](https://github.com/SteveVu2212/Approximate_Dynamic_Programming/blob/main/outcomes/value%20function.png)