# Simple Autonomous Driving in CARLA

This project aims to develop a simple autonomous driving system for the CARLA simulator using deep reinforcement learning.

## Abstract

Autonomous driving is an emerging technology that promises to revolutionize the way we commute. In this project, we develop a simple autonomous driving 
system for the CARLA simulator using deep reinforcement learning. The system is trained to navigate the environment and avoid obstacles while following the 
rules of the road. The effectiveness of the system is evaluated using metrics such as success rate, average speed, and distance traveled.

## Description

The repository contains the code for the following tasks:

* Setting up the CARLA simulator
* Creating the environment and agent
* Training the agent using deep reinforcement learning
* Evaluating the performance of the agent

The CARLA simulator provides a realistic 3D environment for testing autonomous driving systems. We use the simulator to create an environment for the agent to navigate. The agent is trained using deep reinforcement learning techniques such as Q-learning and deep neural networks. The trained agent is then evaluated on its ability to navigate the environment and avoid obstacles.

## Results

The results of the trained agent's performance are presented in the following chart:

![Training Performance](./images/training_performance.png)

As you can see, the trained agent achieves high success rates and travels a significant distance while avoiding obstacles.

## Conclusion

In conclusion, this project demonstrates the effectiveness of using deep reinforcement learning for autonomous driving in the CARLA simulator. The trained agent is able to navigate the environment and avoid obstacles while following the rules of the road.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository: `git clone https://github.com/username/repo.git`
2. Install the required packages: `pip install -r requirements.txt`
3. Set up the CARLA simulator: `python setup_carla.py`
4. Create the environment and agent: `python create_environment.py`
5. Train the agent: `python train_agent.py`
6. Evaluate the agent: `python evaluate_agent.py`

## Credits

This project was developed by [Your Name](https://github.com/username).

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
