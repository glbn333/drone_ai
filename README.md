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

## Project Structure

```bash
droneIA/
│
├── create_map.py        # Script to create and load the drone environment.
├── agent.py             # Defines the agent's (drone's) behavior.
├── main.py              # Main file to train the agent and run simulations.
├── environments/        # Folder containing environment maps.
├── results/             # Folder to store training results.
├── videos/              # Folder containing demo videos of the drone training.
├── requirements.txt     # Dependencies required for the project.
└── README.md            # Project documentation.


## How It Works

- **Environment Creation**: Users can generate 2D grid-based maps with obstacles. The agent (drone) navigates these maps.
- **Training the Drone**: The drone uses Q-Learning or SARSA to learn the optimal path over several iterations by maximizing cumulative rewards based on its actions.
- **Comparison**: Performance metrics, such as distance covered and learning efficiency, are compared between the algorithms (Q-Learning, SARSA, and Hybrid SARSA/Q-Learning).

## Results

- **Q-Learning** demonstrated the best performance, with a total distance covered of **137,979** cells in 1000 iterations.
- **Hybrid Algorithm** covered **224,402** cells, while **SARSA** covered **2,671,286** cells, indicating significantly slower convergence.

You can find the detailed analysis and results in the `results/` folder.

## Future Work

1. **Deep Q-Learning**: Implementing Deep Q-Learning to improve generalization in more complex environments and allow the agent to operate effectively in environments of larger dimensions.
2. **3D Environment**: Moving from a 2D to a 3D simulation to better represent real-world drone navigation challenges.
3. **Physical Implementation**: Implementing the algorithm on an actual drone for real-time obstacle avoidance, with dynamic obstacles and environment factors such as changing weather conditions.

## Demo Videos

- **Training at iteration 1**: [0loop.mp4](path-to-file)
- **After 1000 iterations with Q-Learning**: [qlearning1000loop.mp4](path-to-file)
- **After 1000 iterations with Hybrid SARSA/Q-Learning**: [hybrid1000loop.mp4](path-to-file)

