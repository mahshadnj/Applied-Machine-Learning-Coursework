# Homework 5 — Deep Learning and Reinforcement Learning

This assignment introduces neural networks, image classification,
and reinforcement learning using Python and PyTorch.

## Q2 — Feedforward Neural Network: Forward Pass and Gradients

Implement the computations of a small feedforward neural network
with one hidden layer.

Network architecture:
- 2 input neurons
- 3 hidden neurons with ReLU activation
- 1 output neuron with Sigmoid activation

Main tasks:
- Compute the forward pass
- Calculate the network output
- Compute RMSE for a given target
- Derive and calculate gradients for the output-layer weights and bias

Notebook: `Q2-feedforward-neural-network.ipynb`

---

## Q3 — CIFAR-10 Image Classification with an MLP

Build and train a fully connected neural network for CIFAR-10 image
classification using PyTorch.

Architecture:
- Input: 32 × 32 RGB images
- Hidden layer 1: 256 neurons, ReLU
- Hidden layer 2: 128 neurons, Tanh
- Hidden layer 3: 64 neurons, ReLU
- Output: 10 classes

Main tasks:
- Load and normalize CIFAR-10
- Visualize samples from each class
- Calculate the number of trainable parameters
- Train the model for 30 epochs
- Plot training and test loss
- Plot training and test accuracy
- Analyze overfitting
- Investigate the effect of learning rate
- Add Dropout and evaluate its effect
- Apply data augmentation and compare performance

Notebook: `Q3-cifar10-mlp.ipynb`

---

## Q5 — Cleaning Robot with Q-Learning and SARSA

Train a reinforcement-learning agent to clean a dynamic 10 × 10
grid environment.

The robot can move in four directions or clean its current cell.
The environment contains obstacles and dirty cells, and previously
cleaned cells may become dirty again after a fixed number of steps.

Main tasks:
- Define the grid-world environment
- Design the reward function
- Implement Q-Learning
- Implement SARSA
- Train both agents
- Plot average cumulative reward across episodes
- Compare the learned policies
- Compare the total number of steps required to clean the environment

Notebook: `Q5-cleaning-robot-reinforcement-learning.ipynb`
