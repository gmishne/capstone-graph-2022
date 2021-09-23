---
layout: week
title: Week 01
doodle: /doodle.png
---

# Introduction
This domain centers on an augmeneted data-type: graph-based data, and a class of methods used to analyze such data: geometric deep learning / graph neural networks. The week will provide motivation and an introduciton to both topics.

## Topics

This week's assignments will guide you through the following topics:
- Introduction to machine learning (specifically deep learning) on graphs
- Introduction to implementing deep learning networks in pytorch    

## Reading

Please read the following:
- [What is geometric deep learning?](https://medium.com/@flawnsontong1/what-is-geometric-deep-learning-b2adb662d91d)
- [Machine Learning on graphs](https://towardsdatascience.com/machine-learning-tasks-on-graphs-7bc8f175119a)

## Coding
This capstone will require implementing and training deep networks.
This week we will code simple deep networks from scratch so you understand the underlying machine learning and mathematics that deep learning relies on.
* Read the following tutorial on coding a simple neural network in python with numpy:
https://enlight.nyc/projects/neural-network

Developing and training deep networks is typically done using Python packages such as [pytorch](https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html) or [tensorflow/keras](https://www.tensorflow.org/tutorials).
* This [colab](https://colab.research.google.com/drive/109gHWFUlUzuwhgXROpzIuVoSPZA_qeoy) notebook is a reimplementation of the above numpy code in pytorch.

* The above tutorials implemented a fully-connected layer called [Linear](https://pytorch.org/docs/stable/generated/torch.nn.Linear.html) in pytorch. You can find many more types of layers [here](https://pytorch.org/docs/stable/nn.html). In this [tutorial](https://towardsdatascience.com/handwritten-digit-mnist-pytorch-977b5338e627), a network with 2 fully connected hidden layers is constructed using pytorch Linear layers to classify numerical digits. Please run the code yourself and report your accuracy.

* Comment: To get a better understanding of backpropagation in deep networks this [tutorial](https://towardsdatascience.com/math-neural-network-from-scratch-in-python-d6da9f29ce65) and [video](https://www.youtube.com/watch?v=tIeHLnjs5U8&t=585s&ab_channel=3Blue1Brown) may be useful.


## Weekly Questions

Answer the following questions
- Describe one thing you found interesting in the reading. Describe what it is in your own words and why you found it interesting.
- Describe one thing that you found difficult to understand. Try to be specific about what you don’t think you understand.
- Describe in your own words two machine learning tasks on graphs (2-3 sentences on each task).
