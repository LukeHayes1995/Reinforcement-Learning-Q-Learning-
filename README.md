# Reinforcement-Learning-Q-Learning
Part 1: Create the FrozenLake. 
a) Using Python, create a 5x5 grid sized FrozenLake, with a start state at the top left corner and
a goal state at the bottom right corner.
b) Place four holes at the following grid positions in the FrozenLake. (1,0), (1,3), (3,1), (4,2)
c) The reward for reaching the goal state is +10.0. The reward for falling into a hole is -5.0
(because you die!) and the rewards for each transition to a non-terminal state is -1.0.
d) The episode ends if the agent falls into a hole or reaches the goal state.
e) The actions are “up”, “down”, “left” and “right”.

Part 2: Implement the Reinforcement Learning algorithm Q-learning
a) Using the algorithmic steps outlined in the notes (Week 9 – Model Free Learning (Temporal
Difference Learning)) (or S&B book), implement Q-learning on the FrozenLake problem to
learn a policy which can navigate optimally through the lake.
b) Set the parameters Alpha = 0.5, Gamma = 0.9, and Epsilon = 0.10
c) Run the frozen lake experiment for 10000 episodes and output the action value estimates at
the end of the learning process.
d) Plot a curve of the reward per episode (similar to what was depicted in the slides for the cliff
walking task Q-learning vs SARSA). 
