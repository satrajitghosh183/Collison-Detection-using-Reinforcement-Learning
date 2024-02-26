

# Robot Navigation with Deep Q-Learning

This repository contains code for training a robot car to navigate an environment using Deep Q-Learning. The robot car is trained to avoid obstacles and reach a goal position within the environment.

## Features

- Training of a robot car using Deep Q-Learning
- Obstacle avoidance and goal-reaching capabilities
- Display of the environment and the robot's path



![download (2)](https://github.com/satrajitghosh183/Collison-Detection-using-Reinforcement-Learning/assets/83156880/9d10eb0b-b666-434f-a9ba-f0cc1b9fb71a)
![download (1)](https://github.com/satrajitghosh183/Collison-Detection-using-Reinforcement-Learning/assets/83156880/52104a7d-6339-478b-af72-fdd76fc887ca)
![download](https://github.com/satrajitghosh183/Collison-Detection-using-Reinforcement-Learning/assets/83156880/802f2275-90f4-4366-acf8-69df430a7635)



## Installation

1. Clone this repository:

```
git clone https://github.com/your-username/robot-navigation.git
```

2. Install the required libraries:

```
pip install numpy matplotlib torch
```

## Usage

### Training the Robot Car

To train the robot car using Deep Q-Learning, run the `train.py` script:

```
python train.py
```

By default, this script will train the robot car for 1000 episodes. You can change the number of episodes by modifying the `num_episodes` variable in the script.

### Displaying the Environment

To display the environment and the robot's path, run the `display.py` script:

```
python display.py
```

This script will display the environment in the terminal and plot the robot's path using matplotlib.

## Environment

The environment is a grid with obstacles and a goal position. The robot car starts at a random position and must navigate around obstacles to reach the goal.

## Robot Car

The robot car is a simple class that has methods for moving forward, backward, turning left, and turning right. It also has methods for setting its position and radius.

## Deep Q-Learning

The Deep Q-Learning algorithm is implemented using a Deep Q-Network (DQN) that predicts Q-values for the robot's actions. The DQN is trained using the Adam optimizer and Mean Squared Error loss.

## Conclusion

This code base provides a simple implementation of Deep Q-Learning for robot navigation. With further improvements and optimizations, it could be extended to more complex environments and tasks.
