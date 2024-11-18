---
title: "Learning and Aligning Structured Random Feature Networks"
collection: publications
category: conferences
permalink: /publication/learning-aligning-srfs
excerpt: 'Learning and Aligning Structured Random Feature Networks'
date: 2024-03-02
venue: 'ICLR Re-Align Workshop'
paperurl: 'https://openreview.net/pdf?id=vWhUQXQoFF'
citation: 'Vivian White, Muawiz Sajjad Chaudhary, Guy Wolf, Guillaume Lajoie, and Kameron Decker Harris. Learning and aligning structured random feature networks. In ICLR 2024 Workshop on Representational Alignment, 2024. URL https://openreview.net/forum?id=vWhUQXQoFF.'
---

Abstract:  Artificial neural networks (ANNs) are considered "black boxes" due to the difficulty of interpreting their learned weights. While choosing the best features is not well understood, random feature networks (RFNs) and wavelet scattering ground some ANN learning mechanisms in function space with tractable mathematics. Meanwhile, the genetic code has evolved over millions of years, shaping the brain to develop variable neural circuits with reliable structure that resemble RFNs. We explore a similar approach, embedding neuro-inspired, wavelet-like weights into multilayer RFNs. These can outperform scattering and have kernels that describe their function space at large width. We build learnable and deeper versions of these models where we can optimize separate spatial and channel covariances of the convolutional weight distributions. We find that these networks can perform comparatively with conventional ANNs while dramatically reducing the number of trainable parameters. Channel covariances are most influential, and both weight and activation alignment are needed for classification performance. Our work out lines how neuro-inspired configurations may lead to better performance in key cases and offers a potentially tractable reduced model for ANN learning.
