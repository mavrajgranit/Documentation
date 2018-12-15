# Goals(15.12.2018)
Before implementing Actor Critic I wanted to study Continuous Action Spaces first. I knew about MountainCar and chose it as my first test case, but it turned out that Vanilla Policy Gradients have a hard time solving it so I wanted to try an easier environment first(Pendulum). Currently I need to learn about PNN's in order to be able to solve Pendulum.

- **Study Probabilistic Neural Networks(PNN's) - needed for Gaussian Policies(Pendulum/MountainCarContinuous)** ![#f03c15](https://placehold.it/15/f03c15/000000?text=+)
  - According to http://proceedings.mlr.press/v70/chou17a/chou17a.pdf
  - Resources: Internet and http://www.personal.reading.ac.uk/~sis01xh/teaching/CY2D2/Pattern3.pdf
- **Solve Pendulum Policy Gradients** ![#f03c15](https://placehold.it/15/f03c15/000000?text=+)
- **Solve Pendulum DQN** ![#FF8C00](https://placehold.it/15/FF8C00/000000?text=+)
- **Solve MountainCar DDPG** ![#FFD700](https://placehold.it/15/FFD700/000000?text=+)
- **Solve MountainCarContinuous PG,DQN** ![#FFD700](https://placehold.it/15/FFD700/000000?text=+)
- **Solve CartPole ActorCritic** ![#f03c15](https://placehold.it/15/f03c15/000000?text=+)
- **Solve FrozenLake Stochastic** ![#87CEFA](https://placehold.it/15/87CEFA/000000?text=+)

Legend: ![#f03c15](https://placehold.it/15/f03c15/000000?text=+) (High Priority), ![#FF8C00](https://placehold.it/15/FF8C00/000000?text=+) (Mid Priority), ![#FFD700](https://placehold.it/15/FFD700/000000?text=+) (Low Priority), ![#87CEFA](https://placehold.it/15/87CEFA/000000?text=+) (Optional)

# Future
I will pick these up as I advance and solve other problems.

This is just a mindmapy kind of listing.

- Implement Prioritized Experience Replay
- Study TD(λ)
- Write a DQN-Library to be used for Gym(Pixel Input, RAM, ...)
- Study AC, A2C, A3C
- Study TRPO
- Study PPO
- Study DDPG
- Write a PG-Library to be used for Gym
- Study Dynamic Programming(Policy Evaluation, Policy Iteration, Value Iteration) and the Cross-Entropy Method
- Study RNNs
- Implement YOLO
- Try out some automatization with RNNs

# Done
## Goals(December 2018)
- Solve FrozenLake Deterministic
- Solve CartPole DQN, PG
- Solve MountainCar DQN, PG
