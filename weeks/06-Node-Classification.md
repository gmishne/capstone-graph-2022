---
layout: week
title: Week 06
doodle: /doodle.png
---

# Node Classification

## Topics

This week's assignments will guide you through the following topics:
* Carefully framing and understanding a node classification problems


## Reading

Review previous readings as necessary! Nothing new this week.

## Tasks

Node classification attempts to infer properties of nodes from a given
graph. While you have been attempting node classification tasks
already this quarter, this will give you a chance to digest the
materials you've learned so far in the course.

Approach each of the following classification tasks using the
following methods:
* classify nodes using *only* node features via FCN (use no graph
  information).
* classify nodes using *both* node features and ad-hoc graph variables
  for each node (e.g. for a given node use degree, centrality
  measures, sum of words of the neighbors, etc as features).
  - note: _this_ is really the baseline to which one should compare e.g. GCN, n2v.
* classify nodes using *only* graph structure via node2vec (don't use
  features for nodes).
* classify nodes using *both* graph structure and node features by
  concatenating node2vec embeddings and node features.
* classify nodes using GCN (using both node features and graph
  structure).
  
For all of these, expore different architectures and hyperparameters.
  
Compare these models for each classification problem, using standard
metrics (accuracy, precision, recall) and a thoughtful data analysis
(e.g. are false positives more often high degree nodes?). For node2vec
and GCN, plot the dense vector embeddings and try to interpret them
(e.g. use tSNE to plot the embeddings, colored by label or node
degree).

A note on testing: your classification problems should always be
tested in circumstances similar to how the algorithm be used! Graph
problems will either be:
1. Transductive, when the graph structure is fixed ahead of time, but
   the labels remain unknown.
   - e.g. given a fixed set of publications, can you classify them for
     an analysis?
2. Inductive, when the graph evolves/changes post-training.
   - e.g. a publisher has a service: when an author uploads their
     paper, the algorithm recommends a category/tag for labeling the
     paper.

How would you split and perform train/test in these two cases, for
each of the algorithms above?

### Cora classification

You will build on your work last week, attempting node
classification on the cora dataset. While you began a few of these tasks
already, use this opportunity to toy with different network
archtectures and carfully put together a modeling/evaluation
pipeline.

Tip: start writing library functions automating portions for the next
task.

### Other classification

Choose another dataset from SNAP that has a node classification
problem associated to it. Describe a real world situation where this
node classification would be useful (is it inductive or transductive?)
Go through the procedure described above.

## Weekly Questions

Answer the following questions:
* Summarize the results of the Cora classification. Use this
  opportunity to practice presenting a data analysis.
* Do the same for your other classification exercise.
* Summarize how each ML approach handles inductive graph
  learning (adding new nodes and edges at test-time). What computation
  has to occur at test-time?
  
