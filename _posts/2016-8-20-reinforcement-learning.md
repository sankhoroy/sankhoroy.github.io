---
layout: post
title: Reinforcement Learning
description: Basic Q Learning
image: assets/images/q-learning.png
redirect_url: https://github.com/sankhoroy/Q-Learinng
---

# Maze finding problem solved with Q-Learning (RL)
**Scenario:**
In this walk-through, we’ll use Q-learning to find the shortest path between two areas. It has the ability to embark on a journey with no knowledge of what to do next. This approach requires constant trial and error as it collects data about its surroundings and figures out how to accomplish its goal. This opens up interesting possibilities, what about recording additional information, like environmental details along the way that it may not fully understand until after it reaches its goal? And once reached, could it review that additional data to determine if any of it would have helped it reach its goal faster? 

**Algorithm :**
- Q-learning is a model-free reinforcement learning technique. 

- We create a points-list map that represents each direction our bot can take

- A best path exists and can be found easily regardless of the initial condition. Furthemore, the maze is time invariant. These nice theoretical hypothesis are usually not true when dealing when real world problems and this makes using Q-learning hard in practice, even though the concept behind it is relatively simple.


