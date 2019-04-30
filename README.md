# CSE5742018

This repository consist of the projects I have completed as part of CSE574 2018 machine Learning course at SUNY University at Buffalo.

I have used googlecolab TPU to run my codes because of the large datasets. The processing time might get very lengthy for some of the projects if you use regular personal computer. 

Project1.1 => Software 1.0 vs Software 2.0.

The project is to compare two problem solving approaches to software development:
the logic-based approach (Software 1.0) and the machine learning approach (Software
2.0). It is also designed to quickly gain familiarity with Python and machine learning
frameworks.

Project1.2 => Learning to Rank using Linear Regression (LeTOR)

The goal of this project is to use machine learning to solve a problem that arises in Information Retrieval,
one known as the Learning to Rank (LeToR) problem. We formulate this as a problem of linear regression
where we map an input vector x to a real-valued scalar target y(x;w).

Project2 => Handwriting Comparison

In this project, three different machine learning models is used to solve handwr iting
compar ison problem. The task is to f ind similar ity between the known and the unknown
handwr itten “AND” samples using Linear Regression, Logistic Regression and Neural
Network. The target value has a value ‘1’ if the writers are same and ‘0’ if the writers
are different. This is a cla ssif ication problem where the target value can have two values
(0 or 1) .

Project3 => Classification

This project is to implement machine learning methods for the task of classification. You will first
implement an ensemble of four classifiers for a given task. Then the results of the individual classifiers
are combined to make a final decision.
The classification task will be that of recognizing a 2828 grayscale handwritten digit image and
identify it as a digit among 0, 1, 2, ... , 9. You are required to train the following four classifiers using
MNIST digit images.
1. Logistic regression, which you implement yourself using backpropagtion and tune hyperparameters.
2. A publicly available multilayer perceptron neural network, train it on the MNIST digit images
and tune hyperparameters.
3. A publicly available Random Forest package, train it on the MNIST digit images and tune
hyperparameters.
4. A publicly available SVM package, train it on the MNIST digit images and tune hyperparameters.


Project4 => Reinforcement Learning

The project combines reinforcement learning and deep learning. Your task is to teach the agent to navigate
in the grid-world environment. We have modeled Tom and Jerry cartoon, where Tom, a cat, is chasing Jerry,
a mouse. In our modeled game the task for Tom (an agent) is to find the shortest path to Jerry (a goal),
given that the initial positions of Tom and Jerry are deterministic. To solve the problem, we would apply
deep reinforcement learning algorithm - DQN (Deep Q-Network), that was one of the first breakthrough
successes in applying deep learning to reinforcement learning.
