---
title: "Artificial Neural Networks"
date: 2020-10-22T12:33:51+01:00
summary: Training artificial neural networks on simple tasks to make inferences about the visual system. 
weight: 20

image:
  preview_only: true

---

I have used the [Tensor Flow](https://www.tensorflow.org/) library developed by Google to train several artificial neural networks in categorisation tasks. The most developed of these is a network trained to distinguish whether noisy gabor patches were vertical or horizontal, pictured below.

![noisy gabor patches](Figure_1a.png)

I then injected internal noise into the model when testing on a test set of data. By comparing the effects of different levels of internal and external noise, I demonstrated a proof-of-concept that different levels of noise will have effects on performance that are not necessarily intuitive.

My most recent project using Neural Networks involves using the Tensor Flow framework to make inferences about drawing styles using the [Quick, Draw!](https://github.com/googlecreativelab/quickdraw-dataset) dataset.