# CSE-676-Final-Project
This repository contains code for the final Project for CSE-676 , Spring 2023. 
The implementation is that of a complete Behavioral Cloning Agent pipeline using OpenAI Gym's CartPole environment. A basic DQN agent first collects experiences using a Random Policy and then learns a policy from a Deep Q-Network. Using this policy, the agent then reinteracts with the environment to collect a fresh set of experiences.
These experiences are used to train a Behavioral Cloning Agent. Once trained, the behavioral Cloning Agent then uses this policy to interract with the environment and it's rewards are then recorded.
The code can be run from the Notebook above.
