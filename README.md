# Reinforcement-Learning
Assignment description: The overall aim of the three assignments of the course is to create a robot that can do groceries by itself. To that end, it is important that your robot can learn how to optimally navigate the supermarket, for example to a product or to the cash register. In this assignment, you will help the robot learn a route based on rewards. The supermarket will be modeled as a maze where the target location yields a positive reward. Your robot will learn to navigate from a fixed starting point to this rewarded target through many rounds of exploration. 
	
For this assignment, we implemented 2 different model-free Reinforcement Learning algorithms: Q-Learning (off-policy) and SARSA (on-policy). Combining with the 3 different exploration strategies we implemented, we analyzed the best set of hyperparameters for this specific task, and we also showed that by modifying the discount factor γ, we can regulate how much of the reward signal is propagated and manipulate the robot to go to some other terminals. 

The Jupyter notebook is in /Assignment 3/src/Main.ipynb
