---
layout: week
title: Week 07
doodle: /doodle.png
---

# Link Prediction

## Topics

This week's assignments will guide you through the following topics:
* Introduction to Link Prediction
* Link Prediction using GCN-Autoencoders

## Reading

* Read the 'Entity Resolution and Link Prediction' chapter sent via
  email. Carefully read the setup (first 3 pages) and the case studies
  at the end. Skim the rest.
* Read [this
  tutorial](https://towardsdatascience.com/tutorial-on-variational-graph-auto-encoders-da9333281129)
  on Variational Graph Autoencoders.
* Skim [this paper](https://arxiv.org/abs/1611.07308) on Variational
  Graph Autoencoders.

In the autoencoder readings, do not get too hung-up on the variational
aspects. While it's useful to understand AE vs VAE, you will only have
to implement a G-AE.

## Tasks

* Implement a (non-variational) gcn-autoencoder in PyTorch. Your
  encoder should be 1-3 GCN layers + 1 FC layer. The size of the FC
  layer is the dimension of your dense vector embedding.
* Use the GCN-Autoencoder for a link prediction task. I'm going to
  leave it to you to formulate how to evaluate the task (please
  ask/share on Slack!).

## Weekly Questions

Answer the following questions:
* Create two 4-node graphs of your choice by hand on paper with node
  labels (but no attributes). Begin with a 2-hidden layer GCN with
  weight matrics initialized at 1. Calculate the feed-forward output
  of the graph _by hand_. Compare it to your results using PyTorch.
* What is the loss function for the autoencoder and why is the setup
  appropriate for link-prediction? What if you wanted to take node
  attributes into account as well? How might you change the loss
  function?
* How did you set-up testing your link prediction problem?
* Anything you found difficult understanding, that you'd like
  clarification on?
