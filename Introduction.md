## Introduction

Reinforcement learning is a learning what to do — how to map situations to actions — so as to maximize a numerical reward signal.

In the most interesting and challenging cases, actions may affect not only the immediate reward but also the next situation and, through that, all subsequent rewards.

- Reinforcement learning two most important features: **trial-and-error search** and **delayed reward**
- Another feature is it explicitly considers the whole problem of a goal-directed agent interacting with an uncertain environment

**Markov decision process** are intended to include three aspects: sensation, action and goal.

Machine learning paradigm: supervised learning, unsupervised learning and reinforcement learning.

One of the challenges in reinforcement learning is the trade-off between exploration and exploitation.

## 1.2 Examples

## 1.3 Elements of Reinforcement Learning

Sub-elements: the agent, the environment, a policy, a reward signal, a value function and a model of the environment.

- **policy** defines the learning agent's way of behaving at a given time ( a mapping from states to actions )
- **reward signal** defines the goal of a reinforcement learning problem, reward signals may be stochastic functions of the state of the environment and the actions taken
- **value function** specifies what is good in the long run whereas the reward signal indicates what is good in an immediate sense ( the only purpose of estimating values is to achieve more reward )
  - action choices are made based on value judgements
  - the most **important** component is a method for efficiently estimating values
- **model of the environment** is something that mimics the behavior of the environment, allows inferences to be made about how the environment will behave
  - model-based the method that use models and planning
  - model-free explicitly trial-and-error learners

## 1.4 Limitations and Scope

Our concern in this book is deciding what action to take as a function of whatever state signal is available

## 1.5 An Extended Example: Tic-Tac-Toe

## 1.6 Summary

Reinforcement learning is a computational approach to understand and automate goal-directed learning and decision making.

The concepts of value and value function are key to most of the reinforcement learning methods, value functions are important for efficient search in the space of policies.

## 1.7 Early History of Reinforcement Learning