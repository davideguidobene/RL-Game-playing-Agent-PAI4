# PAI_Pr4_ReinforcementLearning
Project 4 for the course of Probabilistic Artificial Intelligence. Implemented a reinforcement learning (RL) algorithm for playing a variant of a game called “lunar lander”.

# HOW TO EXECUTE
1. Download Docker
2. To run from Linux
  $ bash runner.sh

# SHORT REPORT
The multilayer perceptron architecture is just a sequential neural network implemented in the function mlp (which takes as input the size of each layers, as well as the activation function for the hidden layers and the output function for the last layer).
The Actor class methods are just a simple interface to get logarithm of policy methods.
The Critic class mathods are used to store and get the trajectory and update its discounted rewards-to-go and TD residuals.
Finally, the Agent class methods are used to decide which action to take getting the policy from the actor&#39;s class and using the Critic&#39;s class neural network (implemented through the previously mentioned mlp function) to estimate the value function.

#REFERENCES
Schulman, J., Moritz, P., Levine, S., Jordan, M., & Abbeel, P. (2015). High-Dimensional Continuous Control Using Generalized Advantage Estimation. arXiv. https://doi.org/10.48550/arXiv.1506.02438
	  


