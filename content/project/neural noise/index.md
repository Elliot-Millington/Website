---
title: "Neural Noise"
date: 2020-10-22T12:33:51+01:00
description: Training artificial neural networks on simple tasks to make inferences about the early visual system. 
---

In this project I used the Tensor Flow package developed by Google to train an artificial neural network to distinguish whether noisy gabor patches were vertical or horizontal. I then injected internal noise into the model when testing on a test set of data. By comparing the effects of different levels of internal and external noise, I demonstrated a proof-of-concept that different levels of noise will have effects on performance that are not necessarily intuitive.