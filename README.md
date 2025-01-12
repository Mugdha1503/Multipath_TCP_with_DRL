This project implements a Deep Reinforcement Learning-based MPTCP scheduler. Using deep reinforcement learning (DRL) techniques, a neural network is trained only
via experience to develop the control strategy for packet scheduling. It uses a full reward function that schedules packets by taking into account the round-trip time,
congestion window, and in-flight packets. 
3 such DRL algorithms, Soft Actor-Critic (SAC), MAML, and RL2 are implemented for this application because of their ability to manage continuous 
operations (such as regulating packet flow rates) and optimize efficiency while
balancing exploration and exploitation using an entropy term.
