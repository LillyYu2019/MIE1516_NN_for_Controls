# MIE1516_NN_for_Controls

For the control of complex non-linear systems for which there are no analytical design techniques, a neural net can be used to implement highly non-linear controllers with internal parameters that can be determined through a learning process. This control method has the benefit of a “black-box” method, where there is no need to determine the analytical model of the system, and there is no need to tune control parameters.

This project investigate the use of four different type of neural network and reinforcemnt learning algorithms that can be used for non-linear controls on the CartPole system on the OpenAI GYM.

The four architecture were investigate:

**Reinforcement Learning:**
1. Tabular Q learning with greedy epsilon strategy 

<br>

**Neural Net Controls:**

2. 4 Layers Fully Connected 
3. One directional RNN
4. One directional LSTM 

## CartPole Simulation Environment Overview 
- **Reference:** GitHub. (2019). openai/gym. [online] Available at: https://github.com/openai/gym/wiki/CartPole-v0 [Accessed 28 Mar. 2019].
- OpenAI Gym, Greg Brockman and Vicki Cheung and Ludwig Pettersson and Jonas Schneider and John Schulman and Jie Tang and Wojciech Zaremba 2016 

**Details**
* Name: CartPole-v0  
* Category: Classic Control
* [Leaderboard Page](https://github.com/openai/gym/wiki/Leaderboard#cartpole-v0)
* Old links:
  * [Environment Page](https://gym.openai.com/envs/CartPole-v0)  
  * [Algorithms Page](https://gym.openai.com/algorithms?groups=classic_control)

**Description**
A pole is attached by an un-actuated joint to a cart, which moves along a frictionless track. The pendulum starts upright, and the goal is to prevent it from falling over by increasing and reducing the cart's velocity.

## File Description:

- Controller_Demo: Contrains recorded videos of the controller in action over the rendered environment
- Models: Contain saved model trained in this project
- Q-learning.ipynb: Define and train a Q learning algorithm
- System identification.ipynb: Define and train two NN model to emulate the Cart and Pole system
- Final Report - Controller Training.ipynb: Final report containing controller model definition and training

## Reference:
- GitHub. (2019). openai/gym. [online] Available at: https://github.com/openai/gym/wiki/CartPole-v0 [Accessed 28 Mar. 2019].
- OpenAI Gym, Greg Brockman and Vicki Cheung and Ludwig Pettersson and Jonas Schneider and John Schulman and Jie Tang and Wojciech Zaremba 2016 
- Conyngham, P. (2018). Rendering OpenAi Gym in Google Colaboratory. [Blog] StarAI Applied Research Blog. Available at: https://star-ai.github.io/Rendering-OpenAi-Gym-in-Colaboratory/ [Accessed 26 Mar. 2019].
-   Phil Tabor, OpenAI-Cartpole, (2017), GitHub repository, https://github.com/philtabor/OpenAI-Cartpole
