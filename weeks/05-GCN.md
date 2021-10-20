---
layout: week
title: Week 05
doodle: /doodle.png
---

# Intro to GCNs

## Topics

This week's assignments will guide you through the following topics:
* An introduction to Graph Convolutional Networks
* Build a graph convolutional network

## Reading

Please read the following:
* [Semi-supervised classification with graph convolutional networks, Kipf & Welling](https://arxiv.org/pdf/1609.02907.pdf) - focus on sections 1-3.
For high-level overview you can read [Graph Convolutional Networks](http://tkipf.github.io/graph-convolutional-networks/) or watch this [video](https://www.youtube.com/watch?v=9jSFBcptZ9A&ab_channel=ZihaoZhu).
* Read slides 10-38 from the [presentation on GCN](http://snap.stanford.edu/proj/embeddings-www/files/nrltutorial-part2-gnns.pdf)

## Tasks
* Implement a graph convolutional layer in pytorch.
This [tutorial](https://towardsdatascience.com/understanding-graph-convolutional-networks-for-node-classification-a2bfdb7aba7b) implementation in numpy may be helpful.

* Using the layer you implemented, construct a 1-layer GCN and train it on a node classification task for the Cora dataset. Compare the performance of the GCN to a 1-layer FCN on Cora.

## Weekly Questions

Answer the following questions
* Report the accuracy of the GCN and FCN from the task above. Include the hyper-parameters you used to train the network.
* Describe one thing that you found difficult to understand in the paper. Try to be specific about what you don’t think you understand.
* Consider the formulation of a fully connected layer and a graph convolution layer. In what specific case does a graph convolution layer reduce to a fully connected layer?

