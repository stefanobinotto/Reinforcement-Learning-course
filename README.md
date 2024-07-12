# Reinforcement Learning course labs and homeworks
This repo contains my submitted labs and the 2 final evaluated homeworks for the Reinforcement Learning course at UniPD - DEI 2022/23.

## Lab 1 - The 10 Armed Testbed

The main goal of this lab is to take the first steps in the RL world by solving the multi-armed bandit problem, which is addressed through epsilon-greedy, UCB and gradient bandit algorithms.

Notebook: [Lab1](https://github.com/stefanobinotto/Reinforcement-Learning-course/tree/main/lab1)

## Lab 2 - Dynamic Programming and Jack's Car Rental Problem

The main goal of this lab is to help the understanding of the concepts in Dynamic Programming through a concrete example, given by Jack's Car Rental problem.

In particular we will see how the value-function can be computed and how it allows us to better understand the environment, to take meaningful actions.

Notebook: [Lab2](https://github.com/stefanobinotto/Reinforcement-Learning-course/tree/main/lab2)

## Lab 3 - Monte Carlo Methods and Blackjack Problem

With the following notebook we will see in action different algorithms related to the Monte Carlo structure:
1. Monte Carlo algorithm: every-visit implementation, for prediction only
2. Monte Carlo Exploring-Starts: first-visit implementation, for control
3. Off-Policy Monte Carlo: both ordinary and weighted sampling

We will address both the tasks of prediction and control, and we will make use of on-policy and off-policy schemes.

Notebook: [Lab3](https://github.com/stefanobinotto/Reinforcement-Learning-course/tree/main/lab3)

## Lab 4 - Temporal Difference Learning

In this laboratory lecture, we will look at several examples and implementation of algorithms, all related to the idea of temporal difference learning.

The topics are:
- SARSA VS Q-learning
- TD fixed point
- Mountain Car environment & SARSA(λ)

Notebook: [Lab4](https://github.com/stefanobinotto/Reinforcement-Learning-course/tree/main/lab4)

## Lab 5 - Policy Gradient Methods

In this laboratory lecture, we will take a closer look at Policy Gradient methods.

In this notebook, we will understand how the REINFORCE algorithm may be implemented to solve another instance of the class of the gridworld environments: *short corridor*.

Then we will exmaine the simplest example of baseline, which is as easy as it is a powerful method to accelerate the learning of the optimal policy. It serves also as a bridge from the simplest implementation of the Policy Gradient ideas, i.e. the Monte Carlo REINFORCE, to the more advanced Actor-Critic algorithms.

Notebook: [Lab5](https://github.com/stefanobinotto/Reinforcement-Learning-course/tree/main/lab5)

## Homework 1 - Multi-Armed Bandits and Dynamic Programming

The present homework contains 2 exercises, one related to Multi-Armed Bandit problem and the other to Dynamic Programming.

The first part of the homework deals with the Multi Armed Bandit Problem. In particular, the 10-armed testbed environment is exploited in order to understand what happens when dynamics are introduced in the arm rewards.

The second part of the homework consists of a modification of the Jack's Car Rental problem.

Notebook: [HW1](https://github.com/stefanobinotto/Reinforcement-Learning-course/blob/main/homework_projects/2052421_binotto_stefano_hw01.ipynb) | Assessment: 33.3/100

## Homework 2 - Reinforcement Learning with Jackblack

In particular, I will have to implement Monte Carlo algorithm, SARSA-λ and SARSA-λ with action-value function approximation.

In order to test the implementations, I need an environment. Therefore I need also to complete the given code for a modified version of Blackjack game seen in class, called Jackblack, invented by Jack from the car rental.

Notebook: [HW2](https://github.com/stefanobinotto/Reinforcement-Learning-course/blob/main/homework_projects/2052421_binotto_stefano_hw02.ipynb) | Assessment: 80/100
