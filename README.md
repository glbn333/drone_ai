# DroneIA: Application of Reinforcement Learning Algorithms for Obstacle Avoidance in Drones

This repository contains the final project on applying reinforcement learning algorithms for autonomous drone navigation and obstacle avoidance.

## Project Overview

### Abstract
The aim of this project is to leverage reinforcement learning algorithms, specifically **Q-Learning** and **SARSA**, to plan an optimal path for drones navigating through complex environments. The goal is to avoid collisions while finding the most efficient route. The Q-Learning algorithm has proven to outperform SARSA in terms of distance covered and learning efficiency.

### Features
- **2D environment simulation** for drone navigation.
- **Q-Learning and SARSA algorithms** implemented for obstacle avoidance.
- **Customizable environment creation** using Python’s Pygame library.
- **Performance comparison** between algorithms based on distance covered and efficiency.
- Hybrid SARSA/Q-Learning algorithm.

### Technologies Used
- **Python**: Core programming language.
- **Pygame**: For 2D environment simulation and rendering.
- **Numpy**: For mathematical calculations.
- **OpenAI Gym**: To manage the drone’s interaction with the environment.
- **Pickle**: For saving and loading environment data.
  
## Installation Instructions

To set up and run the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/glbn333/drone_ai.git
   cd drone_ai
