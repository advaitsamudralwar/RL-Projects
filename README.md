# Reinforcement Learning

****Deterministic and Stochastic Gym Environment****

Create deterministic and stochistic enviroment for reinforcement learning.

****Q-Learning****

Implemention uses Frozen Lake Gym Env. 

Action Space
The agent takes a 1-element vector for actions. The action space is (dir), where dir decides direction to move in which can be:

0: LEFT
1: DOWN
2: RIGHT
3: UP

Observation Space
The observation is a value representing the agent’s current position as current_row * nrows + current_col (where both the row and col start at 0). For example, the goal position in the 4x4 map can be calculated as follows: 3 * 4 + 3 = 15. The number of possible observations is dependent on the size of the map. For example, the 4x4 map has 16 possible observations.

Rewards:
Reach goal(G): +1
Reach hole(H): 0
Reach frozen(F): 0





