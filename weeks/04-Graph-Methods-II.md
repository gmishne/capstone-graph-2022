---
layout: week
title: Week 04
doodle: /doodle.png
---

# Graph embeddings

## Topics

This week's assignments will guide you through the following topics:
* Graph embeddings

This week we will learn about graph embeddings via node2vec, But to understand node2vec we first need to understand the following:

### Word2Vec - Representing words with vectors
[Word2Vec](https://arxiv.org/pdf/1301.3781.pdf) was published in 2013 in which Mikolov et al. suggest a method to learn distributed representations of words based on the context in which it appears. The problem they is trying to solve is finding features for words. They build upon the distributional hypothesis which suggests that 'words that are used and occur in the same contexts tend to purport similar meanings'. They propose two methods to do the same. 1) CBOW - Continuous Bag of Words and 2) Skip-gram. I highly recommend reading [word2vec-Explained](https://arxiv.org/pdf/1402.3722.pdf) paper before going through the actual [word2vec](https://arxiv.org/pdf/1301.3781.pdf) paper. [This](https://arxiv.org/pdf/1310.4546.pdf) is an extension of word2vec.
If you want to get a feel of what word2vec are or how to use them, this is a very good  [resource](https://gist.github.com/aparrish/2f562e3737544cf29aaf1af30362f469).

### node2vec
Building on the work of word2vec,  [node2vec](https://arxiv.org/pdf/1607.00653.pdf) proposed a method to learn distributed representation for the nodes in a (homogenous) network. They propose a biased random walk procedure to explore the network and learn the embeddings using the same. You can refer  [DeepWalk](https://arxiv.org/pdf/1403.6652.pdf) if you find node2vec abstruse as it builds upon DeepWalk.


## Reading
Please go through  [word2vec-Explained](https://arxiv.org/pdf/1402.3722.pdf) and  [node2vec](https://arxiv.org/pdf/1607.00653.pdf) prior to this week's discussion. It is completely fine if you don't understand them completely but please try to understand the problem they are trying to solve.

## Links
[The Illustrated Word2vec](http://jalammar.github.io/illustrated-word2vec/)\
[Skip-Gram tutorial](http://mccormickml.com/2016/04/19/word2vec-tutorial-the-skip-gram-model)\
[Word2Vec](https://arxiv.org/pdf/1301.3781.pdf)\
[Word2Vec's extension](https://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf)\
[Word2Vec Explained](https://arxiv.org/pdf/1402.3722.pdf)\
[DeepWalk](https://arxiv.org/pdf/1403.6652.pdf)\
[node2vec](https://arxiv.org/pdf/1607.00653.pdf)\
[node2vec tutorial](https://towardsdatascience.com/node2vec-embeddings-for-graph-data-32a866340fef)
[node2vec source code](https://pytorch-geometric.readthedocs.io/en/latest/_modules/torch_geometric/nn/models/node2vec.html)

## Weekly Questions

Answer the following questions:

Q1. What graph-based analysis problem is node2vec trying to solve?

Q2. How is node2vec related to random walks?

Q3. Describe one thing that you found difficult to understand in the node2vec paper. Try to be specific about what you don’t think you understand.


