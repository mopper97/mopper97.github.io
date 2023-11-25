---
title: "StrAE: Autoencoding for Pre-Trained Embeddings using Explicit Structure"
collection: publications
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: 'We look at the benefits of explicit structure as a way of modelling composition, and the effects this has on representation learning.'
date: 2023-10-01
venue: 'EMNLP Main'
paperurl: 'https://arxiv.org/pdf/2305.05588.pdf'
---
Here we present StrAE: a Structured Autoencoder framework that through strict adherence to explicit structure, and use of a novel contrastive objective over tree-structures, enables effective learning of multi-level representations. Through comparison over different forms of structure, we verify that our results are directly attributable to the informativeness of the structure provided as input, and show that this is not the case for existing tree models. We then further extend StrAE to allow the model to define its own compositions using a simple localised-merge algorithm. This variant, called Self-StrAE, outperforms baselines that don't involve explicit hierarchical compositions, and is comparable to models given informative structure (e.g. constituency parses). Our experiments are conducted in a data-constrained (circa 10M tokens) setting to help tease apart the contribution of the inductive bias to effective learning. However, we find that this framework can be robust to scale, and when extended to a much larger dataset (circa 100M tokens), our 430 parameter model performs comparably to a 6-layer RoBERTa many orders of magnitude larger in size. Our findings support the utility of incorporating explicit composition as an inductive bias for effective representation learning.

[Read Here](https://arxiv.org/pdf/2305.05588.pdf)
