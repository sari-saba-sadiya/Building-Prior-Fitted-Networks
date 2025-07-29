# Building Prior Fitted Networks
The ABCs of PFNs, a repo with step be step example on how to build PFNs

## Overview:
The framework of Prior Fitted Networks (PFNs) in an extreme meta-learning approach. Instead of approximating a function based on data and labels, PFNs learn to implicitly predict the task based on *support* data points that have a label, at which point the PFN does prediction like any other model. Less colloquially, PFNs are trained to directly map inputs to posterior predictive distributions, effectively performing Bayesian inference without explicit on-the-fly posterior updates.

The main idea has echos of [Algorithim Distilation](https://arxiv.org/pdf/2210.14215), only instead of learning to simulate RL policy based on examples from for multiple tasks, PFNs simulate  Bayesian inference.

## Reading List
 - Transformers Can Do Bayesian Inference: [Papar](https://arxiv.org/pdf/2112.10510), [code](https://github.com/automl/TransformersCanDoBayesianInference)
 - TabPFN: A Transformer That Solves Small Tabular Classification Problems in a Second
 - Accurate predictions on small data with a tabular foundation model: [Paper](https://www.nature.com/articles/s41586-024-08328-6), [code](https://github.com/PriorLabs/TabPFN)
 - A Closer Look at TabPFN v2: Understanding Its Strengths and Extending Its Capabilities: [Paper](https://arxiv.org/pdf/2502.17361)
