---
title: "Learning Stochastic Rainbow Networks"
collection: publications
category: conferences
permalink: /publication/learning-srns
date: 2024-10-09
venue: 'NeurIPS Sci4DL Workshop'
paperurl: 'https://openreview.net/pdf?id=bvJ4UGTRtk'
citation: 'Vivian White, Muawiz Sajjad Chaudhary, Guy Wolf, Guillaume Lajoie, and Kameron Decker Harris. Learning stochastic rainbow networks. In NeurIPS 2024 Workshop on Scientific Methods for Understanding Deep Learning, 2024. URL https://openreview.net/pdf?id=bvJ4UGTRtk.'
---

Random feature models are a popular approach for studying network learning that can capture important behaviors while remaining simpler than traditional training. Guth et al. [2024] introduced “rainbow” networks which model the distribution of trained weights as correlated random features conditioned on previous layer activity. Sampling new weights from distributions fit to learned networks led to similar performance in entirely untrained networks, and the observed weight covariance were found to be low rank. This provided evidence that random feature models could be extended to some networks away from initialization. However, White et al. [2024] failed to replicate their results in the deeper ResNet18 architecture. Here we ask whether the rainbow formulation can succeed in deeper networks by directly training a stochastic ensemble of random features, which we call stochastic rainbow networks. At every gradient descent iteration, new weights are sampled for all intermediate layers and features aligned layer-wise. We find: (1) this approach scales to deeper models, which outperform shallow networks at large widths; (2) ensembling multiple samples from the stochastic model is better than retraining the classifier head; and (3) low-rank parameterization of the learnable weight covariances can approach the accuracy of full-rank networks. This offers more evidence for rainbow and other structured random feature networks as reduced models of deep learning.
