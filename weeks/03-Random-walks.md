---
layout: week
title: Week 03
doodle: /doodle.png
---

# Random walks on graphs

## Topics

This week's assignments will guide you through the following topics:
* Random walks on graphs
* Implementing an autoencoder

## Reading

A random walk is a very important concept in graph theory. In our capstone it plays a role in unsupervised graph embeddings (deepwalk and node2vec).
Read:
* Random walks on graphs: read first 4 pages of Dan Spielma's [notes](http://cs.yale.edu/homes/spielman/561/lect10-18.pdf)
* [Slides](https://www.ic.unicamp.br/~wainer/cursos/1s2014/2007-10-01.sarkar.pdf) on random walks and their connection to PageRank
* [Random walks and applications of random walks](https://www.cs.rpi.edu/~slotag/classes/FA16/slides/lec20-sample2.pdf) (clustering and classification)

## Coding

Complete the following tasks:

### Random walk
Implement a random walk of length *k* on a graph given the graph and an initial node as inputs.

### Deep networks
An autoencoder is an unsupervised deep learning model that reconstructs the data from itself, and can be used to learn a low-dimensional embedding of data.
Follow this [tutorial](https://medium.com/pytorch/implementing-an-autoencoder-in-pytorch-19baa22647d1) for implementing an autoencoder in pytorch.

## Weekly Questions

Answer the following questions
1. How can random walks be used to cluster data?
2. Plot 10 steps pf a random walk on the [Zachary Karate club graph](https://networkx.org/documentation/stable/reference/generated/networkx.generators.social.karate_club_graph.html?highlight=karate) starting from a random node. More details on this dataset [here](http://networkdata.ics.uci.edu/netdata/html/zacharyKarate.html).
3. Plot several original and reconstructed digits using the autoencoder.
4. Create two variations of the autoencoder by changing the number of hidden units in an encoder (and corresponding decoder layer) or adding / removing an encoder (and corresponding decoder layer). How does this affect the performance of the network (MSE)?

